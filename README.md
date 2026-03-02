# 🌐 PartyUnNoobifier - i18n

Community-maintained translation files for [PartyUnNoobifier](https://modrinth.com/mod/pun).

## 📂 Structure

Each language file is a JSON with `"key": "translated text"` pairs.

| File         | Language   | Status                  |
| ------------ | ---------- | ----------------------- |
| `en_UK.json` | 🇬🇧 English | ✅ Complete (reference) |
| `fr_FR.json` | 🇫🇷 French  | ✅ Complete             |
| `de_DE.json` | 🇩🇪 German  | ✅ Complete             |

## 🤝 How to Contribute

1. **Fork** this repository
2. **Copy** `en_UK.json` and rename it to your locale (e.g. `es_ES.json`, `pt_BR.json`, `ja_JP.json`)
3. **Translate** all values (keep the keys unchanged!)
4. **Open a Pull Request** with your translation

### Guidelines

- ✅ Translate only the **values** (right side), never the keys (left side)
- ✅ Keep `{placeholders}` like `{user}`, `{count}`, `{reason}` exactly as-is
- ✅ Keep Minecraft formatting codes (`§a`, `§b`, `§l`, etc.) in the same positions
- ✅ Use `en_UK.json` as reference — it's always up to date
- ❌ Don't translate technical terms like "Dungeons", "Kuudra", "Party"
- ❌ Don't modify the JSON structure or add/remove keys

### Locale Code Format

Use the format `language_COUNTRY`, for example:

- `es_ES` — Spanish (Spain)
- `pt_BR` — Portuguese (Brazil)
- `ja_JP` — Japanese
- `zh_CN` — Chinese (Simplified)
- `ko_KR` — Korean

## 🔗 Links

- [PartyUnNoobifier on Modrinth](https://modrinth.com/mod/pun)
- [Discord](https://discord.com/invite/Y6ADqB3zGv)
