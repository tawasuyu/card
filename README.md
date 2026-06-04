# card

> The canonical **presentation card** — sovereign identity + typed flows, in Rust.

`card` is the suite's identity primitive: a content-addressed *Tarjeta de Presentación* that binds an `arje` identity to typed `brahman` flows. It is the leaf that the networking and desktop layers build on — peers, channels and capabilities are all expressed in terms of cards.

## Crates

- **`card-core`** — the canonical card type (identity + typed flows), content-addressed.
- **`card-wit`** — WIT-typed flow descriptions (component-model interfaces).

## How dependencies work

A true leaf: `card` has **no internal dependencies** — only crates.io. It compiles standalone and is git-depended by the rest of the suite (networking via `chasqui`/`minga`, the desktop, etc.).

## License

MIT.
