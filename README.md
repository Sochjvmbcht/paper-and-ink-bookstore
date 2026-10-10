# Paper & Ink — Independent Bookstore

Individual single-page HTML/CSS assignment by **Mohammad Sohail Shaik**, Team 9, Group B.

## Open the project

Open `index.html` in any modern browser. No installation, frameworks, JavaScript, or external assets are needed.

## Assignment checklist

- [x] One responsive HTML5 page
- [x] Semantic `header`, `nav`, `main`, `section`, `article`, `footer`
- [x] Exactly one `h1`
- [x] Navigation links point to real page sections
- [x] Global `box-sizing: border-box`
- [x] Custom CSS color variables defined in `:root`
- [x] Flexbox used in header, navigation, benefits, event cards, and footer
- [x] CSS Grid used for the hero, product grids, event grid, and about section
- [x] Fiction, nonfiction, staff picks, and community events
- [x] Mobile and tablet media queries; no sideways page scrolling
- [x] Keyboard-accessible skip link and visible focus outline

## Code you should understand before the assessment

1. **HTML structure:** `<header>` contains the navigation, `<main>` contains the page content, `<section>` groups categories, and `<footer>` ends the page.
2. **Navigation:** `href="#fiction"` scrolls to `<section id="fiction">`. All navigation targets exist.
3. **CSS variables:** `--forest`, `--paper`, and other colors are defined in `:root` and reused through `var(...)`.
4. **Flexbox:** `.nav-wrap` lays out brand and navigation, while `.benefits` displays three benefits horizontally and wraps as needed.
5. **CSS Grid:** `.book-grid` shows three columns on desktops, two on tablets, and one on phones.
6. **Responsive design:** `@media (max-width: 900px)` and `@media (max-width: 620px)` adapt the layout.
7. **`box-sizing: border-box`:** width includes padding and border, helping layouts fit the screen.
8. **Book covers:** colored book covers are created with CSS rather than external image files.

## Simple demo talk track (about 45 seconds)

"This is my independent bookstore site, Paper & Ink. I used semantic HTML5 with one main heading and section IDs so every navigation link works. The fiction, nonfiction, and staff-pick books are arranged with CSS Grid. I also used Flexbox for the header, benefit strip, and event cards. All colors are defined as CSS variables, and my media queries change the grid from three columns on desktop to two on tablet and one on mobile. I created the book-cover designs in CSS, so the page works without external images or frameworks."

## GitHub: make your own authentic commits

Do not claim commits or collaboration you have not performed. As you personally review and improve the page, commit your own changes in small steps, for example:

```bash
git init
git add index.html README.md
git commit -m "Create first responsive bookstore page"
# Make a real edit (e.g. adjust a color or add a book) after checking your code:
git add index.html
git commit -m "Refine book cards and responsive layout"
```

Create an empty GitHub repository, then follow the "push an existing repository" commands provided by GitHub. The main branch, remote, and repository URL depend on your setup.

**Note:** Event dates and book prices are sample content for this learning project, not real inventory or reservations. The team can agree on one shared visual direction while keeping each person's code separate.
