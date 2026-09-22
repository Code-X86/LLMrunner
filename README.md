# LLMrunner

A portable, single-file launcher for running local LLMs on Windows with llama.cpp: model browser with 570 models,
AMD ROCm / NVIDIA CUDA / Vulkan / CPU backends, and a terminal chat with web search, Context7 docs,
sequential thinking and workspace file tools.

## Download

Get `LLMrunner.bat` from the [latest release](https://github.com/Code-X86/LLMrunner/releases/latest), put it in its
own folder and run it. It needs Python 3.10+ and downloads everything else (llama.cpp, models) next to itself.

## Updates

`manifest.json` in this repo holds the current version. LLMrunner checks it on start and offers to update itself;
you can also run `/upgrade` in the model list or `LLMrunner.bat --upgrade`.
