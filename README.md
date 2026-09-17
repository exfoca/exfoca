<details>
<summary>▶ 🐍</summary>

```python
import base64
import zlib

payload = "eNptj79Kw1AUxp/hPEVewJeoi+Do0DnaSw3mD0jbwckUbQNpXLS0DqLU2xSx3NxqK5VCOoj77Zbg8klAhNoHMBa6uZzv933DOecrMvPAsRh9DXvf8wsCn6IfgE/AY/AOONfAX9H3qGAwu8Zso+RssMoouU+b6VkySH0t9ZLnjSGEUwwChEOEMcIOQo5QkLpSsRotTlWsqXmOL0qqWa5PSi7qixYVmLVVM+z8wh4zdUuvaCW9ottlSkS+fawlvfQ8iT5aSURFwzSPHMtiNmV1L3MbmXuZuTe0qx8b+9X/azTWTZoEOcUogJxAxpAdSA5Zpx3n/VYrM7Nk2MYJQUwg5N+MmhAjRAFEG2K+Zh9C5AltH77dOZr1OXvMf1xdd3+67qr9sPS9pc9/Af2H1hs="

decoded = zlib.decompress(base64.b64decode(payload))
message = bytes((byte - 7) & 0xFF for byte in decoded).decode("utf-8")

print(message)
```

</details>

---

# 👋 Hi, I'm Esdras Cardoso

**Software Engineer** working on **Artificial Intelligence, systems architecture, local-first software, and applied cryptography**.

I build software with an emphasis on strong foundations, explicit boundaries, operational simplicity, and long-term maintainability.

My current work explores how intelligent systems can remain **local, inspectable, interoperable, and under the user's control**.

---

### 🧭 Engineering Principles

I approach software engineering as a discipline of foundations.

That means questioning assumptions before adding abstractions, keeping architectural boundaries explicit, minimizing unnecessary coupling, and introducing complexity only when it solves a concrete problem.

Some principles that consistently influence my work:

* **Local-first when practical**
* **Explicit architecture over accidental architecture**
* **Open standards over unnecessary lock-in**
* **Simple systems before distributed systems**
* **Observability and auditability as architectural properties**
* **Technology should increase human agency, not reduce it**

Software is not an end in itself. I see it as infrastructure for extending human capability, preserving freedom of choice, and making knowledge and computation more accessible.

---

### 🔬 Current Interests

I currently spend most of my time exploring and building around:

* **Local and edge AI**
* **LLM inference and retrieval systems**
* **Agentic architectures**
* **RAG and long-term machine memory**
* **Distributed and event-driven systems**
* **Systems programming**
* **Applied cryptography**
* **Developer infrastructure and tooling**
* **Artificial life and computational experiments**

I am particularly interested in systems that can operate independently of centralized infrastructure while remaining understandable, replaceable, and interoperable.

---

### 🏛 Orion Impact

I founded **[Orion Impact](https://www.orion-impact.com/)** as an independent technology company focused on building technically rigorous software and exploring long-term problems in computing and artificial intelligence.

The company is intentionally broader than any individual product or technology stack.

---

### 🧪 About My Repositories

My repositories usually fall somewhere between **engineering**, **research**, and **experimentation**.

Some become practical tools.

Some are experiments intended to test an architectural or scientific idea.

Others exist simply because I wanted to understand a problem deeply enough to implement it.

I prefer building working systems over treating ideas as purely theoretical exercises.

> Still learning. Still questioning. Still building.

---

### 📖 A Small Git Story

→ [The Magic of Git: An Epic Conversation Between Two Devs](assets/the_magic_of_Git.md)

