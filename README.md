# Theia's Website

[![setup automated](https://img.shields.io/badge/setup-automated-blue?logo=gitpod)](https://gitpod.io/from-referrer/)

The source for the [website](https://theia-ide.org) and [online documentation](https://theia-ide.org/docs/) for the [Theia IDE Framework](https://github.com/eclipse-theia/theia).

## How to contribute

The easiest is to use Gitpod, which has everything readily setup to start working:

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/theia-ide/theia-website)

### Work locally

Building locally requires node 14.x. Alternatively, you can use `npm i --legacy-peer-deps` to ignore conflicting peer dependencies.

```bash
npm install && npm run start
```

To build for production and serve, run:

```bash
npm run build
npm run serve
```

## CI

The website is automatically built at and deployed to Netlify.
A preview of each PR is deployed to Netlify.

In addition, every commit on `master` is built and published to branch `gh-pages`, which will soon replace the deployment of Netlify.
A preview of every pull request is published at [eclipse-theia/theia-website-previews](https://github.com/eclipse-theia/theia-website-previews).
For more information, see [`publish.yml`](.github/workflows/publish.yml) and [`preview.yml`](.github/workflows/preview.yml).

## License

- [Eclipse Public License 2.0](LICENSE)
- [一 (Secondary) GNU General Public License, version 2 with the GNU Classpath Exception](LICENSE)

## Trademark

"Theia" is a trademark of the Eclipse Foundation
https://www.eclipse.dev/theia
