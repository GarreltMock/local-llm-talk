---
layout: section
---

# State of the Art

---

# Wie sieht die Modell-Landschaft aus

1. gpt-oss
2. Qwen
3. Deepseek
4. Mistral
5. Gemma
6. Llama

---

## Welche Fähigkeiten haben wir
1. Chat
2. Tool Usage
3. Visual
4. Image-Gen
5. Voice

=> Hängen den Cloud Model um nichts hinterher

---

# Performance

<!--
https://openai.com/de-DE/index/introducing-gpt-oss/
https://help.openai.com/en/articles/9624314-model-release-notes#h_cb793d13ca
 -->

- gpt-oss:20b  = gpt-o3mini
- gpt-oss:120b = gpt-o4mini

![gpt-oss benchmarks](/img/gpt-oss_benchmark.png)

<!-- Hier möchte ich noch viel mehr machen -->

---

## Benchmark-Exkurs

- Quellen für Benchmarks
- Was sind das für Benchmark-Tests?
    - Bekanntester: MMLU (Massive Multitask Language Understanding)
    - Software: SWE-Bench, HumanEval
> 	AIME, GPQA, Humanity’s Last Exam sind OpenAI-spezifische, hochschwierige Reasoning-Tests, die über die Community-Benchmarks hinausgehen.
>	GSM8K, HumanEval, BBH, MT-Bench sind die üblichen offenen Benchmarks, die viele Labore und Leaderboards vergleichen.

- Aber Vorsicht:
    - Synthetic Tasks # Real-World Performance
    - Benchmark-Hacking möglich
    - Domain-spezifische Performance variiert stark