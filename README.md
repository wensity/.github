# wensity/.github

This repository exists for one reason: GitHub renders
[`profile/README.md`](profile/README.md) on the
[Wensity organization page](https://github.com/wensity).

That file has to live at `profile/README.md`. A `README.md` at the repository
root, like this one, is **not** used for the organization profile; it only
describes this repository. So there are two files here on purpose.

## Editing the org profile

Edit [`profile/README.md`](profile/README.md). Changes appear on
<https://github.com/wensity> as soon as they land on `main`.

Images in that file use absolute `raw.githubusercontent.com` URLs rather than
relative paths. Relative paths resolve against `profile/` when the file is
rendered on the organization page, which breaks them.

## The actual projects

| Repository | What it is |
| --- | --- |
| [registry](https://github.com/wensity/registry) | The public shadcn registry |
| [cli](https://github.com/wensity/cli) | The `wensity` command line tool |
| [nextjs-starter](https://github.com/wensity/nextjs-starter) | Next.js and Tailwind v4 starter |
