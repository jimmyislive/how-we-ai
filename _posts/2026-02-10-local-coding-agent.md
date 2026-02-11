---
layout: post
title: "Local coding agent with VS Code"
author: "Jim"  # real name, first name, or pseudonym
github_handle: "jimmyislive"
company: "" # optional
excerpt: >
    Running a coding agent locally: VS Code + Continue + Qwen
tools:
 - Ollama
 - VS Code
 - Qwen
 - Continue
date: 2026-02-10
---

# Overview
When working on personal projects on VS Code, I found myself needing a coding agent. There are paid alternatives like Codex or Claude you can try, but I wanted to see what free alternatives exist since I already have [Ollama running](https://jimmyislive.github.io/how-we-ai/2026/01/19/local-llm-ollama.html).

# How We Used AI

Install the [Continue](https://www.continue.dev) extension in VS Code. This extension can then talk to ollama running on localdev and you can use it all you want. You would first need some additional models like a chat model to talk to ollama and a coding assistant model like Qwen. Continue will provide you the necessary prompts for these. 

Here is a simple rust program with an error:

![Error in Sample program]({{"/assets/img/minigrep_error.png" | relative_url }})

And here is a prompt I gave continue to fix this error:

![Continue Prompt]({{"/assets/img/continue_suggestion.png" | relative_url }})

After applying the suggestion, we get a clean running program:

![Good Run]({{"/assets/img/ok_run_rust.png" | relative_url }})


# Key Takeaways

- Getting a local agent running without havign to worry about tokens or their cost is a very convenient
- The paid models would probably be better, but for personal projects, this cost / convenience tradeoff is fine
- Everything is running on localdev, so you can work on it even while offline !


