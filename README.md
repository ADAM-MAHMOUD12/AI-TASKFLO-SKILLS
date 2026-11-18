# AI TaskFlow Skills

The shared, open skills library for AI TaskFlow and TF CODE.

The root `catalog.json` publishes reusable `SKILL.md` instructions. AI TaskFlow
can add a selected skill to the signed-in user's chat library. TF CODE can add
the same skill to the active workspace and sync it to that account, so it is
available in AI TaskFlow chats using the account's configured AI provider.

## Install locations

- AI TaskFlow stores selected skills with the signed-in account.
- TF CODE writes selected skills to `.agents/skills/` in the open workspace and
  syncs them to the same signed-in account.
- Public skills can also be searched in the skills.sh library. They remain
  attributed to their original source and are downloaded only after the user
  chooses to add one.

## Catalog format

The version 1 catalog lists Markdown `SKILL.md` files under `skills/`. Keep
IDs unique, lowercase, and limited to letters, digits, and hyphens. Review
each skill's instructions and source before adding it; skill instructions are
sent to the selected AI provider when used in chat.
