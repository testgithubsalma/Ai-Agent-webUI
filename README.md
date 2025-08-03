# Ai-Agent-webUI

<img src="./assets/web-ui.png" alt="Browser Use Web UI" width="full"/>

<br/>

[![GitHub stars](https://img.shields.io/github/stars/browser-use/web-ui?style=social)](https://github.com/browser-use/web-ui/stargazers)
[![Discord](https://img.shields.io/discord/1303749220842340412?color=7289DA&label=Discord&logo=discord&logoColor=white)](https://link.browser-use.com/discord)
[![Documentation](https://img.shields.io/badge/Documentation-📕-blue)](https://docs.browser-use.com)
[![WarmShao](https://img.shields.io/twitter/follow/warmshao?style=social)](https://x.com/warmshao)

This project builds upon the foundation of the [browser-use](https://github.com/browser-use/browser-use), which is designed to make websites accessible for AI agents.

We would like to officially thank [WarmShao](https://github.com/warmshao) for his contribution to this project.

**WebUI:** is built on Gradio and supports most of `browser-use` functionalities. This UI is designed to be user-friendly and enables easy interaction with the browser agent.

**Expanded LLM Support:** Supports Google, OpenAI, Azure OpenAI, Anthropic, DeepSeek, Ollama etc.

**Custom Browser Support:** You can use your own browser for seamless login and recording features.

**Persistent Browser Sessions:** Option to keep the browser open between AI tasks.

## Installation Guide

### Option 1: Local Installation
1. Clone repo, setup Python, install dependencies.
2. Configure `.env` with API keys.
3. Run with:
   ```bash
   python webui.py --ip 127.0.0.1 --port 7788
