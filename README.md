<h1 align="center">Hugo + Bootstrap 3 Starter Theme</h1>

<p align="center">Fokus is a free starter template built with Hugo and Bootstrap, providing everything you need to start your Hugo project.</p>

<p align="center">
  See it in action: 👀 <a target="_blank" href="https://fokus.junian.dev/" rel="nofollow">Demo</a> | 👨🏻‍💻 <a target="_blank" href="https://www.godo.dev/">GoDo.Dev</a> | 🚀 <a target="_blank" href="https://www.junian.net/">Junian.Net</a>
</p>

<p align="center">

  <a href="https://github.com/junian/fokus/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/junian/fokus" alt="license">
  </a>

  <a href="https://github.com/junian/fokus">
    <img src="https://img.shields.io/github/languages/code-size/junian/fokus" alt="code size">
  </a>
</p>

##

## Development

Install dependencies.

```shell
npm install
```

To build the assets.

```shell
npm run build
```

JS bundle is using `webpack`.

CSS bundle is using `gulp` and `sass`.

The rest of automation is using `gulp`.

Edit the files in `./src/`.

## Warning

- Use [`"sass": "=1.32.13"`](https://stackoverflow.com/a/67637646/2640559) because the newer version will cause [Breaking Change: Slash as Division](https://sass-lang.com/documentation/breaking-changes/slash-div/).
