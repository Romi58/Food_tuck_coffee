# Coffee Website

Coffee is a modern and interactive website designed for seamless user engagement. Built with Next.js, TypeScript, and Tailwind CSS, it offers a fast, responsive, and visually appealing interface.

## Features

- **Fast & Responsive**: Optimized for all devices with a mobile-first approach.
- **Modern UI/UX**: Clean and engaging design for the best user experience.
- **API Integration**: Fetch and display dynamic data effortlessly.
- **SEO Optimized**: Ensures high visibility and better ranking on search engines.
- **Dark Mode Support**: User-friendly dark/light mode toggle.

## Tech Stack

- **Frontend**: Next.js, TypeScript, Tailwind CSS
- **Backend (Optional)**: Node.js with Express or any API service
- **State Management**: React Context API or Zustand (optional)

## Installation

To set up the project locally:

1. Clone the repository:
    ```bash
    git clone https://github.com/Romi58/Food_tuck_coffee.git
    ```

2. Navigate to the project folder:
    ```bash
    cd cooee-website
    ```

3. Install dependencies:
    ```bash
    npm install
    ```

4. Start the development server:
    ```bash
    npm run dev
    ```

5. Open `http://localhost:3000` in your browser.

## Usage

- **Home Page**: Engaging introduction to the platform.
- **About Page**: Detailed information about Cooee.
- **Features Page**: Highlights the key functionalities of the website.
- **Contact Page**: Enables users to get in touch.

## Folder Structure


## API Integration

If your project includes API calls, you can use:

```typescript
import { useEffect, useState } from 'react';

const useData = () => {
    const [data, setData] = useState([]);

    useEffect(() => {
        fetch('/api/data')
            .then((response) => response.json())
            .then((data) => setData(data));
    }, []);

    return data;
};
