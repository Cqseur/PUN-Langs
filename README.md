# 🌐 PartyUnNoobifier - i18n

Community-maintained translation files for [PartyUnNoobifier](https://modrinth.com/mod/pun).

## 📂 Structure

Each language file is a JSON with `"key": "translated text"` pairs.

| File         | Language   | Status                  | Credit         |
| ------------ | ---------- | ----------------------- |-----------------|
| `en_UK.json` | 🇬🇧 English | ✅ Complete (reference) |😉|
| `fr_FR.json` | 🇫🇷 French  | ✅ Complete             |🥰|
| `de_DE.json` | 🇩🇪 German  | ✅ Complete             |Knuffiman        |

## 🤝 How to Contribute

### Step 1 — Fork & Translate

1. **Fork** this repository
2. **Copy** `en_UK.json` and rename it to your locale (e.g. `es_ES.json`)
3. **Translate** all the values — see [Guidelines](#guidelines) below

### Step 2 — Open a Pull Request

1. Push your changes to your fork
2. Click **"New Pull Request"** on this repo
3. A **template** will appear in the description — fill in each section:

| Section       | What to fill in                                                                                                                                                              |
| ------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Language**  | Your language name and locale code (e.g. `Spanish` / `es_ES`)                                                                                                                |
| **Credit**    | Your credit text, **translated in your language** (e.g. `por §c§lMyUsername`). This appears next to the language name in-game. The `§c§l` is Minecraft formatting — Tune it as you want! |
| **Checklist** | Check each box to confirm your translation is complete                                                                                                                       |
| **Notes**     | Any extra context (dialect choices, etc.)                                                                                                                                    |

4. Click **"Create pull request"** and wait for review 🎉

### Locale Code Format

Use the format `language_COUNTRY`:

- `es_ES` — Spanish (Spain)
- `pt_BR` — Portuguese (Brazil)
- `ja_JP` — Japanese
- `zh_CN` — Chinese (Simplified)
- `ko_KR` — Korean

## 📝 Guidelines

- ✅ Translate only the **values** (right side), never the keys (left side)
- ✅ Keep `{placeholders}` like `{user}`, `{count}`, `{reason}` exactly as-is
- ✅ Keep Minecraft formatting codes (`§a`, `§b`, `§l`, etc.) in the same positions
- ✅ Use `en_UK.json` as reference — it's always up to date
- ❌ Don't translate technical terms like "Dungeons", "Kuudra", "Party"
- ❌ Don't modify the JSON structure or add/remove keys

## 🔗 Links

- [PartyUnNoobifier on Modrinth](https://modrinth.com/mod/pun)
- [Discord](https://discord.com/invite/Y6ADqB3zGv)
