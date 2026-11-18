# yeakin.me

Personal portfolio of Hossain Ahmed Yeakin. Static site, no build step.

## Structure
- `index.html` – markup
- `css/styles.css` – all styles
- `js/intro.js` – intro animation
- `js/main.js` – page effects, nav, theme, and the lazy loader for the chatbot
- `js/blog.js` – blog data and views
- `js/chat.js` – "Yaki" chatbot, loaded on idle or on first click
- `assets/` – images
- `_headers` – long cache rules (Cloudflare Pages / Netlify)

## Run locally
    python3 -m http.server 8000
then open http://localhost:8000
