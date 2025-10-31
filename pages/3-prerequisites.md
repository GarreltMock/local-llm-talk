---
title: Hardware
class: flex flex-col
hide: true
---

# Hardware

## Stichwort: <v-click>RAM (und zwar ne Menge)</v-click>

<div class="flex-grow flex flex-col items-center justify-center">

<ScrollText
    v-click="1"
    :texts="['RAM','RAM','RAM','RAM','RAM',]"
    :velocity="100"
    :damping="50"
    :stiffness="400"
    :velocity-mapping="{ input: [0, 1000], output: [0, 5] }"
    class-name="text-gray"
/>

</div>


---
hide: true
---

# Rechenleistung
Inferenzgeschwindigkeit

<v-clicks>

| *Setup*    | *Geschwindigkeit*      | *Speichertyp*    |
|------------|------------------------|------------------|
| Local GPU  | **Schnell** ~500ms - 2s    | VRAM             |
| Local CPU  | **Langsam** ~5 - 30s       | RAM              |
| Cloud APIs | **Sehr schnell** ~100ms    | 🤷‍♂️               |

</v-clicks>

---
title: Hardware
class: flex flex-col h-full
---

# Hardware

Hauptsächlich: RAM & GPU
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

<!-- TODO: hier die Preise direkt unter den Optionen aufhängen -->

---
title: Software
class: flex flex-col h-full
---

# Software

<div class="flex w-full flex-grow items-center justify-center gap-10">

<div class="flex basis-0 gap-2 flex-grow justify-end flex-col items-center">
<img v-click src="/img/logos/ollama.png" class="inline-block size-[8em] color-white rounded-[20%] bg-white p-2" />
<div v-click="1">

**Ollama**
- CLI + REST API
- Automatisches Model Management
- Cross-Platform (Mac, Linux, Windows)
- "Docker für LLMs"

↓ [Download](https://ollama.com/download)


</div>
<div v-click class="mt-2 p-2 bg-purple-400 rounded-lg">
<strong>Alternativen:</strong> llama.cpp, vLLM
</div>
</div>

<div class="flex basis-0 gap-2 flex-grow flex-col items-center  justify-end ">
<img v-click src="/img/logos/lmstudio.png" class="inline-block size-[8em] color-white rounded-[20%] bg-white p-2" />
<div v-click="3">

**LM Studio**
- Grafische Benutzeroberfläche
- Model Browser mit Ratings
- Einfaches Download Management
- Local Server Modus

↓ [Download](https://lmstudio.ai/download)


</div>
<div v-click class="mt-2 p-2 bg-purple-400 rounded-lg">
<strong>Alternativen:</strong> GPT4All, jan.ai
</div>
</div>

</div>

