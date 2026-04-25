# prodrive-homebridge

Canonical instructions and skills live under [`agents/prodrive-homebridge/`](agents/prodrive-homebridge/) — pulled in via the [prodrive-agents](https://github.com/k10-motorsports/prodrive-agents) submodule.

Common entry points:
- Repo overview: [`agents/prodrive-homebridge/CLAUDE.md`](agents/prodrive-homebridge/CLAUDE.md)
- Cross-repo context: [`agents/prodrive-context/`](agents/prodrive-context/)
- Skills: installed via the `prodrive-knowledge` plugin (run `/plugin` to inspect). Source lives under [`agents/skills/`](agents/skills/).

To pull updates:
```bash
git submodule update --init --remote agents
```
