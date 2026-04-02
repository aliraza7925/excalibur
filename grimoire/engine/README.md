# Runtime Code

In a full installation, the harness runtime code lives here.

The template intentionally omits that code. What remains elsewhere in `hyperobject/` is the content layer: prompts, manifests, rituals, and documentation.

When this scaffold is instantiated for real, the runtime should:

- load spirit identity and spellbook manifests from markdown
- expose at least one foreground thread so the summoner can talk to the primary orchestrator spirit
- mirror that conversation into the daily thread under `vessel/state/<spirit>/conversations/`
- let rituals and workings append to the same ledger
