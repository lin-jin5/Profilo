
Here is a suggested `README.md` that summarizes the project based on the analysis:

# Hesed's Web3 Vista Portfolio

This repository contains the source code for my personal portfolio website, showcasing my work as a **Creative Web3 Developer and Block Adoption Advocate**.

The site is built with **Next.js**, styled using **Tailwind CSS**, and leverages functional UI components for a modern, dark-themed experience.

## Key Features & Tech Stack

*   **Framework**: Next.js (App Router)
*   **Styling**: Tailwind CSS with a custom dark theme configuration (including a bold violet primary color).
*   **UI/UX**: Custom components based on Radix UI primitives (via shadcn/ui).
*   **Animations**: Framer Motion is used for subtle section transitions.
*   **Navigation**: Smooth scrolling navigation using a unique horizontal scroll-snap layout for main sections and a fixed vertical navigation bar.
*   **AI Integration**: Boilerplate for Genkit integration with Google AI (`gemini-2.5-flash`) is present for potential future AI-powered features.

### Design Highlights (from `docs/blueprint.md`)
*   **Color Palette**: Deep gray background (`#0A0A0A`), bold violet primary (`#A78BFA`), and soft blue accent (`#5AA9E6`).
*   **Typography**: Headline font is **'Pixelify Sans'** for a distinctive look, with a standard sans-serif for the body.

## Project Structure

The site is composed of several distinct sections, all laid out in `src/app/page.tsx`:

*   **Hero**: Introduction and primary call-to-action.
*   **About**: A personal summary section.
*   **Skills**: Interactive display of technical proficiencies (Web2, Web3, Design).
*   **Projects**: Showcase of key projects with stack details and links.
*   **Experience**: A vertical representation of professional/internship history.
*   **Contact**: Links to professional profiles (Email, GitHub, LinkedIn, X).

## Development & Setup

### Requirements

*   Node.js (version compatible with `package.json` dependencies, likely Node 20+ is best).
*   Yarn or npm for package management.

### Local Setup

1.  **Clone the repository**:
    ```sh
    git clone <repository-url>
    cd lin-jin5-profilo
    ```

2.  **Install dependencies**:
    ```bash
    yarn # or npm install
    ```

3.  **Environment Variables**: Create a `.env` file in the root directory (based on standard Next.js projects, though not explicitly shown, Genkit/Firebase often require them).

### Running Commands

*   **Start Development Server (with Turbopack)**:
    ```sh
    yarn dev
    ```

*   **Run AI Flows (Genkit)**:
    ```sh
    yarn genkit:dev
    ```

*   **Build for Production**:
    ```sh
    yarn build
    ```

*   **Type Check**:
    ```sh
    yarn typecheck
    ```

## Configuration

*   **Tailwind CSS**: Custom color themes and font definitions are configured in `tailwind.config.ts`.
*   **Next.js**: Configuration, including allowed remote image hostnames, is in `next.config.ts`.
*   **Shadcn Aliases**: Component path aliases are defined in `components.json`.
