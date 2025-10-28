# 🗓️ 07. August 2025

<div class="meme-grid">
    <div></div>
    <h3 v-click="2">Erwartung</h3>
    <h3 v-click="3">Realität</h3>
    <img src="/img/intro/gpt-5_release.png" class="max-h-full object-contain" v-click="1"/>
    <img src="/img/intro/meme_happy.jpg" class="max-h-full" v-click="2"/>
    <img src="/img/intro/meme_sad.jpg" class="max-h-full" v-click="3"/>
    <img src="/img/intro/gpt-oss_release.png" class="max-h-full object-contain" v-click="4"/>
    <div class="relative">
        <img src="/img/intro/me_sad.png" class="max-h-full" v-click="6" />
        <div v-click="[5, 6]" class="oss absolute top-0 w-[200%] h-full flex flex-col justify-center">
            <p>- Open-Source Modell → Open Weights</p>
            <p>- Zwei Größen: 20B und 120B</p>
            <p>- Deutlich kleiner als GPT-5 → Lokal ausführbar</p>
        </div>
    </div>
    <img src="/img/intro/me_happy.png" class="max-h-full" v-click="7"/>
</div>

<style>
.meme-grid {
    height: 90%;
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr)); /* erlaubt echtes Schrumpfen */
    grid-template-rows: auto 1fr 1fr;                /* statt "fit-content" */
    gap: 0;
    grid-row-gap: 12px;
    align-items: stretch;
}

.meme-grid > * {
  min-width: 0;
  min-height: 0;
}

.oss p {
    margin: 6px 0;
}
</style>

<!--
Ich war vorher recht uninteressiert an lokalen LLMs
Die performance wirkte zu schlecht,
aber da ich recht bekannt war mit ChatGPT war ich interessiert.

Da hat sich eine ganz neue Welt eröffnet.
Ich hab das Gefühl, dass
Und ich bin ein bisschen in ein Rabbit Hole gefallen.
-->

---

<!-- <img src="/img/intro/bain_explosion.gif" class="relative left-1/2 transform-translate-x--1/2 h-[40%]" /> -->
<!-- <img src="/img/intro/mindblow-2.gif" class="absolute w-full h-full top-0 left-0 rounded-0" /> -->
<img src="/img/intro/rabbit-hole2.gif" class="absolute w-full h-full top-0 left-0 rounded-0" />

<div v-click="1" class="absolute w-full h-full top-0 left-0 bg-black/50"></div>

<div class="flex w-full h-1/2 justify-between items-center absolute left-0 top-1/2 -translate-y-1/2 gap-6 px-10">
    <img src="/img/intro/reddit.png" class="basis-0 flex-grow  min-w-0 h-fit" v-click />
    <img src="/img/intro/local-llm-setup.jpeg" class="basis-0 min-w-0 flex-grow object-contain" v-click />
    <img src="/img/intro/disc-space.png" class="basis-0 flex-grow  min-w-0 h-fit" v-click />
</div>

---
layout: cover
---

# Wir reisen zum Mars

### Dafür richten wir uns heute mal eine lokale LLM Entwicklungsumgebung ein

<img src="/img/intro/rocket.gif" class="absolute w-1/4 top-0 left-0 rounded-0" />
<img src="/img/intro/computer-cat.gif" class="absolute w-1/4 bottom-0 right-0 rounded-0" />