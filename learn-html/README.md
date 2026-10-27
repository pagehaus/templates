# Sam's site, from the Learn HTML course

This is the website you build in [Learn HTML](https://pagehaus.app/learn/html), a free course of eight short lessons,
as it is at the end of the last one. Compare it with yours when something doesn't work, or read it to see how the
pieces fit together.

| File | Made in |
|---|---|
| `index.html` | [Lesson 1](https://pagehaus.app/learn/html/your-first-page) to [lesson 3](https://pagehaus.app/learn/html/links-and-images): the home page, its text, links and photo |
| `recipes.html`, `recipes/sourdough.html`, `images/` | [Lesson 4](https://pagehaus.app/learn/html/more-pages-and-folders): more pages, and folders |
| `style.css` | [Lesson 5](https://pagehaus.app/learn/html/style-with-css): colours, fonts and layout |
| `includes/menu.html`, `includes/footer.html` | [Lesson 6](https://pagehaus.app/learn/html/shared-header-and-footer): one menu and footer for every page |
| `contact.html`, `thanks.html` | [Lesson 7](https://pagehaus.app/learn/html/contact-form): a contact form |
| `404.html`, the `description` tags | [Lesson 8](https://pagehaus.app/learn/html/put-it-online): putting it online |

## Seeing it

The pages share their menu and footer through [Server Side Includes](https://pagehaus.app/help/server-side-includes),
so they need a web server. Opened straight from your computer, they show without the menu and footer.

- On your computer: `pagehaus serve` in this folder, then open http://localhost:8080
  ([the pagehaus tool](https://pagehaus.app/cli)).
- Online: upload the contents of this folder to a [Pagehaus](https://pagehaus.app) site. The contact form works there
  as it is.

Free for any use ([MIT](../LICENSE)). The photo is a drawing, made for the course.
