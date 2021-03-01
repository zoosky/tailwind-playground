# Tailwind CSS Playground

Create the project

     yarn create @vitejs/app 

From the templates choose `vanilla`.

    yarn add tailwindcss@latest postcss@latest autoprefixer@latest  --dev

    yarn tailwindcss init -p

Remove the contents of `./style.css` and replace it with this

    @tailwind base;
    @tailwind components;
    @tailwind utilities;

Add a link to the `styles.css` to the `index.html`

    <link rel="stylesheet" href="/style.css">

Empty the contents of `main.js`

Start developing

    yarn dev

And open the page in a browser.

Now edit `index.html` and add a `h1` heading as follows:

    <h1 class="text-3xl md:text-5x1 text-gray-500 text-center font-semibold mx-auto">
        Hello World! How does this look?</h1>


A nice [Youtube video tutorial](https://www.youtube.com/playlist?list=PL5f_mz_zU5eXWYDXHUDOLBE0scnuJofO0) by Tailwind Labs gets you further..