# Hi, I'm Marko 👋

Cybersecurity student at **Lviv Polytechnic National University** (Cybersecurity & Information Protection, expected graduation 2029).
I like building practical things with **Python** and **JavaScript**: from REST APIs and ML models to AI agents that resist prompt injection.
Looking for my **first role or internship** in Python development, QA or cybersecurity (SOC).

📍 Lviv, Ukraine · 🌐 Open to remote · 🗣 Ukrainian (native), English (B2)

---

## 🔨 Featured projects

### 🫐 [Berry Quality Scanner](https://github.com/marko812-52/berry-scanner)
Web app that grades a batch of berries from photos and generates a PDF quality report,
built for a fresh-produce company where quality is checked by hand.
Colour-based segmentation plus a trained **MobileNetV3 segmentation model** (ONNX, runs in the browser via WebAssembly),
mould vs. glare/background detection, sorter-vs-app comparison, analytics and Excel export. Works offline as a PWA.
`JavaScript` `PyTorch` `ONNX Runtime Web` `Computer Vision` `PWA` `Cloudflare Pages`

### 🛡 [AI Librarian Agent with prompt-injection defence](https://github.com/marko812-52/ai-librarian-agent)
LLM agent (LangGraph) that answers questions from documents and a book database,
with **direct and indirect prompt-injection filtering**, a canary token to detect system-prompt leaks,
and human-in-the-loop approval before saving long-term memory.
`Python` `LangGraph` `RAG` `LLM Security`

### 🔐 [Password Hash Cracker: sequential vs. multiprocessing](https://github.com/marko812-52/password-hash-cracker)
Brute-forces a SHA-384 hash and compares single-process and `multiprocessing.Pool` performance;
plus a crack-time estimator showing why password length beats complexity.
`Python` `hashlib` `multiprocessing`

### 📚 Book Catalogue REST API — [devops-lab4](https://github.com/marko812-52/devops-lab4)
REST API for publishers, books and authors (1:N and N:M relations) on PostgreSQL in Docker.
Input validation (ISBN-13 checksum, email, phone), Open/Closed storage layer,
CI with linting, type checking and tests on every push.
`Python` `FastAPI` `PostgreSQL` `Docker` `pytest` `mypy` `ruff` `GitHub Actions`

### 👤 [Face Detection & Recognition + classic ML](https://github.com/marko812-52/face-recognition-ml)
SVM and Random Forest on Digits; face detection with OpenCV Haar cascades and recognition
(LBPH, Eigenfaces, Fisherfaces) on photos and video; SVM accuracy 0.98, contract tests for every model.
`Python` `scikit-learn` `OpenCV`

### 📖 [Library Domain Model](https://github.com/marko812-52/library-domain-model)
OOP domain model with enforced invariants (ISBN-13 value object, state machine for write-off)
and a config-driven CSV → JSON/JSONL pipeline built on Dependency Inversion; 50 tests.
`Python` `OOP` `SOLID` `PyYAML` `pytest` `mypy`

---

## 🧰 Tech I use

**Languages:** Python, JavaScript, SQL, HTML, CSS
**Backend:** FastAPI, PostgreSQL, Docker, REST
**AI / ML:** PyTorch, ONNX, scikit-learn, OpenCV, LangGraph, NumPy, pandas
**Security:** prompt-injection defence, password hashing and cracking, network security basics
**Tools:** Git, GitHub Actions, uv, pytest, mypy, ruff, Linux

---

## 📫 Contact

✉️ vorokmarko@gmail.com · 💬 Telegram [@marchik00](https://t.me/marchik00)
<!-- LinkedIn: add link after the profile is created -->
