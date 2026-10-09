# Vistaar Public Research page

The Research & Advisory page for [Vistaar WebX](https://www.vistaarwebx.com/). It follows the design system of the Vistaar About page: Geist type, brand red `#b41f24`, warm surface `#f6f5f3`, red-dot eyebrows and numbered rows.

`index.html` is self-contained. All CSS and JS are inline, and the only external request is the Geist font from Google Fonts. To preview it, open the file in a browser or run `npx serve .`.

## Sections

1. **Hero:** "Research should improve decisions", with a diagram of the open knowledge initiative (research, field observations, datasets, experiments → structured knowledge).
2. **At a glance:** 7 practice areas, 5 methods, 8 impact dimensions, 4 open formats.
3. **Two kinds of research:** client research and public research, joined by an "only with permission" gate.
4. **Seven practice areas:** a numbered list. AI & Future of Work is tagged *New in 2026*.
5. **How we research:** methods → analysis → findings → decisions, followed by "AI speeds up the analysis. Judgement stays human."
6. **Impact assessment framework:** eight dimensions, each with its question.
7. **Our research standard:** method, what the evidence does not prove, and limitations. Client data needs permission before it becomes public research.
8. **Contact** and the footer.

## Before going live

- Nav and footer links to *About us*, *Our services*, *Career* and *Flowbit* are `#` placeholders. Point them at the real routes.
- Add a `<link rel="canonical">` and an `og:url` once the final URL is known.
