# modelo-ts

- **template of:** vite + vue + typescript + tailwindcss
- **rollup plugins:** terser + visualizer

## Started
```bash
npm install
# or `yarn`
```

---
## Develop
```bash
npm run dev
# or `yarn dev`
```

---
## Build
```bash
npm run build
# or `yarn build`
```

---

# Git config

```bash
[credential]
helper = osxkeychain

[user]
name = Junior Ali
email = alijunior@gmail.com

[core]
editor = ws
pager = cat

[alias]
c = !git add --all && git commit -m
s = !git status -s
l = !git log --pretty=tformat:'%C(yellow)%h%C(red)%d %C(white)%s %C(cyan)%cn %C(green)-> %cr'
t = !sh -c 'git tag -a $1 -m $1'
amend = !git add --all && git commit --amend --no-edit
cfg = !git config --global --edit

[push]
followTags = true

[pager]
log = true
```
---
powered by
<p align="center">
<img src="src/assets/brand-alitec.png">
</p>