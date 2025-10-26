---
layout: section
---

# Modell Auswahl


---
title: Modell Landschaft
class: flex flex-col h-full
---

# Modell Landschaft


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
title: Fähigkeiten
class: flex flex-col h-full
---

# Fähigkeiten

<div class="flex flex-wrap justify-center content-center w-full gap-6 text-6 flex-grow">

<v-clicks>
<div class="rounded-lg border-2 border-color-gray color-gray font-bold  px-4 h-fit">💬 Chat</div>
<div class="rounded-lg border-2 border-color-red color-red font-bold  px-4 h-fit">👀 Vision</div>
<div class="rounded-lg border-2 border-color-blue color-blue font-bold  px-4 h-fit">🛠️ Tool Usage</div>
<div class="rounded-lg border-2 border-color-purple color-purple font-bold  px-4 h-fit">🧠 Reasoning</div>
<div class="rounded-lg border-2 border-color-green color-green font-bold  px-4 h-fit">🌅 Image / Video</div>
<div class="rounded-lg border-2 border-color-orange color-orange font-bold  px-4 h-fit">🗣️ Voice</div>
</v-clicks>

</div>

<!-- > TODO: Beispiel Modelle -->

<v-click>

### → Hängen den Cloud Modell um nichts hinterher

</v-click>

---
title: Modelgröße
class: flex flex-col h-full
---

# Modelgröße

## Parameter

<!-- **Verschiedene Gewichtsklassen** -->

<div class="flex justify-around flex-grow items-center [&_p]:m-0 py-3">
    <div class="h-full gap-2 flex flex-col items-center border-1 p-8 rounded-xl shadow-md border-gray shadow-gray">
        <h2 class="flex-grow flex items-center pb-6 font-bold">7B</h2>
        <p><i>Gemma3</i></p>
        <p><strong>4GB</strong> RAM</p>
    </div>
    <div class="h-full gap-2 flex flex-col items-center border-1 p-8 rounded-xl shadow-md border-green shadow-green">
        <h2 class="flex-grow flex items-center pb-6 font-bold text-green">20B</h2>
        <p><i>gpt-oss:20b</i></p>
        <p><strong>16GB</strong> RAM</p>
    </div>
    <div class="h-full gap-2 flex flex-col items-center border-1 p-8 rounded-xl shadow-md border-blue shadow-blue">
        <h2 class="flex-grow flex items-center pb-6 font-bold text-blue">30B</h2>
        <p><i>qwen3-coder</i></p>
        <p><strong>22GB</strong> RAM</p>
    </div>
    <div class="h-full gap-2 flex flex-col items-center border-1 p-8 rounded-xl shadow-md border-purple shadow-purple">
        <h2 class="flex-grow flex items-center pb-6 font-bold text-purple">70B</h2>
        <p><i>hermes-4</i></p>
        <p><strong>38GB</strong> RAM</p>
    </div>
    <div class="h-full gap-2 flex flex-col items-center border-1 p-8 rounded-xl shadow-md border-yellow shadow-yellow">
        <h2 class="flex-grow flex items-center pb-6 font-bold text-yellow">120B</h2>
        <p><i>gpt-oss:120b</i></p>
        <p><strong>60GB</strong> RAM</p>
    </div>
</div>

## Quantisierung

- **Q4_K_M:** Standard, gute Balance
- **Q8_0:** Bessere Qualität, mehr RAM
- **Q2_K:** Sehr kompakt, Qualitätsverlust

<!--
https://vue-bits.dev/components/profile-card
https://vue-bits.dev/components/bounce-cards
-->

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



<div class="absolute top-[8%] right-10 flex gap-6 text-5">
<div v-click="2" class="rounded-lg border-2 border-color-[#CEDFFE] color-[#CEDFFE] font-bold px-4 h-fit bg-white/20">
oss:120b ~ o4mini
</div>

<div v-click="1" class="rounded-lg border-2 border-color-[#A3BEFA] color-[#A3BEFA] font-bold px-4 h-fit bg-white/20">
oss:20b  ~ o3mini
</div>
</div>


---

# Benchmark-Exkurs

<v-clicks>

- Was sind das für Benchmark-Tests?
    - Bekanntester: `MMLU` (Massive Multitask Language Understanding)
    - Software: `SWE-Bench`, `HumanEval`
- `GSM8K`, `BBH`, `MT-Bench`: Open-Source Benchmarks, nutzen Labore und Leaderboards
- `AIME`, `GPQA`, `Humanity’s Last Exam`: OpenAI-spezifische, hochschwierige Reasoning-Tests, gehen über Community-Benchmarks hinaus

<div class="mt-6 p-4 pt-1 bg-gradient-to-r from-orange-200 to-red-400  rounded-xl p:m-0 color-black shadow-lg">

**Aber Vorsicht:**

    - Synthetic Tasks !== Real-World Performance
    - Benchmark-Hacking möglich
    - Domain-spezifische Performance variiert stark

</div>

→ Meine Lieblingsquelle: [LM Arena](https://lmarena.ai/leaderboard)

</v-clicks>


---
layout: section
---

# Abwägung
## zwischen Größe, Performance und Qualität

---
title: Models
clicks: 9
class: flex flex-col h-full
---

# Modell Naming <img src="/img/logos/huggingface-color.png" class="inline-block size-[1.5em]" />

<div class="flex flex-col items-center mt-4 mb-12 gap-6 flex-grow justify-center">
<h3 v-click><span :class="[$clicks > 1 && 'bg-red']">Qwen/</span><span :class="[$clicks > 2 && 'bg-blue']">Qwen3-Coder-</span><span :class="[$clicks > 3 && 'bg-purple']">30B-</span><span :class="[$clicks > 4 && 'bg-orange']">A3B-</span><span :class="[$clicks > 5 && 'bg-green']">Instruct</span></h3>

<h3 v-click="7"><span class="bg-red">openai/</span><span class="bg-blue">gpt-oss-</span><span class="bg-purple">20b</span></h3>

<h3 v-click="8"><span class="bg-red">deepseek-ai/</span><span class="bg-blue">DeepSeek-Coder-V2-</span><span class="bg-purple">Lite-</span><span class="bg-green">Base</span></h3>
</div>

<v-click at="9">

<div class="relative flex justify-center items-center mb-10">
<h2 class="absolute top-1/2 -translate-y-1/2 left-0"><strong>Modeltyp</strong>:</h2>
<logos-apple class="inline-block bg-white p-2 rounded-full size-[3em]" /> <h2 class="mx-6">MLX vs. GGUF</h2> <img src="/img/logos/nvidia-color.png" class="inline-block color-white rounded-full bg-white p-2 size-[3em]" />
</div>

</v-click>

<!-- Idee hier die Token visualisierung zu nehmen -->
<!-- Hier auch einfach auf Huggingface die Modellliste zeigen -->
<!-- Oder als iFrame einbinden -->
