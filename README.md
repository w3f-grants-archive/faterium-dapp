# Faterium Decentralized Application

Faterium - a place where fates are forged.

Published by [Cloudflare Pages](https://pages.cloudflare.com/). Look at the [Astro](https://astro.build) documentation to learn more. Also, we use [WindiCSS](https://windicss.org/) and [SCSS](https://sass-lang.com/) preprocessors.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command				| Action											 |
| :--------------------- | :------------------------------------------------- |
| `npm install`		  | Installs dependencies							  |
| `npm run dev`		  | Starts local dev server at `localhost:3000` and connects to `dapp-*.faterium.com` |
| `npm run dev:local`	| Starts local dev server at `localhost:3000` and connects to `localhost:9944` and `localhost:8090` |
| `npm run build`		| Build your production site to `./dist/`			|
| `npm run preview`	  | Preview your build locally, before deploying	   |
| `npm run astro ...`	| Run CLI commands like `astro add`, `astro preview` |
| `npm run astro --help` | Get help using the Astro CLI					   |

## Local setup

If you want to run local node, server, and dapp - use our [Launch local network](https://github.com/faterium/faterium-server#docker-and-local-network) from our `faterium-server` repository to launch `faterium-node`, `faterium-server`, and `polkadot-apps` locally.

Then run the following command to launch and connect to local services:

```sh
npm run dev:local
```
