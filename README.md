# From Trends to Posts: My First Fully Automated LinkedIn Workflow 🚀

This project is an **n8n automation** that fetches trending topics, researches them, generates engaging content, and posts directly to **LinkedIn** and **Twitter** — completely hands-free.

---

## 📌 How It Works
1. **Fetch Trending Topics** – Uses Google Trends API to pull the most popular search queries.
2. **Extract High-Volume Keywords** – Filters to top keywords for higher engagement potential.
3. **Research with Perplexity AI** – Gathers fresh and relevant context on the topic.
4. **Generate Posts with AI** – Uses an AI model to craft LinkedIn and Twitter-friendly copy.
5. **Publish & Log** – Posts directly to LinkedIn and Twitter, and saves details to Google Sheets.

---

## ⚡ Setup Steps
*(Approx. 15–20 mins)*
1. Install and set up **n8n** on your local machine or server.
2. Connect the following API credentials in n8n:
   - **Google Trends API**
   - **Perplexity AI API**
   - **OpenAI / LLM API** (for post generation)
   - **LinkedIn API**
   - **Twitter API**
   - **Google Sheets API**
3. Import the provided n8n workflow JSON into your n8n instance.
4. Configure the API keys and credentials for each service.
5. Test the flow with sample keywords before enabling automation.

---

## 🛠 Tech Stack
- **n8n** – Workflow automation
- **Google Trends API** – Data source
- **Perplexity AI** – Topic research
- **Gemini / LLM** – Post content generation
- **LinkedIn API** – Publishing
- **Twitter API** – Publishing
- **Google Sheets API** – Logging

---

## 📸 Workflow Preview
<img width="1557" height="454" alt="image" src="https://github.com/user-attachments/assets/601de255-e2b9-43b7-a425-4ab05c28641a" />


---

## 💡 Improvements & Next Steps
- Add more dynamic post templates for variety.
- Integrate image generation for richer LinkedIn/Twitter posts.
- Include analytics tracking for engagement.

---

## 🤝 Contributing
Pull requests are welcome! If you have ideas to improve the workflow or add new features, feel free to fork and submit changes.

---

## 📜 License
This project is licensed under the MIT License.
