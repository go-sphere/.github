# Sphere

[![](./social_preview.png)](https://github.com/go-sphere/sphere)

**Protobuf-first Go service framework for definition-driven development**

Start modular monolithic, scale to microservices. Define once in Protobuf, generate Go handlers, HTTP routing, client SDKs, OpenAPI docs, and TypeScript bindings from a single source of truth. Complete code generation toolchain with structured error handling and developer-friendly CLI tools.

## core
- [sphere](https://github.com/go-sphere/sphere) - A multi-server application template

## layout
- [sphere-layout](https://github.com/go-sphere/sphere-layout) - Sphere standard layout
- [sphere-simple-layout](https://github.com/go-sphere/sphere-simple-layout) - Sphere simple layout

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
