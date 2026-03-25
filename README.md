# LCARS Sound Pack

Fork of [heidilux/openpeon-lcars](https://github.com/heidilux/openpeon-lcars).

I loved the idea but wanted a few less sounds. Removed all but my favorite for each category.

A Star Trek: The Next Generation LCARS-themed sound pack for [peon-ping](https://github.com/PeonPing/peon-ping) / [OpenPeon](https://openpeon.com) (CESP 1.0).

## What is OpenPeon?

[OpenPeon](https://openpeon.com) is an open standard for coding event sounds. It works with Claude Code, Codex, Cursor, Windsurf, and other agentic IDEs — giving you audio feedback as your AI agent works. Sound packs follow the [CESP v1.0 spec](https://openpeon.com/spec) and can be browsed on the [OpenPeon registry](https://openpeon.com).

Want to create your own? Check out the [sound pack creation guide](https://openpeon.com/create).

## Sounds

50 sound effects across 7 event categories:

| Event | Sounds | Description |
|---|---|---|
| `session.start` | 1 | Session initialization |
| `task.acknowledge` | 1 | Task accepted and processing |
| `task.complete` | 1 | Task finished successfully |
| `task.error` | 1 | Something failed |
| `input.required` | 1 | Waiting for user input |
| `resource.limit` | 1 | Rate or quota limit hit |
| `user.spam` | 1 | Too many commands too fast |

## Installation

1. Clone this repo
```bash
git clone https://github.com/heidilux/openpeon-lcars.git
```

2. Install it into your local peon-ping
```bash
peon packs install-local <PATH_TO_FOLDER>/openpeon-simple-lcars
```

## License

Personal use. See `openpeon.json` for details.
