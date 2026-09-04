# Sphere

[![](./social_preview.png)](https://github.com/go-sphere/sphere)

**Protobuf-first Go service framework for definition-driven development**

Start modular monolithic, scale to microservices. Define once in Protobuf, generate Go handlers, HTTP routing, client SDKs, OpenAPI docs, and TypeScript bindings from a single source of truth. Complete code generation toolchain with structured error handling and developer-friendly CLI tools.

## CI status

| Repository | Status |
| --- | --- |
| [binding](https://github.com/go-sphere/binding) | [![Test](https://github.com/go-sphere/binding/actions/workflows/build.yml/badge.svg?branch=master)](https://github.com/go-sphere/binding/actions/workflows/build.yml) |
| [confstore](https://github.com/go-sphere/confstore) | [![Test](https://github.com/go-sphere/confstore/actions/workflows/build.yml/badge.svg?branch=master)](https://github.com/go-sphere/confstore/actions/workflows/build.yml) |
| [entc-extensions](https://github.com/go-sphere/entc-extensions) | [![Test](https://github.com/go-sphere/entc-extensions/actions/workflows/build.yml/badge.svg?branch=master)](https://github.com/go-sphere/entc-extensions/actions/workflows/build.yml) |
| [errors](https://github.com/go-sphere/errors) | [![Test](https://github.com/go-sphere/errors/actions/workflows/build.yml/badge.svg?branch=master)](https://github.com/go-sphere/errors/actions/workflows/build.yml) |
| [go-sphere.github.io](https://github.com/go-sphere/go-sphere.github.io) | [![Build and deploy](https://github.com/go-sphere/go-sphere.github.io/actions/workflows/hugo.yaml/badge.svg?branch=master)](https://github.com/go-sphere/go-sphere.github.io/actions/workflows/hugo.yaml) |
| [httpx](https://github.com/go-sphere/httpx) | [![Test](https://github.com/go-sphere/httpx/actions/workflows/build.yml/badge.svg?branch=master)](https://github.com/go-sphere/httpx/actions/workflows/build.yml) |
| [jsoncompressor](https://github.com/go-sphere/jsoncompressor) | [![Test](https://github.com/go-sphere/jsoncompressor/actions/workflows/build.yml/badge.svg?branch=master)](https://github.com/go-sphere/jsoncompressor/actions/workflows/build.yml) |
| [options](https://github.com/go-sphere/options) | [![Test](https://github.com/go-sphere/options/actions/workflows/build.yml/badge.svg?branch=master)](https://github.com/go-sphere/options/actions/workflows/build.yml) |
| [protoc-gen-route](https://github.com/go-sphere/protoc-gen-route) | [![Test](https://github.com/go-sphere/protoc-gen-route/actions/workflows/build.yml/badge.svg?branch=master)](https://github.com/go-sphere/protoc-gen-route/actions/workflows/build.yml) |
| [protoc-gen-sphere](https://github.com/go-sphere/protoc-gen-sphere) | [![Test](https://github.com/go-sphere/protoc-gen-sphere/actions/workflows/build.yml/badge.svg?branch=master)](https://github.com/go-sphere/protoc-gen-sphere/actions/workflows/build.yml) |
| [protoc-gen-sphere-binding](https://github.com/go-sphere/protoc-gen-sphere-binding) | [![Test](https://github.com/go-sphere/protoc-gen-sphere-binding/actions/workflows/build.yml/badge.svg?branch=master)](https://github.com/go-sphere/protoc-gen-sphere-binding/actions/workflows/build.yml) |
| [protoc-gen-sphere-errors](https://github.com/go-sphere/protoc-gen-sphere-errors) | [![Test](https://github.com/go-sphere/protoc-gen-sphere-errors/actions/workflows/build.yml/badge.svg?branch=master)](https://github.com/go-sphere/protoc-gen-sphere-errors/actions/workflows/build.yml) |
| [sphere](https://github.com/go-sphere/sphere) | [![Test](https://github.com/go-sphere/sphere/actions/workflows/build.yml/badge.svg?branch=master)](https://github.com/go-sphere/sphere/actions/workflows/build.yml) |
| [sphere-bun-layout](https://github.com/go-sphere/sphere-bun-layout) | [![Test](https://github.com/go-sphere/sphere-bun-layout/actions/workflows/build.yml/badge.svg?branch=master)](https://github.com/go-sphere/sphere-bun-layout/actions/workflows/build.yml) |
| [sphere-cli](https://github.com/go-sphere/sphere-cli) | [![Test](https://github.com/go-sphere/sphere-cli/actions/workflows/build.yml/badge.svg?branch=master)](https://github.com/go-sphere/sphere-cli/actions/workflows/build.yml) |
| [sphere-layout](https://github.com/go-sphere/sphere-layout) | [![Test](https://github.com/go-sphere/sphere-layout/actions/workflows/build.yml/badge.svg?branch=master)](https://github.com/go-sphere/sphere-layout/actions/workflows/build.yml) [![Codegen compatibility](https://github.com/go-sphere/sphere-layout/actions/workflows/codegen.yml/badge.svg?branch=master)](https://github.com/go-sphere/sphere-layout/actions/workflows/codegen.yml) |
| [sphere-simple-layout](https://github.com/go-sphere/sphere-simple-layout) | [![Test](https://github.com/go-sphere/sphere-simple-layout/actions/workflows/build.yml/badge.svg?branch=master)](https://github.com/go-sphere/sphere-simple-layout/actions/workflows/build.yml) |
| [telegram-bot](https://github.com/go-sphere/telegram-bot) | [![Test](https://github.com/go-sphere/telegram-bot/actions/workflows/build.yml/badge.svg?branch=master)](https://github.com/go-sphere/telegram-bot/actions/workflows/build.yml) |
| [wecom-aibot-go-sdk](https://github.com/go-sphere/wecom-aibot-go-sdk) | [![Test](https://github.com/go-sphere/wecom-aibot-go-sdk/actions/workflows/build.yml/badge.svg?branch=master)](https://github.com/go-sphere/wecom-aibot-go-sdk/actions/workflows/build.yml) |
| [wecom-bot-api](https://github.com/go-sphere/wecom-bot-api) | [![Test](https://github.com/go-sphere/wecom-bot-api/actions/workflows/build.yml/badge.svg?branch=master)](https://github.com/go-sphere/wecom-bot-api/actions/workflows/build.yml) |
| [weixin-mp-api](https://github.com/go-sphere/weixin-mp-api) | [![Test](https://github.com/go-sphere/weixin-mp-api/actions/workflows/build.yml/badge.svg?branch=master)](https://github.com/go-sphere/weixin-mp-api/actions/workflows/build.yml) |

## core
- [sphere](https://github.com/go-sphere/sphere) - A multi-server application template

## layout
- [`sphere-layout`](https://github.com/go-sphere/sphere-layout) : Default sphere project layout template with `ent` as ORM.
- [`sphere-simple-layout`](https://github.com/go-sphere/sphere-simple-layout) : A simplified version of the Sphere project layout template.
- [`sphere-bun-layout`](https://github.com/go-sphere/sphere-bun-layout) : A layout template with `bun` as ORM.

## protobuf
- [errors](https://buf.build/go-sphere/errors)
- [options](https://buf.build/go-sphere/options)
- [binding](https://buf.build/go-sphere/binding)

## toolchains
- [sphere-cli](https://github.com/go-sphere/sphere-cli) - A command-line tool designed to streamline the development of Sphere projects.
- [protoc-gen-route](https://github.com/go-sphere/protoc-gen-route) - A protoc plugin that generates routing code from `.proto` files.
- [protoc-gen-sphere](https://github.com/go-sphere/protoc-gen-sphere) - A protoc plugin that generates HTTP server code from `.proto` files.
- [protoc-gen-sphere-binding](https://github.com/go-sphere/protoc-gen-sphere-binding) - A protoc plugin that generates Go struct tags for Sphere binding from `.proto` files.
- [protoc-gen-sphere-errors](https://github.com/go-sphere/protoc-gen-sphere-errors) - A protoc plugin that generates error handling code from `.proto` files.
