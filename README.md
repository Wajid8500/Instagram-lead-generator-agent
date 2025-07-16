# Instagram Lead Generator Agent 🚀

This is a no-code AI-powered lead scraper built using **n8n**, designed to extract profession + location based leads from **Instagram** without using Instagram’s API. It fetches public profile data like name, username, description, and followers directly into **Airtable**.

## 📌 Features
- Search Instagram accounts by profession and city (e.g., Dentist in Pune, Models in Mumbai)
- Collects public info: Name, Username, Profile URL, Description, Follower count
- Data stored directly into Airtable
- No Instagram API required
- Filter data into views: All, Posts, Reels

## 🛠 Tools Used
- [n8n](https://n8n.io/)
- [Apify Google Search Scraper](https://apify.com/)
- [Airtable](https://airtable.com/)
- ChatGPT for JSON to structured output conversion

## 📷 Screenshots
### Form Setup
<img width="680" height="687" alt="Form" src="https://github.com/user-attachments/assets/4ba57fa8-49b9-40f7-9696-a373fac9fd23" />


### Execution Example
<img width="1679" height="778" alt="Insta scrapper workflow" src="https://github.com/user-attachments/assets/d6eb9606-dbf2-4dcd-b8ce-552df08f7eec" />



### Airtable Output
<img width="1789" height="442" alt="image" src="https://github.com/user-attachments/assets/29777f76-6203-49f9-804f-e11d5743858d" />


## 🚀 How to Use
1. Import `instagram_lead_agent_n8n.json` into your n8n instance.
2. Set up the Apify Google Search Scraper actor.
3. Connect Airtable and configure fields: Name, Username, Instagram URL, Description, Followers.
4. Run the agent and start collecting leads based on profession + location.

## 🧠 Example Use Cases
- Freelancers looking for local business clients
- Marketing agencies finding niche-based leads
- Influencer outreach automation

## 📌 Notes
- Works without Instagram API
- Use descriptive search terms (e.g., "dentist", "fashion model")
- You can filter views in Airtable for Reels vs Posts


