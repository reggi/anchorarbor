# ⚓️🌲 AnchorArbor

This project is inspired by Deno's series of articles "[A Whole Website in a Single JavaScript File](https://deno.com/blog/a-whole-website-in-a-single-js-file-continued)" and the Deno "[blog](https://deno.land/x/blog@0.6.0)" module. These projects build HTML site and serve it in real-time with no build step. ArborAnchor is a single page route that offers a function with the signature `(req: Request) => Response`. The page renders a list of links, along with optional profile image, meta tags, a summary, and footer. 

I named it AnchorArbor™ get it 😉? In reference to the popular service [https://linktr.ee/](https://linktr.ee/).

It uses tailwind 🐕💨 classes for theming 😎 so you can customize the design however you want, and share themes.

Source code running on Deno Deploy 👇
https://dash.deno.com/playground/anchor-arbor

Live code running 💗
https://anchor-arbor.deno.dev/

You can run the exmaple with:

```bash
deno run --allow-net ./examples/alpha.ts
```