# Hands-on: Lokale Tools

---

## Ollama – Der einfache Einstieg

<div class="grid grid-cols-2 gap-8">

<div>

### 🚀 **Was ist Ollama?**
- Docker für LLMs
- CLI + REST API
- Automatisches Model Management
- Cross-Platform (Mac, Linux, Windows)

</div>

<div v-click>

### ⚡ **Quick Start**
```bash
# Installation
curl -fsSL https://ollama.ai/install.sh | sh

# Model laden
ollama pull llama3.1

# Chat starten
ollama run llama3.1
```

</div>

</div>

<v-click>

<div class="mt-6 p-4 bg-blue-100 rounded-lg">
<strong>💡 Perfect für:</strong> Entwickler, CLI-Fans, API-Integration
</div>

</v-click>

---

## LM Studio – UI First Ansatz

<div class="grid grid-cols-2 gap-8">

<div>

### 🖥️ **Features**
- Grafische Benutzeroberfläche
- Model Browser mit Ratings
- Einfaches Download Management
- Chat Interface
- Local Server Modus

</div>

<div v-click>

### 📊 **Vorteile**
- **Anfängerfreundlich:** Drag & Drop Interface
- **Transparenz:** Hardware-Usage in Echtzeit
- **Flexibilität:** Verschiedene Quantisierungen
- **Testing:** A/B-Vergleiche zwischen Modellen

</div>

</div>

<v-click>

<div class="mt-6 p-4 bg-green-100 rounded-lg">
<strong>✅ Perfect für:</strong> Einsteiger, Experimente, schnelle Prototypen
</div>

</v-click>

---

## OpenRouter – Model Playground

<div class="grid grid-cols-2 gap-8">

<div>

### 🔬 **Konzept**
- Zugriff auf 200+ Modelle
- Einheitliche API
- Local + Cloud Models
- Kosten-Transparenz

</div>

<div v-click>

### 💰 **Pricing Vergleich**
```
GPT-4o: $5.00/1M tokens
Claude 3.5: $3.00/1M tokens
LLaMA 70B: $0.80/1M tokens
Mistral 7B: $0.20/1M tokens
```

</div>

</div>

<v-click>

<div class="mt-6 p-4 bg-yellow-100 rounded-lg">
<strong>🎯 Perfect für:</strong> Model-Vergleiche, Testing, Hybrid-Ansatz
</div>

</v-click>

---

## Model Downloads – Die Quellen

<div class="grid grid-cols-3 gap-6">

<div>

### 🤗 **Hugging Face**
- Größte Sammlung
- GGUF, Safetensors
- Community-driven
- Quantisierte Versionen

**Empfehlung:**
- TheBloke's Quantizations
- Microsoft/Meta official

</div>

<div v-click>

### 🚀 **GPT4All**
- Kuratierte Auswahl
- Qualitäts-getestet
- Einfache Downloads
- Desktop App

**Vorteile:**
- Weniger Auswahl = weniger Verwirrung
- Getestet auf Consumer Hardware

</div>

<div v-click>

### 📦 **Ollama Library**
- Automatisches Management
- Optimierte Quantisierung
- Dependency Handling
- Version Control

**Commands:**
```bash
ollama list
ollama pull model:tag
ollama rm model
```

</div>

</div>

---

## Tipps für Model-Selection

<v-clicks>

🎯 **Nach Anwendungsfall wählen:**
- **Code:** CodeLlama, Phi-3, DeepSeek-Coder
- **Chat:** LLaMA 3.1, Mistral, Qwen
- **Reasoning:** gpt-oss, o1-mini alternatives
- **Multilingual:** Qwen, Command-R

📏 **Größe vs. Performance:**
- **7B:** Schnell, MacBook M1 16GB
- **13B:** Gute Balance, MacBook M2 Pro
- **70B:** Beste Qualität, braucht 48GB+ RAM

🔢 **Quantisierung verstehen:**
- **Q4_K_M:** Standard, gute Balance
- **Q8_0:** Bessere Qualität, mehr RAM
- **Q2_K:** Sehr kompakt, Qualitätsverlust

</v-clicks>