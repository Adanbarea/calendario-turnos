# Calendario de Turnos · web

Public pages of the Calendario de Turnos Android app, served by GitHub Pages at
https://adanbarea.github.io/calendario-turnos/ (the app's own repository, `CalendarioTurnos`, is private):

- `index.html`: home page.
- `privacidad.html`: privacy policy, in Spanish and English. It is the URL given to Google Play
  (Policy → App content → Privacy policy), so if it moves, change it there too.

Plain HTML and one stylesheet (`estilo.css`), with no build step and nothing loaded from elsewhere.

GitHub Pages publishes the **`gh-pages`** branch (it switched itself on when that branch was pushed).
Keep `main` and `gh-pages` equal: commit on `main`, then `git push origin main main:gh-pages`.
