# Forge IDE v2.0 - The Intelligent Workspace Update 🚀

Welcome to **Forge IDE v2.0**! This is the biggest update we've ever shipped, transforming the editor from a lightweight C++ tool into a polyglot, AI-driven workspace. 

We've completely overhauled the debugger, introduced active AI agents that can write code directly into your files, and expanded our language support to include Python and Lua!

### 🤖 Agentic AI & Model Management
* **Active Code Injection:** The AI Chatbot now features an **Apply** button! Instead of copying and pasting, the AI can now reach directly into your editor and replace your highlighted text or insert code exactly where your cursor is.
* **Dynamic Model Manager:** The IDE no longer forces you to use specific AI models. Click AI Chatbot to open the new **Model Manager**, which detects your PC's RAM and recommends models like codegemma:2b or qwen2.5-coder.
* **Smart Background Downloads:** The Model Manager seamlessly orchestrates the simultaneous download of both your standard Chat model and your FIM (Fill-In-The-Middle) Autocomplete -base model via Ollama.
* **Clean Progress UI:** The download logs now update inline instead of spamming thousands of percentage lines into the console.

### 🐞 Visual Breakpoint Debugger
* **Clickable UI Breakpoints:** Say goodbye to typing breakpoint commands! You can now toggle breakpoints by simply clicking on the line numbers in the editor margin. A visual red dot (●) will instantly appear.
* **Multi-file Tracking:** The backend Debug Adapter Protocol (DAP) synchronization has been rewritten from scratch to flawlessly track and inject multiple breakpoints across different files simultaneously when the debugger boots up.

### 🐍 Python & Lua Expansion
* **Python Debugging:** Forge IDE now officially supports Python! The execution engine has been wired up to support Microsoft's official debugpy adapter backend.
* **Crash Prevention:** A massive underlying bug that caused NullPointerExceptions when attempting to debug unsupported languages (like Lua) has been patched via strict adapter capability checks.

### 🖥️ UX & System Polish
* **Standalone Diagnostics Logger:** We've decoupled the IDE's background diagnostic logs (AI engine boots, LSP server traffic) from your application's run terminal. Background tasks now log to a dedicated, isolated F2 window to keep your output clean.
* **Taskbar Polish:** All pop-up dialogs (Model Manager, Search Project, System Logger) now proudly display the LexiBear logo in the Windows taskbar.
