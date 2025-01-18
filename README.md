# DalamudAssets
Static assets for Dalamud

All Noto Sans, FontAwesome and Inconsolata fonts are licensed under the [SIL Open Font License](http://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL).
Material Design Icons are licensed under the [Apache License Version 2.0](https://www.apache.org/licenses/LICENSE-2.0.txt).

## Steps on how to block a plugin from being loaded
1. Fork this repository
2. Pull the `master` branch
3. Make a new local branch
4. Update `UIRes/bannedplugin.json` with your changes. 
  <br>**NOTE**: If you need to block a plugin from a custom repository, please SHA256 the InternalAssembly name. The SHA hash must be in ALL CAPS.
5. Commit, Push, and create a PR.
6. Once CI checks pass, someone will merge it.
7. Instruct affected users to relaunch.
