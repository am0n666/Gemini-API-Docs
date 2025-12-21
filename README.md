# Gemini API Documentation

This repository contains the complete Gemini API documentation automatically downloaded and organized for easy reference.

## Automatic Updates

This repository uses GitHub Actions to automatically download the latest Gemini API documentation. The workflow runs on every push to the main branch and can also be triggered manually.

Documentation files are stored in the `docs/` directory.

## Table of Contents

### Get Started
- [docs.md](./docs/docs.md) - Main Gemini API documentation
- [quickstart.md](./docs/quickstart.md) - Quick start guide
- [api-key.md](./docs/api-key.md) - API key setup and management
- [libraries.md](./docs/libraries.md) - Available libraries and SDKs
- [interactions.md](./docs/interactions.md) - Basic interactions with Gemini API

### Models
- [models.md](./docs/models.md) - Available models overview
- [gemini-3.md](./docs/gemini-3.md) - Gemini 3 model documentation
- [nanobanana.md](./docs/nanobanana.md) - Nano and Banana models
- [video.md](./docs/video.md) - Video model capabilities
- [music-generation.md](./docs/music-generation.md) - Music generation model
- [imagen.md](./docs/imagen.md) - Imagen image generation model
- [embeddings.md](./docs/embeddings.md) - Embeddings model
- [robotics-overview.md](./docs/robotics-overview.md) - Robotics model overview
- [pricing.md](./docs/pricing.md) - Pricing information
- [rate-limits.md](./docs/rate-limits.md) - Rate limits and quotas

### Core Capabilities
- [text-generation.md](./docs/text-generation.md) - Text generation capabilities
- [video-understanding.md](./docs/video-understanding.md) - Video understanding
- [document-processing.md](./docs/document-processing.md) - Document processing
- [structured-output.md](./docs/structured-output.md) - Structured output generation
- [function-calling.md](./docs/function-calling.md) - Function calling capabilities
- [long-context.md](./docs/long-context.md) - Long context handling

### Tools
- [tools.md](./docs/tools.md) - Tools and integrations overview
- [deep-research.md](./docs/deep-research.md) - Deep research capabilities
- [google-search.md](./docs/google-search.md) - Google Search integration
- [maps-grounding.md](./docs/maps-grounding.md) - Maps grounding
- [code-execution.md](./docs/code-execution.md) - Code execution capabilities
- [url-context.md](./docs/url-context.md) - URL context retrieval
- [computer-use.md](./docs/computer-use.md) - Computer use capabilities
- [file-search.md](./docs/file-search.md) - File search functionality

### Live API
- [live.md](./docs/live.md) - Live API overview
- [live-guide.md](./docs/live-guide.md) - Live API guide
- [live-tools.md](./docs/live-tools.md) - Tools for Live API
- [live-session.md](./docs/live-session.md) - Live session management
- [ephemeral-tokens.md](./docs/ephemeral-tokens.md) - Ephemeral tokens

### Advanced
- [batch-api.md](./docs/batch-api.md) - Batch API
- [files.md](./docs/files.md) - File handling
- [caching.md](./docs/caching.md) - Caching mechanisms
- [openai.md](./docs/openai.md) - OpenAI compatibility
- [media-resolution.md](./docs/media-resolution.md) - Media resolution
- [tokens.md](./docs/tokens.md) - Token management
- [prompting-strategies.md](./docs/prompting-strategies.md) - Prompting strategies

## Workflow

The documentation is automatically downloaded using GitHub Actions. You can find the workflow configuration in `.github/workflows/main.yml`.

### Manual Trigger

To manually trigger the download workflow:

1. Go to the [Actions](../../actions) tab
2. Select "Download Gemini API Docs"
3. Click "Run workflow"

## Structure

```
.
├── docs/
│   ├── docs.md
│   ├── quickstart.md
│   ├── api-key.md
│   ├── libraries.md
│   ├── interactions.md
│   ├── ... (and all other documentation files)
├── .github/
│   └── workflows/
│       └── main.yml (Automated download workflow)
└── README.md
```

## Source

All documentation is downloaded from the official [Google AI Studio](https://ai.google.dev/) documentation.

## Last Updated

Documentation is automatically updated whenever changes are pushed to the main branch or when manually triggered through GitHub Actions.
