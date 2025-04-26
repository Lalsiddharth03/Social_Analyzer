
# Social Network Project

## Overview

This is a full-stack Social Network application built with:
- **Frontend**: React, TypeScript, Tailwind CSS, Vite
- **Backend Functions**: Supabase Edge Functions
- **Additional Processing**: Custom C++ processing (`processor.cpp`)

It allows users to interact on a social platform with enhanced performance using custom backend logic.

---

## Project Structure

```
project/
│
├── src/                  # Frontend source code (React + Tailwind)
├── dist/                 # Production build output
├── supabase/functions/   # Supabase Edge Functions (serverless backend)
├── .bolt/                # AI-driven configuration prompts
├── processor.cpp         # Additional C++ processing logic
├── package.json          # Node dependencies and scripts
├── tailwind.config.js    # Tailwind CSS configuration
├── vite.config.ts        # Vite build configuration
└── .env                  # Environment variables
```

---

## Installation and Setup

1. **Clone the repository** (if not already):

    ```bash
    git clone <repo-url>
    cd project
    ```

2. **Install Node.js dependencies**:

    ```bash
    npm install
    ```

3. **Set up environment variables**:

    - Create a `.env` file (already included).
    - Configure your Supabase project credentials and API keys inside `.env`.

4. **Run the development server**:

    ```bash
    npm run dev
    ```

5. **Build for production**:

    ```bash
    npm run build
    ```

6. **Running the C++ Processor** (optional):

    - Compile `processor.cpp`:

    ```bash
    g++ processor.cpp -o processor
    ./processor
    ```

---

## Deployment

You can deploy this app using:
- **Vercel**, **Netlify**, or any static site hosting for the frontend.
- **Supabase Functions** for backend serverless functions.

---

## Technologies Used

- React
- TypeScript
- Tailwind CSS
- Vite
- Supabase
- C++ (for custom backend processing)

---

