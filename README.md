# Awwwards-Winning Website Clone

This project is a clone coding exercise based on a tutorial by JavaScript Mastery, aiming to replicate an Awwwards-winning website. It focuses on modern web development techniques, including advanced animations and a responsive user interface.

Original Tutorial: [JavaScript Mastery - Build an Awwwards Winning Website](https://youtu.be/zA9r5zTllx4?si=WMwbdGdGT5KwuP6d)

## Features

*   **React & TypeScript:** Built with a modern JavaScript library for user interfaces and a strong typing system for robust code.
*   **Tailwind CSS:** A utility-first CSS framework for rapid UI development and custom designs.
*   **GSAP (GreenSock Animation Platform):** Used for creating high-performance animations.
*   **Vite:** A fast frontend build tool that significantly improves the development experience.
*   **Responsive Design:** Adapts to various screen sizes for a seamless experience on desktops, tablets, and mobile devices.
*   **ESLint & Prettier:** Configured for code linting and formatting to maintain code quality and consistency.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

*   [Node.js](https://nodejs.org/) (v18.x or later recommended)
*   [pnpm](https://pnpm.io/installation) (Package manager used for this project)

### Installation

1.  Clone the repository:
    ```bash
    git clone https://github.com/your-username/your-repository-name.git
    ```
    (Replace `your-username/your-repository-name` with the actual remote URL if you plan to push this to a new repo)
2.  Navigate to the project directory:
    ```bash
    cd your-repository-name
    ```
3.  Install dependencies:
    ```bash
    pnpm install
    ```

### Running the Development Server

To start the development server, run:

```bash
pnpm dev
```

This will open the project in your default browser, usually at `http://localhost:5173`. The server supports Hot Module Replacement (HMR), so changes in the code will reflect live in the browser.

### Building for Production

To create a production build, run:

```bash
pnpm build
```

The optimized static assets will be placed in the `dist/` directory.

### Linting

To check the code for linting issues, run:

```bash
pnpm lint
```

## Project Structure

The project follows a standard Vite + React project structure:

```
.
├── public/              # Static assets (images, fonts, etc.)
├── src/
│   ├── components/      # Reusable React components
│   ├── App.tsx          # Main application component
│   ├── main.tsx         # Entry point of the application
│   ├── index.css        # Global styles
│   └── ...              # Other TypeScript/TSX files
├── .gitignore           # Specifies intentionally untracked files that Git should ignore
├── eslint.config.js     # ESLint configuration
├── index.html           # Main HTML file
├── package.json         # Project metadata and dependencies
├── pnpm-lock.yaml       # Exact versions of dependencies
├── tsconfig.json        # TypeScript compiler options
└── vite.config.ts       # Vite configuration
```

## Learn More

*   Explore more Awwwards-winning sites: [Awwwards](https://www.awwwards.com/)
*   Learn more about the technologies used:
    *   [React](https://react.dev/)
    *   [TypeScript](https://www.typescriptlang.org/)
    *   [Tailwind CSS](https://tailwindcss.com/)
    *   [GSAP](https://gsap.com/)
    *   [Vite](https://vitejs.dev/)