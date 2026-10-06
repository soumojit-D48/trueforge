---
'@truefoundry/trueforge': patch
---

Fix derived session titles ending in a lone surrogate when the length cap splits an emoji, which stored
malformed Unicode.
