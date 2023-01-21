<br>

<div align="center">
    <img src="https://raw.githubusercontent.com/StarlaneStudios/cirql/main/.github/branding/logo.png">
</div>

<hr />

<br>

<p align="center">
  <a href="https://github.com/StarlaneStudios/cirql/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/StarlaneStudios/cirql"> 
  </a>
  <a href="https://discord.gg/exaQDX2">
      <img src="https://img.shields.io/discord/414532188722298881">
  </a>
  <img src="https://img.shields.io/bundlephobia/min/cirql">
  <img src="https://img.shields.io/github/contributors/StarlaneStudios/cirql">
</p>

Cirql (pronounced Circle) is a simple and lightweight ORM and query builder for [SurrealDB](https://surrealdb.com/) with built in model mapping and validation powered by [Zod](https://github.com/colinhacks/zod). Unlike most query builders, Cirql takes a very open approach, providing you with complete control over your queries.

## Features
- 🔗 Connect to SurrealDB over stateful WebSockets or stateless requests
- 📦 Support for query batching & transactions
- ⚙️ Zod-powered schema validation of query results
- 📝 Full TypeScript support with Zod schema inference
- 💎 Write flexible queries using the Query Writer API

## Notice
Cirql is still in early developmental stages. While you can use it for production applications, it may still lack specific features and edge cases. Feel free to submit feature requests or pull requests to add additional functionality to Cirql. We do ask you to please read our [Contributor Guide](CONTRIBUTING.md).

While we try to prevent making any significant API changes, we cannot guarantee this.

## Installation
The first step to use Cirql is to install the package from npm, together with a supported version of zod.
```
npm install cirql zod
```

## How to use
You can [read our documentation](https://cirql.starlane.studio/) for information on how to use Cirql.

## Contributing
We welcome any issues and PRs submitted to Cirql. Since we currently work on multiple other projects and our time is limited, we value any community help in supporting a rich future for Cirql.

Before you open an issue or PR please read our [Contributor Guide](CONTRIBUTING.md).

### Requirements
- [PNPM](https://pnpm.io/) (npm i -g pnpm)

### Roadmap
You can find the roadmap of intended features [here](ROADMAP.md).

### Changelog
The changelog of previous versions can be found [here](CHANGELOG.md).

### Live Development
To run in live development mode, run `pnpm dev` in the project directory. This will start the Vite development server.

## Maintainers
<a href="https://starlane.studio">
  <img src="https://raw.githubusercontent.com/StarlaneStudios/cirql/main/.github/branding/starlane.png" height="64">
</a>

Cirql is built and maintained by <a href="https://starlane.studio/">Starlane Studios</a> at no cost. If you would like to support our work feel free to [donate to us](https://paypal.me/ExodiusStudios) ⚡

## License

Cirql is licensed under [MIT](LICENSE)

Copyright (c) 2023, Starlane Studios
