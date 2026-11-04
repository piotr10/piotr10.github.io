# piotr10.github.io

Personal portfolio of **Piotr Czerski, Senior SQL Developer** (MS SQL Server, T-SQL, SSIS, SSRS, Power BI).

**Live:** https://piotr10.github.io

## The idea

Scrolling moves a camera *into* the page instead of down it. Each section is a level nested inside the previous one, like going deeper into a database: `PIOTR-SQL01 › Career › dbo.Projects › dbo.Skills › @contact`.

- 3D depth transitions with CSS `perspective` and `translate3d`, driven by scroll and eased with `requestAnimationFrame`
- An endless tunnel of result-grid frames and drifting T-SQL keywords drawn on `<canvas>`
- A colour theme per level, blended continuously while you travel
- An `about_me.sql` query that types itself and returns my career as a result set

## Accessibility & fallbacks

- Phones, tablets and short screens get a regular scrolling layout with gentle reveals
- `prefers-reduced-motion` disables the camera, typing and animations
- Keyboard: PageUp/PageDown, arrows, Home/End; focusing a link on a far level flies you there

No frameworks and no build step: one `index.html` with plain HTML, CSS and JavaScript.
