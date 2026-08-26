# Wensity

Premium UI systems, developer tools, templates, and design engineering.

We build React and Next.js interface components that you install as source code
you own. No runtime dependency, no theme provider, no lock-in. The code lands in
your repository and it is yours to edit.

[wensity.com](https://wensity.com) ·
[ui.wensity.com](https://ui.wensity.com) ·
[Components](https://ui.wensity.com/components) ·
[Docs](https://ui.wensity.com/docs) ·
[@wensitylabs](https://x.com/wensitylabs)

<table>
  <tr>
    <td width="50%" align="center">
      <img src="https://raw.githubusercontent.com/wensity/.github/main/profile/media/siri-orb.gif" alt="An iridescent ribbon swirling inside a glass sphere" width="100%">
      <br><sub>Siri Orb</sub>
    </td>
    <td width="50%" align="center">
      <img src="https://raw.githubusercontent.com/wensity/.github/main/profile/media/chatgpt-orb.gif" alt="A soft blue orb with drifting internal cloud motion" width="100%">
      <br><sub>ChatGPT Orb</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" align="center">
      <img src="https://raw.githubusercontent.com/wensity/.github/main/profile/media/stack-reveal.gif" alt="A deck of landscape cards promoting one plate at a time" width="100%">
      <br><sub>Stack Reveal</sub>
    </td>
    <td width="50%" align="center">
      <img src="https://raw.githubusercontent.com/wensity/.github/main/profile/media/refraction-glass-container.gif" alt="A glass card bending the colour blobs drifting behind it" width="100%">
      <br><sub>Refraction Glass Container</sub>
    </td>
  </tr>
</table>

## Start here

```bash
# With the shadcn CLI
npx shadcn@latest add @wensity/liquid-multimodal-input

# Or with the Wensity CLI
npx wensity@latest init
npx wensity@latest add button
```

## Open source

| Repository | What it is |
| --- | --- |
| [registry](https://github.com/wensity/registry) | The public shadcn registry. 91 free components, text animations, UI primitives, fonts, and design tokens, all MIT |
| [cli](https://github.com/wensity/cli) | The `wensity` command line tool for installing components and applying Tailwind presets |
| [nextjs-starter](https://github.com/wensity/nextjs-starter) | Next.js 16 and Tailwind v4 starter whose whole design system swaps from one preset code |

The Wensity product itself is closed source. These repositories hold the parts
meant to run inside your project.

## What we make

**Agentic AI interfaces.** Prompt inputs, voice orbs, model switchers, and
generative loading states for AI products.

**UI primitives.** The standard accessible set built on Base UI, wired to a
single token contract so one preset restyles all of it.

**Text animations.** Shimmer, glitch, scribble, and morph effects for headlines, all free and installable on their own.

**Cinematic interactions.** Scroll-scrubbed sequences, morphing backgrounds, and
marquees that hold their frame rate.

**Templates and design engineering.** Full builds for teams that want the whole
surface done properly.

## Presets

Wensity components read from one `--primitive-*` CSS block, so a single
shareable code restyles the entire set without touching component source. Build
one in the [preset studio](https://ui.wensity.com/create-preset) and apply it:

```bash
npx wensity@latest apply --preset <wsty1-code>
```

## Contact

[hey@wensity.com](mailto:hey@wensity.com) · India
