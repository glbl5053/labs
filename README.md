# GLBL 5053 Workshops

Student-facing workshop pages and notebooks for GLBL 5053: Applied AI for Global Affairs I, Fall 2026.

## Pages

- [Week 6: A tiny agent](week-06/): what an agent is, a notebook that builds one in six steps, and the same task in an open-source agent
- [What is an AI agent?](week-06/what-is-an-agent.html): the Week 6 slides, as one self-contained file (arrow keys step through)
- [What is an AI agent? (short)](week-06/what-is-an-agent-short.html): a 24-slide cut of the Week 6 slides
- [How Claude watermarks its text](week-06/watermarking.html): an interactive page that builds a toy text watermark with the digits of pi as the key
- [Week 5: Calling models directly](week-05/): API introduction, the model-comparison notebook, and Karpathy's GPT materials
- [A map of the model list](week-05/models.html): how to read the OpenRouter catalog

The HTML files have no build step. After cloning, open `index.html` directly in Chrome, Safari, or Firefox, or serve the repository locally:

```bash
python3 -m http.server 8000
```

## Sources

The Week 5 API introduction and notebook are adapted from CPSC 1710 Lab 4 (`cpsc1710/labs`, `lab-04/`). The notebook's key setup, key check, and embedding section follow that lab; the model ladder and side-by-side experiments are new. The Week 6 notebook reuses the Week 5 key setup; its tiny agent and the recorded run on the Week 6 page are new. The optional last part runs [pi](https://github.com/earendil-works/pi) (MIT license) inside Colab. The short Week 6 slides keep 24 of the full deck's 30 slides. The watermarking page is adapted from a CPSC 1710 Week 7 page; only the course labels and the opening paragraph changed. Its facts about Claude come from Anthropic's post [How Claude's text watermarking works](https://www.anthropic.com/news/claude-text-watermark) (August 14, 2026).

Model names and prices on `week-05/models.html` were read from OpenRouter's public catalog on October 5, 2026.

## Credits

Materials are by [Xiuye Chen](https://github.com/xiuyechen) and shared under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Pages were drafted by Claude (Anthropic) and Codex (OpenAI), based on the direction of Xiuye Chen.
