# WebCrawlAI: Intelligent Web Crawler & Conversational Agent

This is a **Proof of Concept (POC)** for a chatbot agent that **crawls a website, stores extracted data as vector embeddings, and enables conversational interactions** based on the retrieved information.

## 🌟 Use Cases

WebCrawlAI can be utilized in two primary ways:

1. **Website Interaction** – Build a platform that allows users to chat with any website in natural language.
2. **Support Chatbot** – Develop a support assistant using the crawled data to provide responses for customer service.

The project uses:

- **Cheerio** for web crawling and extracting website content
- **OpenAI** for generating responses based on the extracted data
- **ChromaDB** for storing vector embeddings for efficient retrieval

---

## 🚀 Getting Started

### 1️⃣ Clone the repository

```sh
git clone https://github.com/Prakhar788/WebCrawlAI.git
```

### 2️⃣ Install dependencies

```sh
npm install
```

### 3️⃣ Set up environment variables

Copy the `.env.example` file and rename it to `.env`:

```sh
cp .env.example .env
```

Then, update the `.env` file with your API keys and configuration.

### 4️⃣ Run the project

Start the application using Node.js:

```sh
node index.js
```

### 5️⃣ Using Docker (Optional)

This project includes a **Docker Compose** file for easy deployment.
To start the services using Docker, run:

```sh
docker-compose up --build -d
```

---

## 🔧 Technologies Used

- **Cheerio** – Web scraping & crawling
- **OpenAI API** – Answer generation
- **ChromaDB** – Vector embeddings storage
- **Docker Compose** – Containerized deployment

## 🤝 Contributing

If you have ideas for new features or improvements, feel free to contribute! 🚀

- Open an **issue** for discussions.
- To add a feature, submit a **pull request**.

## 📩 Need Help?

If you encounter any issues, feel free to open an issue in the repository or contact the maintainer.

This is a basic POC, and it can be extended to support more advanced features like multi-page crawling, better data filtering, and integration with different LLMs. 🚀

