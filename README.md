# Qwik qwik-react-demo ⚡️

[![ITMan - Tech #23 - Qwik: Framework reimagined for the edge!](https://i.ytimg.com/vi/bqHBUpGAT-w/hqdefault.jpg)](https://www.youtube.com/watch?v=bqHBUpGAT-w)

- File based routing and MDX support
- Vite.js tooling.
- Express.js server.
- Prettier code formatter.
- Use React components into your Qwik app

## Development Builds

### Client only

During development, the index.html is not a result of server-side rendering, but rather the Qwik app is built using client-side JavaScript only. This is ideal for development with Vite and its ability to reload modules quickly and on-demand. However, this mode is only for development and does not showcase "how" Qwik works since JavaScript is required to execute, and Vite imports many development modules for the app to work.

```
pnpm run dev
```

### Server-side Rendering (SSR) and Client

Server-side rendered index.html, with client-side modules prefetched and loaded by the browser. This can be used to test out server-side rendered content during development, but will be slower than the client-only development builds.

```
pnpm run dev.ssr
```

## Production Builds

A production build should generate the client and server modules by running both client and server build commands.

```
pnpm run build
```

### Client Modules

Production build that creates only the client-side modules that are dynamically imported by the browser.

```
pnpm run build.client
```

### Server Modules

Production build that creates the server-side render (SSR) module that is used by the server to render the HTML.

```
pnpm run build.ssr
```

## Express Server

This app has a minimal [Express server](https://expressjs.com/) implementation. After running a full build, you can preview the build using the command:

```
pnpm run serve
```

Then visit [http://localhost:8080/](http://localhost:8080/)

---

## Related

- [Qwik Docs](https://qwik.builder.io/)
- [Qwik Github](https://github.com/BuilderIO/qwik)
- [@QwikDev](https://twitter.com/QwikDev)
- [Discord](https://qwik.builder.io/chat)
- [Vite](https://vitejs.dev/)
- [Partytown](https://partytown.builder.io/)
- [Mitosis](https://github.com/BuilderIO/mitosis)
- [Builder.io](https://www.builder.io/)

## Author

👤 **Dung Huynh**

- Website: https://productsway.com/
- Twitter: [@jellydn](https://twitter.com/jellydn)
- Github: [@jellydn](https://github.com/jellydn)

## Show your support

Give a ⭐️ if this project helped you!

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/Q5Q61Q7YM)

---
