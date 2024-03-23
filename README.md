This is hugo repository for [saz.jp](https://saz.jp/). Generated content (published) can be found in `/docs` folder.

## Quick notes

- Testing locally

      hugo server

- Testing locally with posts with future date

      hugo server --buildFuture

- Then go to

      http://localhost:1313/

- Generate `docs/` and commit

      rm -rf docs/ && hugo -d docs/ && echo -n "saz.jp" > docs/CNAME && git add docs/ && git commit -m "generate docs"

- Add a new page

      hugo new my-new-page.md


## Installing hugo

- Install hugo

      brew install hugo

- Verify hugo version

      hugo version
