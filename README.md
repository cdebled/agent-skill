# Lightpanda Skill for LLM Agents

A skill that provides integration with [Lightpanda](https://github.com/lightpanda-io/browser), a fast headless browser optimized for data extraction and web automation.

## What is this?

This is a generalist skill for LLM agents (Claude Code, Openclaw, and others) that teaches agents how to use Lightpanda as a drop-in replacement for Chrome/Chromium when performing web scraping and automation tasks.

## Features

- Faster and lighter than Chrome for headless operations
- CDP (Chrome DevTools Protocol) compatible
- Works with Playwright and Puppeteer
- JavaScript execution support
- Accessibility tree extraction

## Installation

### Via [skills.sh](https://skills.sh)

```bash
npx skills add lightpanda-io/agent-skill
```

### Manual

Copy `SKILL.md` to your agent's skills directory, then run the install script to download the Lightpanda binary:

```bash
bash scripts/install.sh
```

## Platform Support

- Linux (x86_64, aarch64)
- macOS (x86_64, arm64)
- Windows is not supported

## Usage

See [SKILL.md](SKILL.md) for detailed usage instructions, including:

- Starting the browser server
- Connecting with Playwright or Puppeteer
- Extracting accessibility trees
- Important notes and limitations

## License

Apache 2.0
