# Nuxt 3 + Tailwind CSS 4 Boilerplate

A modern boilerplate for building web applications using Nuxt 3, Tailwind CSS 4, and essential developer tools.

## Features

- **Nuxt 3** - The powerful Vue framework for building server-side rendered, static, and hybrid applications.
- **Nuxt Content** - Markdown-based content management system.
- **Nuxt UI** - Pre-built UI components for faster development.
- **Tailwind CSS 4** - Utility-first CSS framework for rapid styling.
- **PNPM** - Efficient and fast package manager.
- **ESLint** - Code quality and formatting enforcement.

## Getting Started

### Prerequisites

Ensure you have the following installed on your system:
- [Node.js](https://nodejs.org/) (LTS recommended)
- [PNPM](https://pnpm.io/)

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/tfd-ed/nuxt3-tailwind4-boilerplate.git
   cd nuxt3-tailwind4-boilerplate
   ```
2. Install dependencies:
   ```sh
   pnpm install
   ```
3. Start the development server:
   ```sh
   pnpm dev
   ```

### Build for Production

To generate a production build:
```sh
pnpm build
```

To preview the production build:
```sh
pnpm preview
```

## Project Structure

```
Nuxt3-Tailwind4-Boilerplate/
├── components/        # Vue components
├── content/           # Markdown-based content
├── layouts/           # Layout components
├── pages/             # Nuxt pages
├── public/            # Static assets
├── nuxt.config.ts     # Nuxt configuration
├── tailwind.config.js # Tailwind CSS configuration
└── eslint.config.mjs  # ESLint configuration
```
## Acknowledgment
Thanks to:
- [HyperUI](https://www.hyperui.dev/) for providing ready-to-use tailwind components 

## Contribution Guide

We welcome contributions! Please follow these steps to contribute:

1. **Fork the Repository** - Click the "Fork" button on the top-right corner of this repository.
2. **Clone Your Fork** -
   ```sh
   git clone https://github.com/tfd-ed/nuxt3-tailwind4-boilerplate.git
   cd nuxt3-tailwind4-boilerplate
   ```
3. **Create a New Branch** -
   ```sh
   git checkout -b feature-branch-name
   ```
4. **Make Changes** - Modify code and commit changes following conventional commit messages.
5. **Push Your Changes** -
   ```sh
   git push origin feature-branch-name
   ```
6. **Submit a Pull Request** - Open a pull request in this repository.

### Code Guidelines
- Follow ESLint rules.
- Use meaningful commit messages.
- Write clear and concise documentation for any changes.

## License

This project is licensed under the [MIT License](LICENSE).