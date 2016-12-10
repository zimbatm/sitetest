# sitetest

Testing https://github.com/blog/2289-publishing-with-github-pages-now-as-easy-as-1-2-3

## Code rendering

```nix
{ stdenv }:
stdenv.mkDerivation {
  name = "foo";
}
```

## Page links

* [link to sub-page 1](./docs/sub-page.md)
* [link to sub-page 2](./docs/sub-page)
* [link to sub-page 3](./docs/sub-page.html)
