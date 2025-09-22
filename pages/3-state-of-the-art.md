---
layout: section
---

# State of the Art
## Wie sieht die Modell-Landschaft aus

1. gpt-oss
2. Qwen3
3. Deepseek
4. Mistral
5. Gemma

---

# Modelnamen

- Qwen/Qwen3-Coder-30B-A3B-Instruct

- MLX vs. GGUF

<!-- Idee hier die Token visualisierung zu nehmen -->

---

# Benchmarks

https://openai.com/de-DE/index/introducing-gpt-oss/
https://help.openai.com/en/articles/9624314-model-release-notes#h_cb793d13ca

![gpt-oss benchmarks](img/gpt-oss_benchmark.png)

- gpt-oss:20b  = gpt-o3mini
- gpt-oss:120b = gpt-o4mini
- qwen3 coding 30b

---

## Kleiner Exkurs in Benchmark-Nutzung

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