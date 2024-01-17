# How to build

## Install Flatpak Builder

`flatpak install org.flatpak.Builder`

## Build

`flatpak-builder --repo=repo --force-clean build-dir manifests/**/<app-id>.yaml`

## Add repo

`flatpak --user remote-add --no-gpg-verify local repo`

## Install

`flatpak --user install local <app-id>`
