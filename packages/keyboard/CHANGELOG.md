# @solid-primitives/keyboard

## 1.0.5

### Patch Changes

- 85edc294: Check if the key in keydown and keyup events is a stirng. (fixes #246)

## 1.0.4

### Patch Changes

- Updated dependencies [9ed32b38]
  - @solid-primitives/utils@4.0.0
  - @solid-primitives/event-listener@2.2.4
  - @solid-primitives/rootless@1.2.1

## 1.0.3

### Patch Changes

- b662fe9f: Improve package export contidions for SSR (node, workers, deno)
- Updated dependencies [e36ed229]
- Updated dependencies [a372d0e7]
- Updated dependencies [b662fe9f]
- Updated dependencies [abb8063c]
- Updated dependencies [abb8063c]
  - @solid-primitives/rootless@1.2.0
  - @solid-primitives/utils@3.1.0
  - @solid-primitives/event-listener@2.2.3

## 1.0.2

### Patch Changes

- 7ac41ed: Update to solid-js version 1.5
- Updated dependencies [7ac41ed]
  - @solid-primitives/event-listener@2.2.2
  - @solid-primitives/rootless@1.1.3
  - @solid-primitives/utils@3.0.2

## 1.0.1

### Patch Changes

- Updated dependencies [73b6a34]
  - @solid-primitives/utils@3.0.0
  - @solid-primitives/event-listener@2.2.1
  - @solid-primitives/rootless@1.1.2

## Changelog up to version 1.0.0

0.0.100

Initial release as a Stage-0 primitive.

1.0.0

[PR#159](https://github.com/solidjs-community/solid-primitives/pull/159)

General package refactor. The single initial `makeKeyHoldListener` primitive has been replaced by:

- `useKeyDownList`,
- `useCurrentlyHeldKey`,
- `useKeyDownSequence`,
- `createKeyHold`,
- `createShortcut`
