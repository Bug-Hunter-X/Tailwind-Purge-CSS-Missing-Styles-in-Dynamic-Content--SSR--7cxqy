# Tailwind Purge CSS Issue with Dynamic Content in SSR

This repository demonstrates a bug where Tailwind CSS's purge feature fails to include styles for dynamically generated content in a Next.js/Nuxt.js application using server-side rendering (SSR).  This results in missing styles on the client-side.

## Steps to Reproduce

1. Clone this repository.
2. Install dependencies: `npm install`
3. Run the development server: `npm run dev`
4. Observe the missing styles on certain components when viewing the page initially.