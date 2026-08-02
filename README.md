# ajar-media

Screenshots and video embedded in [`ajar-next`](https://github.com/studiofrontier/ajar-next)
pull requests.

Public on purpose. `ajar-next` is private, and an image embedded from a private repo only
loads for a viewer whose browser already holds a github.com session — so it renders on
desktop and shows as a broken image in the GitHub mobile app, which is where review
actually happens. Served from here, GitHub's image proxy can fetch it and it renders
everywhere.

One folder per ticket. Published by `scripts/pr-media.sh` in the main repo.
