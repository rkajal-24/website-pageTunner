# website-pageTunner

project installation command

Backend
1)  terminal command: npm i

Frontend
1) terminal command: npm i
2) tailwind command in terminal:  npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init 

3) tailwind file changed content:

   // eslint-disable-next-line no-undef
const flowbite = require("flowbite-react/tailwind");
/** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
    flowbite.content(),
  ],
  theme: {
    extend: {},
  },
  plugins: [flowbite.plugin()],
}
