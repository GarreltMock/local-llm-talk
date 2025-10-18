# 07. August 2025

<!-- Am 07. August 2025 -> Release von GPT5 -->

<!-- Alle waren so:
GPT-5   Erwartung 🤩 -> Realität 😞

Ich war so:
gpt-oss Erwartung 😞 -> Realität 🤩 -->

<!-- <div>
    <div class="flex h-[20dvh] items-stretch mb-6">
        <div class="flex-grow basis-0"><img src="/img/intro/gpt-5_release.png" class="h-full"/></div>
        <div class="flex justify-end"><img src="/img/intro/meme_happy.jpg" class="h-full"/></div>
        <div class=""><img src="/img/intro/meme_sad.jpg" class="h-full"/></div>
    </div>
    <div class="flex h-[20dvh]">
        <div class="flex-grow basis-0"><img src="/img/intro/gpt-oss_release.png" class="h-full object-contain"/></div>
        <div class=" flex justify-end"><img src="/img/intro/meme_sad.jpg" class="h-full"/></div>
        <div class=""><img src="/img/intro/meme_happy.jpg" class="h-full"/></div>
    </div>
</div> -->

<div class="meme-grid">
    <p></p>
    <p>Erwartung</p>
    <p>Realität</p>
    <img src="/img/intro/gpt-5_release.png" class="max-h-full object-contain"/>
    <img src="/img/intro/meme_happy.jpg" class="max-h-full"/>
    <img src="/img/intro/meme_sad.jpg" class="max-h-full"/>
    <img src="/img/intro/gpt-oss_release.png" class="max-h-full object-contain"/>
    <img src="/img/intro/meme_sad.jpg" class="max-h-full"/>
    <img src="/img/intro/meme_happy.jpg" class="max-h-full"/>
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

# Was ist denn gpt-oss eigentlich?

- oss = open source software
- Open Source Model
    - Open Weights
- Apache 2.0 Lizenz
- Deutlich kleiner als GPT-5
- Lokal ausführbar

<!-- Das hier zeigen bevor ich meine Reaktion darauf zeige -->
<!-- Begriff Cloud Models vs. OSS Models einführen -->

---

<img src="/img/intro/bain_explosion.gif" class="relative left-1/2 transform-translate-x--1/2 h-[40%]" />

<div class="flex w-full justify-between">
    <img src="/img/intro/bain_explosion.gif" class="w-[30%]" />
    <img src="/img/intro/bain_explosion.gif" class="w-[30%]" />
    <img src="/img/intro/bain_explosion.gif" class="w-[30%]" />
</div>
