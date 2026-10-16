# DeckCraft Web (PowerPoint Clone)

Wersja przeglądarkowa **DeckCraft** (Rust + WebAssembly + WebGPU/WebGL2 + egui).

## Dostęp online

Aplikacja jest serwowana bezpośrednio pod adresem:
- **[https://powerpoint.lmk.one/](https://powerpoint.lmk.one/)**
- Kopia GitHub Pages: **[https://lukasz-sklad.github.io/deck-web/](https://lukasz-sklad.github.io/deck-web/)**

## Architektura i hosting

- **Silnik:** Rust `wasm32-unknown-unknown` zoptymalizowany przez `wasm-opt -Oz --all-features`.
- **Domyślna konfiguracja:** Ciemny motyw interfejsu (Dark mode), interfejs z polskimi etykietami ładowania.
- **Hosting:** GitHub Pages + Cloudflare Proxy (CNAME `powerpoint.lmk.one` wskazujący na `lukasz-sklad.github.io` z włączonym pomarańczowym proxy Cloudflare CDN i buforowaniem na brzegu sieci).
