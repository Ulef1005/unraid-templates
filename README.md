# Unraid templates

Unraid Community Applications templates by Ulf Weihbold.

| App | Template |
|---|---|
| [Brick Work](https://github.com/Ulef1005/brick-work): a workbench for your brick collection | [`templates/brick-work.xml`](templates/brick-work.xml) |

## Brick Work on Unraid

1. Install **brick-work** from Apps (Community Applications).
2. Set a **Password**, keep or change the port (3333) and the data folder (`/mnt/user/appdata/brick-work`), and apply.
3. Open the WebUI, sign in, and press **Download the catalogue** (no key needed). The container creates your empty collection on its first start; no Console step.

The container runs as `nobody:users` (99:100), the owner of Unraid's appdata. Needs Brick Work 1.0.1 or newer (the `latest` image). Back up the data folder; it holds the whole collection. Help: [GitHub Discussions](https://github.com/Ulef1005/brick-work/discussions).

LEGO is a trademark of the LEGO Group, which does not sponsor, authorise or endorse this project.
