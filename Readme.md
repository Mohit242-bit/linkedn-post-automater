# 🚀 LinkedIn Post Automater

Automate your LinkedIn project updates—directly from your GitHub commits!  
No more manual copy-pasting: let AI and n8n handle your LinkedIn posts every time you push a new project.

---

## ✨ What is it?

**LinkedIn Post Automater** is a workflow built with [n8n](https://n8n.io) that listens for a special commit message (like `linked in post`) in your GitHub repository. When detected, it automatically generates a professional LinkedIn post using AI, pulls in your project details from the README, and can even attach screenshots and links—ready to share with your network.

---

## 🛠️ Features

- **Automated LinkedIn Post Generation:**  
  Instantly creates a LinkedIn-ready update when you push with a trigger commit message.
- **AI-Powered Summaries:**  
  Uses AI (OpenAI, Claude, etc.) to craft concise, engaging post captions.
- **README Integration:**  
  Pulls project description and highlights straight from your repo’s README file.
- **Customizable Workflow:**  
  Easily adapt for your own needs—add live demo links, badges, or more.
- **Screenshot Support:**  
  Attach project screenshots for extra visual appeal.
- **Flexible Posting:**  
  Use LinkedIn API for direct posting (if you have access), or send via email/Gmail as a fallback.

---

## 🖼️ Demo

![Workflow Screenshot](https://raw.githubusercontent.com/Mohit242-bit/linkedn-post-automater/main/Screenshots/showcase.png)


---

## 🚦 How It Works

1. **Push to GitHub:**  
   Make your final push with a commit message like `linked in post`.
2. **n8n Webhook:**  
   The workflow listens for GitHub webhooks and checks commit messages.
3. **AI Generation:**  
   If triggered, AI generates a LinkedIn post using your README and commit info.
4. **Post or Notify:**  
   The post is sent via LinkedIn API (if available) or emailed to you for manual posting.

---

## ⚡️ Getting Started

1. **Clone this repository:**
git clone https://github.com/Mohit242-bit/linkedn-post-automater.git

text

2. **Import the Workflow into n8n:**
- Open your n8n instance.
- Import the provided workflow file.

3. **Set Up GitHub Webhook:**
- In your GitHub repo, go to Settings > Webhooks > Add webhook.
- Set the payload URL to your n8n webhook URL.
- Choose “Just the push event.”

4. **Configure AI & Email/LinkedIn Nodes:**
- Add your API keys for OpenAI or another AI provider.
- Set up LinkedIn API credentials (if you have access) or configure Gmail for email notifications.

5. **Customize as Needed:**
- Adjust the commit trigger message if you want.
- Edit the AI prompt for your preferred post style.

---

## 💡 Why This Project?

Sharing your work is key to building your developer brand.  
This project removes the friction—so you can focus on building, while your network stays up to date automatically.

---

## 📝 Example Commit Message

git commit -am "linked in post"
git push

text

---

## 🔗 Links

- [n8n Documentation](https://docs.n8n.io/)
- [GitHub Webhooks Guide](https://docs.github.com/en/webhooks)
- [OpenAI API](https://platform.openai.com/docs/api-reference)

---

## 🙌 Contributing

Pull requests are welcome!  
If you have ideas for new features, improvements, or want to share how you’re using the workflow, open an issue or PR.

---


## 📣 Connect

Feel free to connect with me on [GitHub](https://github.com/Mohit242-bit) or share your feedback!

---
