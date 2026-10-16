# Dog-Ear Books

A single-page website for an independent bookstore. This is my own version of a group project: our team agreed on the same idea and look, but each of us built our own site from scratch in our own repo.

Built with plain HTML5 and CSS3. No frameworks, no JavaScript.

## What's on the page

- A header with navigation links that scroll to each section
- A short intro at the top
- Three book sections (fiction, nonfiction and staff picks) laid out as product cards
- An events section for readings and book clubs
- A footer with opening hours and contact details

## Folder structure

```
index.html
css/
  style.css
media/
  (book cover images, SVG)
```

## How to run it

There's nothing to install. Download or clone the repo and open `index.html` in a browser.

```
git clone <your-repo-link>
```

## Notes on how it's built

- Semantic tags are used for the page structure (`header`, `nav`, `main`, `section`, `article`, `footer`), with one `h1`.
- `box-sizing: border-box` is set on everything, and all colours come from CSS variables in `:root`.
- Flexbox is used for the header, nav, card layout, event dates and footer.
- Grid is used for the book cards and the events list. The book grid uses `auto-fit` with `minmax`, so it changes the number of columns by itself as the screen gets narrower.
- It has been checked at phone, tablet and desktop widths, and there is no horizontal scrolling.

## About the content

The shop name, book titles, authors, prices and events are made up for this assignment. The book covers are simple SVG placeholders I made, not real covers.

## Team

This is one of several sites built by our group using the same brief.

- Bookstore C-4:
- Elsie
- Gabriel 


## Use of AI

I used AI to help get started and to understand parts of the code. I went through the code myself and can explain how it works.
