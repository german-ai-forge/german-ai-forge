# Hi, I'm German Rodriguez — `german-ai-forge`

Solution Engineer | Software Development Specialist | Certified Data & AI Engineer  
Bridging business needs and technical execution through scalable AI and data systems  
Turning customer problems into elegant, production-ready solutions

---

## 🛠️ What I Do

- 🔍 Extract, clean, and transform real-world data for analytics & machine learning  
- ⚙️ Build reliable pipelines with Delta Lake, APIs, and schema validation  
- 🧩 Act as a bridge between technical teams and stakeholders to deliver real-world solutions  
- 🧾 Translate customer needs into clear, developer-friendly technical documentation  
- 🤖 Integrate AI/LLMs (OpenAI, LangChain, Mistral, Whisper) to solve real business problems  
- 🔐 Champion data governance — quality, lineage, control  

---

## 🔧 Tech Stack

- **Languages:** Python, JAVA, SQL  
- **Data Tools:** pandas, Delta Lake, PyArrow, FastAPI, MongoDB  
- **AI/LLM Tools:** OpenAI API, Mistral, Whisper, LangChain (in progress), prompt engineering  
- **Governance:** schema enforcement, last-run control, deduplication  
- **Infra & Dev:** Git, VSCode, Postman, REST APIs  

---

## 📂 Featured Projects

- [MonitoringLogs](https://github.com/german-ai-forge/MonitoringLogs) – Fleet log monitoring project (Software Engineering with Python & Git).  
- [coingecko-deltalake-pipeline](https://github.com/german-ai-forge/coingecko-deltalake-pipeline) – ETL pipeline using CoinGecko API + Delta Lake.  
- [Ticketing System](https://github.com/german-ai-forge/events3287) – Microservices architecture with Flask & MongoDB.  
- [Radio Data Pipeline](https://github.com/german-ai-forge/radio_pipeline) – End-to-end pipeline for radio audio streams with Whisper, Mistral, and heuristics.  

---

### 🎙️ [Radio Data Pipeline](https://github.com/german-ai-forge/radio_datalake_python)

> Experimental AI + Data Engineering project that transforms **live radio audio** into structured, analytics-ready data.  

#### 📝 Project Bio  
- Capture **radio streams** as raw audio.  
- Transcribe with **Whisper** (speech-to-text).  
- Classify with **Mistral LLM + heuristic rules** (ads, music, talk/news).  
- Store in **Delta Lake** layers: Bronze → Silver → Gold.  
- Demonstrates **hybrid AI + heuristics** for accuracy & explainability.  

#### 🚀 Usage  
```bash
# Extract & transcribe
python extract.py --source <radio_stream_url>
python transcribe.py --input data/bronze/audio.wav --output data/silver/

# Classify with Mistral + heuristics
python classify.py --input data/silver/transcripts.json --output data/gold/

# Full pipeline
python main.py --source <radio_stream_url>

🧩 Hybrid AI + Heuristics Approach
Whisper: generates transcript

Heuristics: first-pass rules (e.g., ads < 15s, music = long non-speech, keywords like “discount”)

Mistral LLM: validates, overrides, enriches classification

Delta Lake: stores final enriched dataset

🪙 CoinGecko Delta Lake Pipeline
Real-world ELT pipeline using CoinGecko's public API
Full & incremental extractions
Silver-layer transformations with pandas
Delta Lake storage, partitioned by time

Data governance: schema, deduplication, last run tracking

📚 Learning & Goals
🎓 Finalizing my Data Engineer Certification

📈 Building LLM-based tools (retrievers, chatbots, agents)

🧩 Exploring LangChain, vector DBs & low-code AI tooling

🌐 Seeking remote opportunities in AI or Data Engineering


## 📫 Let’s Connect

- [LinkedIn] https://www.linkedin.com/in/german-rodriguez-93211a53/
- GitHub: [german-ai-forge](https://github.com/german-ai-forge)

---

“I don’t just build AI — I forge reliable systems where data is trusted, governed, and useful.”


