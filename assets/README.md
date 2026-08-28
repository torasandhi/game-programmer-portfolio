# Portfolio assets

Add only real project media here. The Carnifall placeholders in `index.html` expect:

- `projects/carnifall/multiplayer-01.webp` — representative current multiplayer gameplay
- `projects/carnifall/multiplayer-02.webp` — lobby or online-session flow
- `projects/carnifall/multiplayer-03.webp` — a replicated gameplay system in action

Recommended export: WebP, 1600×900 pixels (16:9), ideally under 400 KB per image.

After adding each image, replace its matching `.media-placeholder` block in `index.html` with an `<img>` element. Suggested markup:

```html
<figure class="project-image">
  <img src="assets/projects/carnifall/multiplayer-01.webp" alt="Describe what is visible in the Carnifall multiplayer screenshot" width="1600" height="900" loading="lazy">
  <figcaption>Short, factual screenshot caption.</figcaption>
</figure>
```

Do not add proprietary code captures or assets that you do not have permission to publish.
