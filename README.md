# SnapShop

An eCommerce web app built with React.js

## Web app link

- Web app deployed at: [SnapShop](https://snapshop-ul.netlify.app/)

## Hosting

- Frontend hosted at [Netlify](https://www.netlify.com/)
- Backend web service deployed at [Render](https://render.com/): https://snapshop-mock-server.onrender.com

## Localhost JSON commands (json-server):

<!-- JSON Server -->
- `json-server --watch data/db.json --port 8000`

<!-- JSON Server and Auth -->
- `json-server data/db.json -m ./node_modules/json-server-auth --port 8000`

<!-- JSON Server and Auth with routes -->
- `json-server data/db.json -m ./node_modules/json-server-auth -r data/routes.json --port 8000`
