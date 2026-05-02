# mxscript.com

The official website for [MX Script](https://github.com/jlkdevelop/mxscript) — a modern, open-source scripting language for building web apps and APIs.

> Founded by [Jassim Alkharafi](https://github.com/jlkdevelop). MIT-licensed and built in the open.

## About this repo

This repository hosts the source for **mxscript.com**, the official site for the MX Script language.

**Goal:** the entire site is built using MX Script itself. Every route, every page, every byte of HTML — generated from `.mx` code. The site is the language's first real-world dogfood, and grows in parallel with the language.

The whole site lives in a single file: [`app.mx`](./app.mx). HTML is built up from small functions that return strings; CSS is inlined; routes are first-class. As the language gains features the site needs (templating, asset pipeline, etc.), the site grows alongside it.

## Stack

- **Language:** [MX Script](https://github.com/jlkdevelop/mxscript)
- **Runtime:** the `mx` CLI (`mx run app.mx`)
- **Output:** HTML rendered directly from `.mx` via the `html()` response helper
- **No JS frameworks. No build step. No `node_modules`. One file.**

## Routes

| Path       | Purpose                                          |
| ---------- | ------------------------------------------------ |
| `/`        | The landing page (full HTML rendered from `.mx`) |
| `/status`  | JSON heartbeat — proof that MX Script serves it  |

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
