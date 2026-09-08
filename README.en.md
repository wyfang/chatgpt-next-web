# NextChat

A cross-platform AI chat client with multiple model providers, web deployment, and desktop applications.

[Use online](https://chat.wangyifang.com/) · [Upstream documentation](https://github.com/ChatGPTNextWeb/NextChat/blob/main/README_CN.md) · [简体中文](./README.md)

## Features

- OpenAI, Azure OpenAI, Anthropic, Google, and other model APIs.
- Streaming responses, Markdown, LaTeX, Mermaid, prompt templates, and conversation compression.
- Responsive web interface, PWA, and desktop applications.
- Conversation history stored locally in the browser.

## Usage

Use Yarn 1.22.19, as specified in `package.json`:

```bash
yarn install
yarn dev
```

For a production web build and server:

```bash
yarn build
yarn start
```

## Notes

Configure the API key for your chosen model provider before deployment. Access passwords, proxy URLs, and provider-specific options are covered in the [upstream environment variable guide](https://github.com/ChatGPTNextWeb/NextChat/blob/main/README_CN.md#环境变量). Do not commit keys or expose them in public build logs. Chat requests are sent to the configured model provider; local history storage does not make inference local.

The existing [detailed Chinese guide](./README_CN.md), [Japanese guide](./README_JA.md), and [Korean guide](./README_KO.md) remain available. Their upstream instructions may differ from this branch; use the current code and configuration as the source of truth.

## License

This project is a fork of [ChatGPTNextWeb/NextChat](https://github.com/ChatGPTNextWeb/NextChat), distributed under the [MIT License](./LICENSE). Upstream copyright belongs to NextChat. Personal branding and assets are excluded.

See [license scope](./LICENSE_SCOPE.md) for the boundaries.
