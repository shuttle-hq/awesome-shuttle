![](https://raw.githubusercontent.com/shuttle-hq/shuttle/master/assets/logo-rectangle-transparent.png)
# Awesome Shuttle

An awesome list of Shuttle-hosted projects and resources that users can add to.

If you want to contribute, please read [this](CONTRIBUTING.md).

## Table of contents

<!-- toc -->

- [Official Pages](#official-pages)
- [Official Tutorials](#official-tutorials)
- [Official Examples and Community Examples](#official-examples-and-community-examples)
- [Workshops](#workshops)
- [Built on Shuttle](#built-on-shuttle)
- [Libraries](#libraries)
- [Resources](#resources)
- [License](#license)

<!-- tocstop -->

## Official Pages

- [Status Page](status.shuttle.rs) - Status page for Shuttle services. If anything goes down, you can check here.
- [Docs](docs.shuttle.rs): The Shuttle docs.

## Official Tutorials

Official Shuttle tutorials to help you write more competent services.

- [Working with Databases in Rust](https://docs.shuttle.rs/tutorials/databases-with-rust) - A guide on how to work with databases in Rust.
- [Writing a REST HTTP service with Axum](https://docs.shuttle.rs/tutorials/rest-http-service-with-axum) - A guide on how to write a competent HTTP service in Axum that covers static files, cookies, middleware and more.
- [Writing a Custom Service](https://docs.shuttle.rs/tutorials/custom-service) - A guide on how to write a web service that implements multiple services (so for example, a Discord bot and router that you can potentially extend and add some background tasks to)

## Official Examples and Community Examples

Find full Shuttle app examples in the [shuttle-examples](https://github.com/shuttle-hq/shuttle-examples) repository and use them as templates for your next project.
Also check out the [Community Examples](https://github.com/shuttle-hq/shuttle-examples#community-examples) for even more examples.

## Workshops

Shuttle workshops that have been held in the past. 

- [Re-writing an Express.js Chat App in Rust](https://www.youtube.com/watch?v=-N8AKKCE9L8&t=708s) - A workshop that details writing a web-socket based real time chat app in Rust with Axum.
- [Building Semantic Search in Rust with Qdrant & Shuttle](https://www.youtube.com/watch?v=YLWSeiDh2o0) - A workshop that details leveraging the power of LLMs to write a Semantic Search AI in Rust, using Qdrant (an open-source vector search database) and OpenAI.

## Built on Shuttle

A list of cool web-based applications that have been built on Shuttle.

- [Kitsune](https://github.com/aumetra/kitsune/tree/aumetra/shuttle) - A self-hostable ActivityPub-based social media server, like Mastodon. Uses Vue as a frontend.
- [Rustypaste](https://github.com/orhun/rustypaste) - A simple web service that lets you host and share long plain text. 
- [Github API Dashboard](https://github.com/marc2332/ghboard) - A dashboard that tracks your Github contributions. Uses Dioxus as a frontend, powered by the Github GraphQL API. [(Demo)](https://ghboard.shuttleapp.rs/user/demonthos)
- [no-more-json](https://github.com/beyarkay/no-more-json) - Fed up with massive JSON objects? Just give `no-more-json` an API endpoint and a [`jq`](https://jqlang.github.io/jq/) query. `no-more-json` will apply that query to the JSON returned by the endpoint, and give you the (much smaller) result.
- [Licensebat](https://github.com/licensebat/licensebat) - A tool to help you verify that your dependencies comply with your license policies
- [plabayo.tech](https://plabayo.tech/): [open source](https://github.com/plabayo/website) official company website of Plabayo, a FOSS dev and consultancy studio
- [bckt.xyz](https://bckt.xyz): [open source](https://github.com/plabayo/bucket) link shortener and secret sharing service (for friends of Plabayo)

## Libraries

Plugins for Shuttle that users have made.

- [shuttle-diesel-async](https://github.com/aumetra/shuttle-diesel-async) - A plugin for Shuttle that lets you use Diesel as the provided connection instead of SQLx.
- [shuttle-seaorm](https://github.com/joshua-mo-143/shuttle-seaorm) - A plugin for Shuttle that lets you use SeaORM as the provided connection instead of SQLx.

## Resources

Unofficial Shuttle tutorials.

- [Building a SaaS with Rust](https://joshmo.bearblog.dev/lets-build-a-saas-with-rust/) - A guide for writing a SaaS backend in Rust.
- [Building a Movie Collection Manager](https://bcnrust.github.io/devbcn-workshop/)  - Full Stack Workshop with Rust, Actix, SQLx, Dioxus, and Shuttle.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
