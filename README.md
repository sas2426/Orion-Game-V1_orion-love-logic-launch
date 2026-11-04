# Orion: Love, Logic & Launch 💚

An adult relationship and human-connection learning game presented as a gentle space adventure. Players explore five short scenarios, choose a response, and receive an explanation and a golden rule.

## Play

Open [`index.html`](index.html) in a modern browser. The game has no build step, package installation, account, or server requirement. It also works when hosted as a static site, including GitHub Pages.

To publish with GitHub Pages, upload the contents of this folder to a repository, then select **Settings → Pages** and deploy from the `main` branch and `/ (root)`. The site entry point is `index.html`.

## What is included

- Five scenario-based levels: **Crush or Connection?**, **Situationship Station**, **Boundary Shield**, **Commitment Compass**, and **Self-Worth Galaxy**.
- A calm, optional **Baggage Bypass** flight interlude with a steerable ship and drifting asteroid metaphors. There are no collisions, penalties, or flight score.
- Adult life-stage selector, level progression, badges, and stardust for choices aligned with each scenario's learning goal.
- Keyboard, pointer, and touch controls for flight, pause/restart controls, responsive layout, visible focus styles, and reduced-motion preference support.
- Darwin’s playtest guide at [`docs/DARWIN_TESTING.md`](docs/DARWIN_TESTING.md).

## Adult pathways

Pathways are provided for 18–24, 25–29, 30–34, 35–39, 40–44, 45–49, 50–54, 55–58, 59–60, 61–69, 70+, and all adult stages. Age is not a maturity score or restriction. Players can choose topics independent of age. In this MVP the selector records a lens for the player; it does not yet rewrite scenario text.

This MVP is for adults. A children’s pathway requires its own age-appropriate content and safeguarding review; adult romance scenarios should not simply be relabeled for children.

## Design principles

Orion is educational, non-diagnostic, and consent- and safety-centered. It makes room for different relationship structures and life choices, including marriage and committed relationships without marriage. The feedback is intended to invite reflection, not diagnose a relationship or prescribe a single answer. Where a scenario mentions fear, coercion, or harm, personal safety and trusted support take priority.

The supplied reference images informed the broad space-adventure direction. This prototype uses original CSS and canvas visuals and does not reproduce those designs.

## Technology and dependencies

The game is a single self-contained HTML page using browser-native HTML, CSS, and JavaScript. It has no runtime dependencies. The page requests optional fonts from Google Fonts; system fallbacks are provided if the font service is unavailable.

## Next steps

1. Run the adult scenario testing session in [`docs/DARWIN_TESTING.md`](docs/DARWIN_TESTING.md).
2. Review wording with an adult relationship-education or safeguarding reviewer before broader use.
3. Use playtest notes to improve life-stage relevance, accessibility, and scenario variety.
4. Design any children’s experience as a separate product and review effort.

## License

No license is included. Choose and add a license before distributing or accepting contributions.
