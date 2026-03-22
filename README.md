npx create-next-app@latest rs3-technology --typescript --app
cd rs3-technology
npm install tailwindcss postcss autoprefixer
npx tailwindcss init -p
{
  "name": "rs3-technology",
  "version": "1.0.0",
  "private": true,
  "scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "next start",
    "lint": "next lint"
  },
  "dependencies": {
    "next": "latest",
    "react": "latest",
    "react-dom": "latest"
  },
  "devDependencies": {
    "typescript": "^5",
    "tailwindcss": "^3",
    "postcss": "^8",
    "autoprefixer": "^10"
  }
}
