---
layout: section
---

# Wie binde ich das jetzt ein?

---
class: flex flex-col h-full
---

# Chat Apps

<div class="flex w-full flex-grow items-center justify-center gap-10">

<img v-click src="/img/logos/ollama.png" class="inline-block size-[10em] mb-2 color-white rounded-[20%] bg-white p-2" />

<img v-click src="/img/logos/lmstudio.png" class="inline-block size-[10em] mb-2 color-white rounded-[20%] bg-white p-2" />

</div>

<div v-click class="mt-6 p-2 bg-purple-400 rounded-lg">
<strong>Alternativen:</strong> LibreChat, Cherry-Studio
</div>

---
title: VS Code Integration
class: flex h-full gap-8
---

<div class="flex-grow">

# VS Code
[Continue](https://www.continue.dev/)

<br>

### ⚙️ **Setup**
1. VSCode Extension installieren
2. Config anpassen (`~/.continue/config.json`) →
3. LM Studio Server einstellen
4. Fertig! 🎉

<br>

> ✅ Chat wirkt super<br>
> ⛔ Autocomplete hinkt (Qualität, Features und Speed)

<div class="mt-6 p-2 bg-purple-400 rounded-lg">
<strong>Alternativen:</strong> VS Code Insider, Cline
</div>

</div>

<div class="-mt-11">

```yaml
name: Local Assistant
version: 1.0.0
schema: v1
models:
    - name: qwen2.5-coder:1.5b
      provider: ollama
      model: qwen2.5-coder:1.5b-base
      roles:
          - autocomplete
    - name: qwen3-coder
      provider: lmstudio
      model: qwen/qwen3-coder-30b
      apiBase: http://localhost:1234/v1
      roles:
          - chat
          - edit
          - apply
      capabilities:
          - tool_use
      defaultCompletionOptions:
          contextLength: 131072
          maxTokens: 32768
context:
    - provider: code
    - provider: docs
    - provider: diff
    - provider: terminal
    - provider: problems
    - provider: folder
    - provider: codebase

```

</div>


---
class: flex h-full gap-8
---

<div class="flex-grow">

# CLI Agent

[Opencode](https://opencode.ai/docs/)

<br>

### 🚀 **Installation**

```bash
npm install -g @opencode/cli
```

```bash
#oder
pip install opencode
```

<br>

Kontextlänge bei LM Studio einstellen

> TODO: Ollama lief hier nicht <br>
> Vielleicht weil es nicht kompatibel war? Screenshot zeigen

<div class="mt-6 p-2 bg-purple-400 rounded-lg">
<strong>Alternativen:</strong> Claude Code Router, Aider, Continue (Beta)
</div>

</div>
<div>

`~/.config/opencode/opencode.json`

```json
{
    "$schema": "https://opencode.ai/config.json",
    "provider": {
        "lmstudio": {
            "npm": "@ai-sdk/openai-compatible",
            "name": "LM Studio (local)",
            "options": {
                "baseURL": "http://127.0.0.1:1234/v1"
            },
        }
    }
}
```

</div>
---
layout: section
---

# Reality Check

<br>

<v-clicks>

<p>✅ Boilerplate Code, einfache Funktionen</p>
<p>✅ Code-Erklärungen, Dokumentation</p>
<p>⚠️ Komplexe Algorithmen, Business-Logik</p>
<p>❌ Perfekter Code ohne Review</p>

</v-clicks>

<style scoped>
.slidev-layout h1 + p  {
    opacity: 1
}

p {
    margin: 0;
    margin-bottom: 0.6em;
}
</style>

---

# Bonus

- [Perplexica](https://github.com/ItzCrazyKns/Perplexica)
- [superwhisper](https://superwhisper.com/)
- Image / Video generierung