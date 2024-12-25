->npm install -D tailwindcss postcss autoprefixer vite
->npx tailwindcss init
->add ["*"] in "tailwind.config.js" file...

like this:

content: ["*"],

And then go to package.json file and add this:

"scripts": {
    "start": "vite"
},