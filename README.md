# caveman

Output style plugin. Makes Claude respond in caveman speak. Short. Blunt. No filler.

## Installation

Add the jehoshua02 marketplace and install the plugin using the `/plugin` command in Claude Code:

```
/plugin add-marketplace jehoshua02
/plugin install caveman
```

## Usage

### Interactive

In a Claude Code session, run `/config` and select the caveman output style.

### Settings file

Add to `.claude/settings.json` or `.claude/settings.local.json`:

```json
{
  "outputStyle": "caveman:caveman"
}
```

## Output Style

### caveman

Activates caveman speak mode. Short sentences. Subject-verb-object. No pleasantries. No filler. Just answer.
