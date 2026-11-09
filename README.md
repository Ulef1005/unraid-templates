# Unraid templates

Unraid Community Applications templates by Ulf Weihbold.

| App | Template |
|---|---|
| [Brick Work](https://github.com/Ulef1005/brick-work): a workbench for your brick collection | [`templates/brick-work.xml`](templates/brick-work.xml) |

## Brick Work on Unraid

1. Install **brick-work** from Apps (Community Applications).
2. Set a **Password**, keep or change the port (3333) and the data folder (`/mnt/user/appdata/brick-work`), and apply.
3. Open the container's **Console** once and run `brickwork setup`. This step goes away once [#266](https://github.com/Ulef1005/brick-work/issues/266) lands.
4. Open the WebUI, sign in, and press **Download the catalogue** (no key needed).

The container runs as `nobody:users` (99:100), the owner of Unraid's appdata. Back up the data folder; it holds the whole collection. A `Control server error: Permission denied` line in the log at each start is harmless ([#265](https://github.com/Ulef1005/brick-work/issues/265)). Help: [GitHub Discussions](https://github.com/Ulef1005/brick-work/discussions).

LEGO is a trademark of the LEGO Group, which does not sponsor, authorise or endorse this project.
