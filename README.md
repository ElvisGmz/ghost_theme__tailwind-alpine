# GhostTA
Customizable Ghost Theme builded in TailwindCSS &amp; AlpineJS

# How to use it
First download the `Ghost_TA.zip` from this repository.

Then you just have to go to your Ghost Dashboard, then go to `Settings > Themes > Upload Theme`.

You will see the box to upload your `Ghost_TA.zip` file and then click Activate.

# How to modify the theme
You open your `Ghost` folder and in it you must go to `/content/themes/` and open the `Ghost_TA` folder. Finally you should only open this folder with your favorite code editor.

You must run `npm install` to be able to modify the theme, since it requires some packages for the compilation of changes.

If you add a class or remove another you can run `npm run build` to rebuild the CSS, you also have at your disposal the `tailwind.config.css` file to be able to create or modify your configuration.

Much work to recharge? You just have to run the command `npm run watch` and now you will have the terminal automatically compiling your Tailwind CSS every time you make a change either in the configuration or in your layout.

To view the changes you only have to reload the page, in case it does not work reload by clearing the browser cache (in Firefox & Chrome you can reload without cache with the shortcut `CTRL + F5` or` Shift + Command + R`).

Note: remember that the terminal must be located in the theme folder to be able to execute the commands included in the theme

# More documentation on TailwindCSS & AlpineJS
[TailwindCSS Docs](https://tailwindcss.com/docs)
[AlpineJS Docs](https://alpinejs.dev/start-here)
