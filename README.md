# Personal website

A tiny multilingual Hugo site. Content lives in Markdown under `content/en`, `content/es`, and `content/it`.

## Write a post

Create the same filename in each language folder, for example:

```text
content/en/blog/my-post.md
content/es/blog/my-post.md
content/it/blog/my-post.md
```

Give each version the same `translationKey` in its front matter. Hugo will connect them for the language switcher.

## Preview and build

Install [Hugo Extended](https://gohugo.io/installation/), then run:

```bash
hugo server
hugo
```

The production site is written to `public/`. Do not commit that directory; your deployment host should run `hugo` for each push.
