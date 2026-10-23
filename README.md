# Phos & Kin — language packs

Quotes and greeting-card messages for the Phos & Kin app, written natively for each language. © Sustain Digital.

| Path | What |
|---|---|
| `manifest.json` | Each language's current pack: version, file, size, SHA-256. The app reads it when someone picks a language. |
| `packs/<lang>-<version>.pack` | One encrypted pack per language (3,000 quotes and the card messages). English also ships inside the app; the others download once and then work offline. |
| `packs/<lang>/additional.json`, `quotes/v1.json` | Only for app versions before 1.0.4 (their "Get New Quotes" button). Remove once those versions are gone. |

Packs are built by `tool/build_packs.py` in the private app repo from its `content/<lang>.json` files. Don't edit them here.

Languages: `en`, `hi`, `ta`, `zh` (Simplified), `ja`, `ko`, `ar`, `de`, `fr`.

**Review status:** non-English text was written by AI and still needs native-speaker review before marketing.
