# Renovate discussion 35658

First, read the [Renovate minimal reproduction instructions](https://github.com/renovatebot/renovate/blob/main/docs/development/minimal-reproductions.md).

Then replace the current `h1` with the Renovate Issue/Discussion number.

## Current behavior

Renovate finds the update to the immich-server container (ghcr.io/immich-app/immich-server v1.132.1→ [Updates: v1.132.3]), but does not find the update to the immich-machine-learning container, even though they are currently released at the same time using the same versioning.

## Expected behavior

Renovate should find the immich-machine-learning update too: https://github.com/immich-app/immich/pkgs/container/immich-machine-learning/404243588?tag=v1.132.3

## Link to the Renovate issue or Discussion

[Discussion 35658](https://github.com/renovatebot/renovate/discussions/35658)
