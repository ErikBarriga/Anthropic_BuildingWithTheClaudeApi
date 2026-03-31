# Building with the Claude API

Jupyter notebooks for learning and experimenting with the Anthropic Claude API.

## Setup

### 1. Install dependencies

```bash
pip install anthropic python-dotenv
```

### 2. Create your `.env` file

Copy the example file and add your API key:

```bash
cp .env.example .env
```

Then edit `.env` and replace the placeholder with your actual key:

```
ANTHROPIC_API_KEY="your-api-key-here"
```

You can get an API key from the [Anthropic Console](https://console.anthropic.com/).

### 3. Model selection

The notebooks use `claude-haiku-4-5-20251001` by default. You can change this to any model available on your account, such as:

- `claude-haiku-4-5-20251001`
- `claude-sonnet-4-6-20250527`
- `claude-opus-4-6-20250527`

To check which models are enabled on your account, go to the [Anthropic Console](https://console.anthropic.com/) and navigate to **Settings > Models**.
