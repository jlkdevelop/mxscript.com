# mxscript.com

The official website for [MX Script](https://github.com/jlkdevelop/mxscript) — a modern, open-source scripting language for building web apps and APIs.

> Founded by [Jassim Alkharafi](https://github.com/jlkdevelop). MIT-licensed and built in the open.

## About this repo

This repository hosts the source for **mxscript.com**, the official site for the MX Script language.

**Goal:** the entire site is built using MX Script itself. Every route, every page, every endpoint — written in `.mx`. The site is the language's first real-world dogfood, and grows in parallel with the language.

That means this repo is intentionally minimal today. As the language gains the features the site needs (templating, asset pipeline, etc.), the site grows alongside it.

## Stack

- **Language:** [MX Script](https://github.com/jlkdevelop/mxscript)
- **Runtime:** the `mx` CLI (`mx run app.mx`)
- **Static assets:** served via the `static` directive
- **No JS frameworks. No build step. One file.**

## Running locally

Install MX Script (see the [language repo](https://github.com/jlkdevelop/mxscript) for instructions), then:

```sh
mx run app.mx
```

The site will be available at `http://localhost:8080`.

## Contributing

Contributions are welcome. Because the site is a dogfood for MX Script, the highest-leverage contributions are:

1. Surfacing language gaps the site exposes (open an issue on the [language repo](https://github.com/jlkdevelop/mxscript/issues))
2. Improving copy, design, or content
3. Adding examples and tutorials

## License

[MIT](./LICENSE) © Jassim Alkharafi
