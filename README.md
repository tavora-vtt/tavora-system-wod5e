# tavora-system-wod5e

World of Darkness 5e for Tavora VTT.

This system is built from its own repository against published versions of
[`@tavora/sdk`](https://github.com/tavora-vtt/tavora-sdk), with no access to engine internals.
That is deliberate: the first-party systems exist to prove the SDK is sufficient, and a
system living next to the engine could reach for an internal helper without anyone
noticing. CI builds it in a container with no access to the other checkouts.

Design: [concept doc 07](https://github.com/tavora-vtt/tavora-docs/blob/main/concept/07-game-systems.md).

> Links to `tavora-docs` point at a repository that is currently private, so they resolve
> only for members of the organisation. The design rationale will open up with it.

## Content and licensing

The package ships rules automation, sheets and dice. Bundled content is a separate question
answered per system and is settled before release, not after. See the licensing section of
concept doc 07.

## Status

Milestone M7. Manifest only so far.
