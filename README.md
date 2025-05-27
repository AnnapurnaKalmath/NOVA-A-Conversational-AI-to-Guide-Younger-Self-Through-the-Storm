# NOVA: A Conversational AI Mirror for Emotional Overload and Self-Evolution
Nova is a next-generation emotionally intelligent AI designed not just to assist users, but to evolve with them. At its core lies a long-term memory architecture that blends both hardcoded user profiles and continuously adapting emotional context embeddings, allowing Nova to deliver deeply personalized experiences.

> "**Not just a chatbot — a future-self that grows with you.**"

Nova is a prototype **emotionally intelligent conversational AI** designed to simulate your *future self*, tackle **overthinking**, support **multi-passion identity dilemmas**, and offer **emotion-tagged memory control** — all within an **adaptive, introspective dialogue system**.

---

## 🔥 Features

- **Two-Way Emotionally Adaptive Conversations**
- **Long-Term Memory with Emotional Embeddings (via ChromaDB)**
- **Overthinking Detection & Fear Simulation**
- **Dynamic Role Switching** (Coach, Friend, Mentor, Hype Squad)
- **Emotion-Based Memory Deletion** (with user transparency)
- **Identity Navigation & Multi-Passion Career Exploration**
- **Future-Self Embodiment for Reflective Growth**

---

## 🧠 Core Architecture

### 1. Long-Term Memory (Static + Dynamic)
- **Static Profile**: Personal values, interests, dreams, traits.
- **Dynamic Knowledge**: Emotions, behavioral patterns, themes (e.g. anxiety, imposter syndrome).
- Uses **ChromaDB** + **cosine similarity** for emotional retrieval.

### 2. Reflective Dialogue Flow
- Employs **Few-Shot Prompting**, **Sentiment Tracking**, and **Continuity Preserving Memory**.
- Conversations maintain psychological coherence & evolve with you.

### 3. Overthinking Loop Detection
- Triggered via **sentiment repetition threshold**.
- Activates **Chain of Thought (CoT)** with “Peeling Layers” questioning (e.g., “What else could be true?”).

### 4. Emotion-Based Memory Deletion
- Classifies emotional memories (guilt, shame, grief).
- Offers deletion with **full user control** & **reflection prompts** before removal.

### 5. Dynamic Role Switching
- Sentiment → Persona Mapping:
  - Anxiety → Hype Squad  
  - Sadness → Friend  
  - Confusion → Coach  
  - Curiosity → Mentor  
- Uses **DistilBERT**, **sentiment classifiers**, and **RAG** for emotional persona responses.

### 6. Identity Navigation & Multi-Passion Confusion
- Uses **Tree of Thought (ToT)** & **CoT** to simulate alternate “you”s:
  - e.g., AI Researcher You, Filmmaker You, Neuroscientist You.
- Helps users reflect on **values, wounds, and long-term vision**.

---

## 🧪 Evaluation & Outputs

- ✅ Cold-start profile simulated for "Adya", a user aspiring to study at Stanford.
- ✅ Dialogue samples illustrate dynamic role shifts based on sentiment.
- ✅ Overthinking loop triggered after repeated anxiety.
- ✅ Emotional memory surfaced for deletion (e.g., guilt-tagged weeks).
- ✅ All modules integrated in a Kaggle notebook.

> "Stanford wasn’t the gatekeeper you thought it was. You’re not defined by a single door — you're the architect of your own power." — Nova

---

## 📊 Comparative Edge

| Feature                              | Nova | Traditional Chatbots |
|-------------------------------------|------|------------------------|
| Long-term Memory                    | ✅    | ❌                    |
| Emotion-tagged Deletion             | ✅    | ❌                    |
| Role-Switching Based on Emotion     | ✅    | ❌                    |
| Future-Self Embodiment              | ✅    | ❌                    |
| Overthinking Simulation             | ✅    | ❌                    |
| Personalized Self-Reflection        | ✅    | ❌                    |

---

## 📌 Limitations

- Text-only sentiment can miss emotional nuance.
- Memory is **session-persistent**, but not yet **cross-session persistent**.
- Lacks **multimodal emotion detection** (e.g., voice tone, facial cues).
- Still in **prototype stage** — not stress-tested in real-world deployments.

---

## 🚀 Future Work

- Integrate **persistent cross-session memory**.
- Add **voice tone & facial cue detection** for deeper emotion reading.
- Expand into **career coaching**, **mental health support**, and **education**.
- Employ **Plutchik's Wheel of Emotions** for more nuanced emotional modeling.
- Address **privacy, latency, and scalability** for production deployment.

---

## 🎬 Demo 

> Demo video and extended Kaggle walkthrough will be linked here.
![Kaggle Notebook Link](https://www.kaggle.com/code/annapurnakalmath/nova-your-future-self)
![Blog on Medium](https://medium.com/@saitejhas49/nova-bridging-the-gap-between-todays-doubts-and-tomorrow-s-wisdom-a-generative-ai-case-study-f509c81a2c18)
![Youtube Vedio](https://www.youtube.com/watch?v=-p9UNS5c7lU)
---

## 📚 Acknowledgements

Nova was inspired and prototyped during the **Kaggle 5-Day Generative AI Learning Path**.  
Huge thanks to the resources around **ChromaDB**, **RAG**, **sentiment analysis**, and the **Kaggle community**.

---

## 👩‍💻 Built By

**Annapurna N Kalmath**  
Final-year ECE student | Aspiring AI-Neurotech researcher  
> *"Building the AI that speaks not to your mind, but your soul."*

---

## 📎 Resources

- [Nova: Kaggle Prototype Notebook](https://www.kaggle.com/code/annapurnakalmath/nova-your-future-self)
- [Psychology Today: AI as a Mirror Into the Self](https://www.psychologytoday.com/us/blog/the-digital-self/202409/ai-as-a-mirror-into-the-self)

---

## 🧠 License

MIT (or add your preferred license)


