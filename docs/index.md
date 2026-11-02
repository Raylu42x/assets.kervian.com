# assets.kervian.com docs

Static files shared by the Kervian sites. See [../README.md](../README.md).

## Adding a file

1. Put images in `img/` and videos in `videos/`.
2. Push to `main`. The `CNAME` file sets the custom domain.
3. Link to `https://assets.kervian.com/img/<file>` from other sites.

Files here are public. Renaming or deleting one breaks any site that links to it, so search the other
Kervian repos first.

There's no build step. Each folder's `index.html` is a landing page for that folder.
