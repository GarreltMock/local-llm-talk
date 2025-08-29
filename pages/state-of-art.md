# State of the Art – Wo stehen wir?

---

## Überblick: Die wichtigsten Modelle

<div class="grid grid-cols-2 gap-6">

<div>

### 🦙 **LLaMA 3.1**
- **Größen:** 7B, 70B, 405B
- **Highlight:** Sehr gute Code-Generation
- **Hardware:** 8GB - 200GB+ RAM

### 🌪️ **Mistral & Mixtral**  
- **Mistral 7B:** Kompakt, schnell
- **Mixtral 8x7B:** Mixture-of-Experts
- **Hardware:** 8GB - 48GB RAM

</div>

<div v-click>

### 🔬 **Phi-3**
- **Microsoft Research**
- **Phi-3 Mini:** 3.8B Parameter
- **Highlight:** Sehr effizient, kleine Modelle

### 🔥 **gpt-oss (DeepSeek-R1)**
- **Aktueller Hype-Train**
- **Reasoning-fokussiert**
- **Ähnlich zu o1-Preview**

</div>

</div>

---

## Benchmarks & ihre Aussagekraft

<div class="overflow-x-auto">

| Modell | MMLU | HumanEval | RAM | Besonderheit |
|--------|------|-----------|-----|--------------|
| **LLaMA 3.1 7B** | 69.4% | 60.4% | 8GB | Allrounder |
| **Mistral 7B** | 64.1% | 40.2% | 8GB | Schnell |
| **Phi-3 Mini** | 69.1% | 61.0% | 4GB | Effizient |
| **gpt-oss** | ~78%* | ~65%* | 16GB | Reasoning |

</div>

<v-click>

<div class="mt-6 p-4 bg-orange-100 rounded-lg">
<strong>⚠️ Vorsicht bei Benchmarks:</strong>
<ul>
<li>Synthetic Tasks ≠ Real-World Performance</li>
<li>Benchmark-Hacking möglich</li>
<li>Domain-spezifische Performance variiert stark</li>
</ul>
</div>

</v-click>

---

## Hardware-Anforderungen

<div class="grid grid-cols-3 gap-6">

<div>

### 💻 **MacBook M-Serie**
- **M1/M2/M3:** 16GB RAM → 7B Modelle
- **M1/M2/M3 Pro:** 32GB RAM → 13B Modelle  
- **M1/M2 Ultra:** 64-128GB → 70B+ Modelle

<v-click>

**Vorteil:** Unified Memory, sehr effizient

</v-click>

</div>

<div v-click>

### 🎮 **Gaming PC**
- **RTX 3080:** 10GB VRAM → 7B
- **RTX 4080:** 16GB VRAM → 13B
- **RTX 4090:** 24GB VRAM → 70B (quantized)

**Vorteil:** Sehr schnelle Inferenz

</div>

<div v-click>

### 🖥️ **Kleine Server**
- **128GB RAM:** Mehrere 70B Modelle
- **AMD Threadripper:** Viele CPU-Kerne
- **Server-GPUs:** A100, H100 für Enterprise

**Vorteil:** Multi-User, hoher Durchsatz

</div>

</div>

---

## Performance-Vergleich

<div class="text-center">

```mermaid
graph LR
    A[Cloud APIs] --> B[Sehr schnell<br/>~100ms]
    C[Local GPU] --> D[Schnell<br/>~500ms-2s]
    E[Local CPU] --> F[Langsam<br/>~5-30s]
    G[Local Mobile] --> H[Sehr langsam<br/>~30s+]
```

</div>

<v-click>

<div class="mt-6 grid grid-cols-2 gap-6">

<div class="p-4 bg-green-100 rounded-lg">
<strong>✅ Wann ist lokal gut?</strong>
<ul>
<li>Batch-Processing</li>
<li>Asynchrone Anwendungen</li>
<li>Nicht-interaktive Tasks</li>
</ul>
</div>

<div class="p-4 bg-red-100 rounded-lg">
<strong>❌ Wann ist lokal schwierig?</strong>
<ul>
<li>Echtzeit-Chat</li>
<li>Hoher Durchsatz</li>
<li>Mobile Anwendungen</li>
</ul>
</div>

</div>

</v-click>