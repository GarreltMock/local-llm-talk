---
title: Hardware
class: flex flex-col
---

# Hardware

<div class="flex-grow flex flex-col items-center justify-center">

## Stichwort: RAM

besser gesagt VRAM

<!-- Meme Wand? Und dann am Ende ein besserwisser mit erhobenem Finger VRAM -->
<!--
Cloud APIs -> Sehr schnell ~100ms
Local GPU -> Schnell ~500ms-2s
Local CPU -> Langsam ~5-30s
Local Mobile -> Sehr langsam ~30s+
-->

</div>

---
title: Hardware
class: flex flex-col h-full
---

# Hardware
## Was für Optionen haben wir
<!-- 1. Mac (unified M-Chip, MLX, gerade super)
2. Grafikkarte / Gaming-PC
3. KLeiner Server - Strix Halo -->

<div class="flex w-full flex-grow">
    <img v-click src="/img/hardware/mac.png" class="min-w-0 basis-0 flex-grow object-contain"/>
    <img v-click src="/img/hardware/grafikkarte.png" class="min-w-0 basis-0 flex-grow object-contain"/>
    <img v-click src="/img/hardware/strix-halo.png" class="min-w-0 basis-0 flex-grow object-contain"/>
</div>

<v-click>

### → unter 1500 - 2000€ eher schwierig

</v-click>

---
title: Software
class: flex flex-col h-full
---

# Software

<div class="flex w-full flex-grow items-center justify-center gap-10">

<div v-click class="flex basis-0 gap-10 flex-grow justify-end flex-col items-center">
<img src="/img/logos/ollama.png" class="inline-block size-[8em] mb-2 color-white rounded-[20%] bg-white p-2" />
<div>

- "Docker für LLMs"
- CLI + REST API
- Automatisches Model Management
- Cross-Platform (Mac, Linux, Windows)

↓ [Download](https://ollama.com/download)

</div>
</div>

<div v-click class="flex basis-0 gap-10 flex-grow flex-col items-center  justify-end ">
<img src="/img/logos/lmstudio.png" class="inline-block size-[8em] mb-2 color-white rounded-[20%] bg-white p-2" />
<div>

- Grafische Benutzeroberfläche
- Model Browser mit Ratings
- Einfaches Download Management
- Local Server Modus

↓ [Download](https://lmstudio.ai/download)

</div>
</div>

</div>

<div v-click class="mt-6 p-2 bg-purple-400 rounded-lg">
<strong>Alternativen:</strong> llama.cpp, vLLM, GPT4All, jan.ai
</div>