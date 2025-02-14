## Documenting other content.

Only frontend components documentation is generated from the source code. Rest (for example, chrome documentation) must be wirrten. The documentation is using [next.js](https://nextjs.org/docs/getting-started) framework. If you are not familiar with it, check the documentation. In short the next.js is a SSR framework for react. The only thing you have to know, is that it uses filesystem routing, meaning that the routes are equal to a directory tree under `/packages/docs/pages`. Pages can be `.js` or `.md` files. Because we use `MDX` we suggest using `.md` as you can use both Markdown and JSX syntax.

Let's add a new page to the `/chrome` directory.

1. Go to <a href="http://localhost:3000/chrome" target="_blank">http://localhost:3000/chrome</a>
2. Create new file `/packages/docs/pages/chrome/example.md`. Immediately you will notice a new entry in the left nav pops up with `Example` title.
3. Click on the new link open <a href="http://localhost:3000/chrome/example" target="_blank">http://localhost:3000/chrome/example</a> link.
4. Start editing the `/packages/docs/pages/chrome/example.md` file.
5. If you have to create proprietary components for your documentation page, please place them at `/packages/docs/components/<section-name>/<component-name>.js`.