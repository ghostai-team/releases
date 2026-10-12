# releases

Public. Holds release assets only: installers and `SHA256SUMS.txt` per release, nothing else, no source (DEC-062). It exists because a private repository's assets cannot be fetched by a visitor's browser.

## How releases get here

A `carry-v*` tag on `ghostai-team/buzz` runs its release job, which mints a one-hour token as the `ghostai-agents` App and creates the release here with the assets. Nobody commits to this repository by hand; the README is the only file.

## Do not

- Add source, documentation or workflows here. Private repositories hold those.
- Delete or edit a published release: the website's download links point at these URLs.
