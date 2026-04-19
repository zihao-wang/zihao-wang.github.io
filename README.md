# zihao-wang.github.io

Public static site deployed from my private knowledge vault.

## Architecture

- **Private:** `zihao-wang/pkm` — all notes, ArXiv capture, Quartz config, Docker dev env
- **Public:** `zihao-wang/zihao-wang.github.io` (this repo) — deploy workflow only

The deploy workflow clones the private `pkm` repo, filters notes with `publish: true` frontmatter, builds a [Quartz v4](https://quartz.jzhao.xyz/) static site, and pushes to `gh-pages`.

## Setup

1. Generate a [fine-grained PAT](https://github.com/settings/tokens?type=beta) with **read-only** access to `zihao-wang/pkm` (Contents: Read)
2. Add it as a repository secret `PKM_DEPLOY_TOKEN` in this repo
3. Trigger the deploy manually or wait for a `repository_dispatch` event from `pkm`
