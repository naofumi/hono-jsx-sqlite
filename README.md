# Hono + Hotwire

Example TODO application based on Yusuke Wada ["Hono + htmx + Cloudflare is a new stack"](https://blog.yusu.ke/hono-htmx-cloudflare/)

Instead of HTMX, we use Hotwire (Turbo + Stimulus) and run on Node.js. We also run on our own SQLite.

```
npm install
npm run dev
```

Create Database table `todos` with `id` and `title` columns using your database management tools inside the `db` folder.

```
open http://localhost:3000
```
