# The Poorly Named Modpack

Yet another attempt at making a Minecraft modpack.

Currently installation is a bit of a mess, as mcdex does not appear to support directly installing from a manifest.json.
How to install it:

1. Download [mcdex](https://github.com/dizzyd/mcdex) and if possible put it on your PATH.
2. Run `mcdex pack.create the-poorly-named-modpack 1.12.2`.
3. Find the location the pack has been installed to (`[your minecraft folder]/mcdex/pack/the-poorly-named-modpack`).
4. Replace the `manifest.json` in that folder with the one from this repository.
5. Run `mcdex pack.install the-poorly-named-modpack`.
6. The pack should now be available in your launcher.

If you prefer using MultiMC, then use the same steps, replacing `mcdex` with `mcdex -mmc`.