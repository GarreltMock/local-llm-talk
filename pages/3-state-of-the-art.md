---
layout: section
transition: view-transition
---

# Model Landschaft {.inline-block.view-transition-title}


---
title: Model Landschaft
class: flex flex-col h-full
---

# Model Landschaft {.inline-block.view-transition-title}


<div class="flex-grow relative mt-12">

<div v-click class="flex flex-col items-center absolute logo-0"  v-motion :enter="{ x: 0, y: 0 }"  :initial="{ x: 0, y: -80 }"><img src="/img/logos/openai.png" class="inline-block size-[4em] mb-2 color-white rounded-full" />openai</div>
<div v-click class="flex flex-col items-center absolute logo-1"  v-motion :enter="{ x: 0, y: 0 }"  :initial="{ x: 0, y: -80 }"><img src="/img/logos/qwen_logo.png" class="inline-block size-[4em] mb-2 color-white rounded-full bg-white p-2" />qwen</div>
<div v-click class="flex flex-col items-center absolute logo-2"  v-motion :enter="{ x: 0, y: 0 }"  :initial="{ x: 0, y: -80 }"><img src="/img/logos/deepseek.png" class="inline-block size-[4em] mb-2 color-white rounded-full bg-white p-2" />deepseek</div>
<div v-click class="flex flex-col items-center absolute logo-3"  v-motion :enter="{ x: 0, y: 0 }"  :initial="{ x: 0, y: -80 }"><img src="/img/logos/gemma.png" class="inline-block size-[4em] mb-2 color-white rounded-full bg-white p-2" />gemma</div>
<div v-click class="flex flex-col items-center absolute logo-4"  v-motion :enter="{ x: 0, y: 0 }"  :initial="{ x: 0, y: -80 }"><img src="/img/logos/microsoft-color.png" class="inline-block size-[4em] mb-2 color-white rounded-full bg-white p-2" />phi</div>
<div v-click class="flex flex-col items-center absolute logo-5"  v-motion :enter="{ x: 0, y: 0 }"  :initial="{ x: 0, y: -80 }"><img src="/img/logos/meta-color.png" class="inline-block size-[4em] mb-2 color-white rounded-full bg-white p-2" />llama</div>
<div v-click class="flex flex-col items-center absolute logo-6"  v-motion :enter="{ x: 0, y: 0 }"  :initial="{ x: 0, y: -80 }"><img src="/img/logos/mistral.png" class="inline-block size-[4em] mb-2 color-white rounded-full bg-white p-2" />mistral</div>

</div>

<style scoped>
.logo-0 { left: 0%;   top: 0%;   }
.logo-1 { left: 15%; top: 9.38%; }
.logo-2 { left: 30%; top: 18.75%; }
.logo-3 { left: 45%;   top: 28.13%; }
.logo-4 { left: 60%; top: 37.50%; }
.logo-5 { left: 75%; top: 46.88%; }
.logo-6 { left: 90%;  top: 56.25%; }

</style>

---
title: Models
clicks: 9
---

# Model Auswahl

## **Modelname**:

<div class="flex flex-col items-center mt-4 mb-12 gap-6">
<h3><span :class="[$clicks > 0 && 'bg-red']">Qwen/</span><span :class="[$clicks > 1 && 'bg-blue']">Qwen3-Coder-</span><span :class="[$clicks > 2 && 'bg-purple']">30B-</span><span :class="[$clicks > 3 && 'bg-orange']">A3B-</span><span :class="[$clicks > 4 && 'bg-green']">Instruct</span></h3>

<h3 v-click="6"><span class="bg-red">openai/</span><span class="bg-blue">gpt-oss-</span><span class="bg-purple">20b</span></h3>

<h3 v-click="7"><span class="bg-red">deepseek-ai/</span><span class="bg-blue">DeepSeek-Coder-V2-</span><span class="bg-purple">Lite-</span><span class="bg-green">Base</span></h3>
</div>

<v-click at="8">

<div class="relative flex justify-center items-center mb-10">
<h2 class="absolute top-1/2 -translate-y-1/2 left-0"><strong>Modeltyp</strong>:</h2>
<logos-apple class="inline-block bg-white p-2 rounded-full size-[3em]" /> <h2 class="mx-6">MLX vs. GGUF</h2> <img src="/img/logos/nvidia-color.png" class="inline-block color-white rounded-full bg-white p-2 size-[3em]" />
</div>

</v-click>

<v-click at="9">

<div class="relative flex justify-center">
<h2 class="absolute top-0 left-0"><strong>Modelgröße</strong>:</h2>
<h2>Parameter & Quantisierung</h2>
</div>

Abwägung zwischen Größe, Performance und Qualität

</v-click>

<!-- Idee hier die Token visualisierung zu nehmen -->
<!-- Hier auch einfach auf Huggingface die Modellliste zeigen -->
<!-- Oder als iFrame einbinden -->


---
title: Fähigkeiten
class: flex flex-col h-full
---

# Fähigkeiten

<div class="flex flex-wrap justify-center content-center w-full gap-6 text-6 flex-grow">

<div class="rounded-lg border-2 border-color-gray color-gray font-bold  px-4 h-fit">💬 Chat</div>
<div class="rounded-lg border-2 border-color-red color-red font-bold  px-4 h-fit">👀 Vision</div>
<div class="rounded-lg border-2 border-color-blue color-blue font-bold  px-4 h-fit">🛠️ Tool Usage</div>
<div class="rounded-lg border-2 border-color-purple color-purple font-bold  px-4 h-fit">🧠 Reasoning</div>
<div class="rounded-lg border-2 border-color-green color-green font-bold  px-4 h-fit">🌅 Image / Video</div>
<div class="rounded-lg border-2 border-color-orange color-orange font-bold  px-4 h-fit">🗣️ Voice</div>

</div>

### → Hängen den Cloud Model um nichts hinterher

---
title: Performance
class: flex flex-col h-full
---

# Performance

<!-- ## Benchmarks -->

<!--
https://openai.com/de-DE/index/introducing-gpt-oss/
https://help.openai.com/en/articles/9624314-model-release-notes#h_cb793d13ca
 -->

:::div{class="flex flex-grow my-2 min-h-0 gap-4"}

![gpt-oss benchmarks](/img/benchmarks/chart2.png){class="object-contain h-full"}
![gpt-oss benchmarks](/img/benchmarks/chart.png){class="object-contain h-full"}

:::

<v-clicks>

<div class="absolute top-[8%] right-10 flex gap-6 text-5">
<div class="rounded-lg border-2 border-color-[#CEDFFE] color-[#CEDFFE] font-bold px-4 h-fit bg-white/20">
oss:120b ~ o4mini
</div>

<div class="rounded-lg border-2 border-color-[#A3BEFA] color-[#A3BEFA] font-bold px-4 h-fit bg-white/20">
oss:20b  ~ o3mini
</div>
</div>

</v-clicks>

<!-- TODO: Hier möchte ich noch viel mehr machen -->

---

# Benchmark-Exkurs

<v-clicks>

- Was sind das für Benchmark-Tests?
    - Bekanntester: `MMLU` (Massive Multitask Language Understanding)
    - Software: `SWE-Bench`, `HumanEval`
- `GSM8K`, `HumanEval`, `BBH` und `MT-Bench`: Open-Source Benchmarks, nutzen Labore und Leaderboards
- `AIME`, `GPQA` und `Humanity’s Last Exam`: OpenAI-spezifische, hochschwierige Reasoning-Tests, gehen über Community-Benchmarks hinaus

→ Meine Lieblingsquelle: [LM Arena](https://lmarena.ai/leaderboard)

<div class="mt-6 p-4 pt-1 bg-gradient-to-r from-orange-200 to-red-400  rounded-xl p:m-0 color-black shadow-lg">

**Aber Vorsicht:**

    - Synthetic Tasks !== Real-World Performance
    - Benchmark-Hacking möglich
    - Domain-spezifische Performance variiert stark

</div>

</v-clicks>


