+++
title = "Book"
template = "docs.html"
page_template = "docs.html"
insert_anchor_links = "right"
+++

If you came here because you wanted to learn how to make 2D / 3D games, visualizations, user interfaces, or other graphical applications with Bevy... you came to the right place! If not, stick around anyway. I promise it will be fun.

<h2>
    <img src="/assets/whats_a_bevy.svg" class="docs-whats-a-bevy" alt="What's a BEVY?"/>
</h2>

A bevy is a group of birds!

But Bevy is also a refreshingly simple data-driven game engine built in Rust. It is [free and open-source](https://github.com/bevyengine/bevy) forever under your choice of the MIT or Apache 2.0 licenses.

Bevy has the following design goals:

* **Capable**: Offer a complete 2D and 3D feature set
* **Simple**: Easy for newbies to pick up, but infinitely flexible for power users
* **Data Focused**: Data-oriented architecture using the Entity Component System paradigm
* **Modular**: Use only what you need. Replace what you don't like
* **Fast**: App logic should run quickly, and when possible, in parallel
* **Productive**: Changes should compile quickly... waiting isn't fun

Bevy is [built in the open by volunteers](https://bevyengine.org/learn/contribute/introduction) using the [Rust programming language](https://www.rust-lang.org/). The code is free and open-source because we believe developers should fully own their tools. Games are a huge part of our culture and humanity is investing _millions_ of hours into the development of games. Why are we continuing to build up the ecosystems of closed-source monopolies that take cuts of our sales and deny us visibility into the tech we use daily? We believe that the developer community can do so much better.

{% callout(type="warning") %}

## Stability Warning

Bevy is still in the early stages of development. Important features are missing. Documentation is sparse. A new version of Bevy containing breaking changes to the API is released [approximately once every 3 months](https://bevyengine.org/news/bevy-0-6/#the-train-release-schedule). We provide [migration guides](https://bevyengine.org/learn/book/migration-guides/), but we can't guarantee migrations will always be easy. Use only if you are willing to work in this environment.

If you are currently trying to pick an engine for your Next Big Project™, we recommend that you check out [Godot Engine](https://godotengine.org). It is currently much more feature-complete and stable. And it is also free, open-source, and [scriptable with Rust](https://github.com/godot-rust/gdext)!
{% end %}

## How do I learn Bevy?

Like any game engine, Bevy is a large project, and there's a lot to learn!
Everyone learns differently, so we offer a variety of complementary learning paths:

* [Quickstart](learn/quickstart): Dive in and get your hands dirty, learning how to create a simple game in a hands-on tutorial for absolute beginners.
* [The Book](learn/book): Read about the core concepts that make Bevy work, and browse our library of the advanced topics needed to ship a production game.
* [docs.rs](https://docs.rs/bevy/latest/bevy/): Versioned API documentation that explains exactly what every struct, method and function mean. Module and crate docs are also great, and provide an overview of the structure and usage of specific areas of the code.
* [API examples](https://bevyengine.org/examples/api): Try out our APIs hands on, as part of larger runnable examples.
* [Usage examples](https://bevyengine.org/examples/usage): Figure out how to solve specific game dev problems (like running a game in split screen) by shamelessly stealing from our runnable snippets.
* [Game examples](https://bevyengine.org/examples/game): Get a sense of how to structure larger projects and tackle new genres with playable game stubs.
