# coredns.io

Purpose:

1. What is CoreDNS?
1. How to use it?
1. How to get involved and get help.

The website is created with HUGO, you'll need to download and install that if you want to locally
work on the website. For creating new content it is not needed.

We have three types of pages.

* Home - `themes/coredns/layouts/index.html`
* Blog/News/Documentation - `content/blog/*` (depends on params, see `archetypes`)
* Plugins - `content/plugins/*` and `content/explugins/*`

Any blog post you'll tag with 'documentation' will also become visible on the "Documentation"
link on the website.

Releases should be tagged with 'release = "number" and `data/coredns.toml` should be updated
with the number.

`data/subtext.toml` controls the buttons for "Docs", "Plugins" and "External Plugins".

Create:

* new release: `hugo new -k release blog/coredns-<number>.md`
* new blog: `hugo new -k blog blog/coredns-<number>.md`
* new blog that will also be documentation: `hugo new -k doc blog/coredns-<number>.md`

## Colors

* Dark: #280071   (40, 0, 113)
* Middle: #5F259F (95, 37, 159)
* Light: #8246AF  (130, 70, 175)

## Popup

See the top-level (i.e. not in the themes directory) layout/partials/popup.html for adjusting the
text.
