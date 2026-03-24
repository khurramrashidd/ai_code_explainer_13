# 🦀 Rust AI Code Explainer CLI

A powerful **Command Line AI Tool written in Rust** that analyzes code files and provides explanations and improvements using the **Gemini API (gemini-3-flash-preview model)**.

This tool helps developers understand code quickly and improve code quality.

This project is part of my **Rust learning journey (Day 13 Project)**.

---

## 🚀 Features

* Analyze any code file
* Generate explanation in simple terms
* Suggest improvements
* Uses Gemini 3 Flash model
* Secure API key with `.env`
* Fast and lightweight CLI tool

---

## 🛠 Built With

* **Rust**
* `reqwest`
* `serde_json`
* `dotenv`
* Google Gemini API

---

## 📂 Project Structure

```text
ai_code_explainer_13/
│
├── src/
│   └── main.rs
├── Cargo.toml
├── Cargo.lock
├── .gitignore
├── .env
```

---

## ⚙️ Installation

```bash
git clone https://github.com/yourusername/rust-ai-code-explainer.git
cd rust-ai-code-explainer
cargo build
```

---

## 🔑 Setup

Create `.env` file:

```env
GEMINI_API_KEY=your_api_key_here
```

---

## ▶️ Usage

```bash
cargo run
```

Enter file path when prompted.

---

## 📸 Example

<img width="1383" height="531" alt="image" src="https://github.com/user-attachments/assets/4a98fdb4-264d-4a07-a87a-4b4e346dbb8a" />


---

## 🧠 Concepts Practiced

* File handling in Rust
* AI integration
* Prompt engineering
* CLI input/output
* API requests

---

## 🔮 Future Improvements

* Support multiple files
* Add language detection
* Add code summarization modes
* Export explanation to file
* Add syntax highlighting

---

## 📜 License

MIT License

---

## 👨‍💻 Author

**Khurram Rashid**  
B.Tech Computer Science Engineering  
Amity University Mumbai
