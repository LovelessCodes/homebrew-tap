# Story Forge Homebrew tap

```sh
brew install --cask lovelesscodes/tap/storyforge
```

The cask is generated from the release artifacts by
[StoryForge](https://github.com/LovelessCodes/StoryForge)'s
`scripts/packaging/update-manifests.ts` and pushed by
`.github/workflows/distribute.yml` after every published release — do not edit
`Casks/storyforge.rb` by hand, changes here are overwritten.

The app updates itself through its built-in updater, so Homebrew does not track
upgrades for it.
