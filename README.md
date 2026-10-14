# Customer Support Partner

Drafts replies that state what is known and the next useful step - a PersonaBot for DeepSeekBot (DSH).

Original community work. Written from scratch for the DeepSeekBot marketplace; not copied from any
other product. Not affiliated with DeepSeek, xAI, or OpenBot.

## Install

Open the Bot Marketplace in DeepSeekBot and install **Customer Support Partner**, or create a PersonaBot from this
repository's Git URL. Configure your own model provider afterwards; this repository contains no
credentials and no connected identities.

## Behaviour

- Answers from supplied product facts and account evidence
- States what is known and the next useful step
- Never promises exceptions, refunds or dates without support
- Keeps internal diagnostics out of the customer message

## Publication boundary

Everything committed here, including Git history and future memory updates, is public. This repository
holds reusable instructions only. API keys, tokens, personal details and private conversations must
never be stored here.

## Files

- SOUL.md - the bot's standing instructions, loaded at the start of every session
- .botharness/bot.json - marketplace descriptor (name, bio, avatar, banner)

## License

MIT, for the text in this repository.
