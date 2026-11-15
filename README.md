<p align="center"><img src="https://www.11ty.dev/img/logo-github.svg" width="200" height="200" alt="eleventy Logo"></p>

# 11ty.dev 🕚⚡️🎈🐀

- https://www.11ty.dev/

The website and documentation for the [Eleventy static site generator](https://github.com/11ty/eleventy/).

## Running Locally

Use Node.js 22.15 or newer. The data-refresh script uses POSIX shell commands,
and the production scripts use POSIX environment-variable assignments. On
Windows, use WSL or configure npm to use a POSIX script shell such as Git Bash.

```
npm install
npm run get-new-data
npm start
```

Browse to http://localhost:8091/ (`npm start` sets port 8091; if the server selects
a different available port, use the address it prints).

Refresh community data with `npm run get-new-data`. There is no
`get-new-supporters` script in this checkout.
