# N8N Workflow Collection

A comprehensive collection of n8n workflows for various use cases and automation scenarios. This repository showcases practical implementations of workflow automation using n8n.

![N8N Workflow Collection](image.png)

## 🚀 About This Collection

I'm building **use case command workflows** - practical, ready-to-deploy n8n workflows that solve real-world problems. Each workflow is designed to be easily imported, configured, and used in your n8n instance.

**Happy to have contributions!** If you have workflow ideas, improvements, or want to add new use cases, feel free to contribute.

## 📁 Workflows Included

### 1. **Slack Notification Workflow** (`slackbot-on-form-n8n/`)
- Automated Slack notifications based on form submissions
- Time-based conditional logic (7-day window)
- Prevents notification spam from old submissions
- [View Details](slackbot-on-form-n8n/on-form/README.md)

### 2. **Hacker News Workflow** (`hacker-news-n8n/`)
- Automated Hacker News monitoring and processing
- Custom automation for HN content
- [View Details](hacker-news-n8n/README.md)

### 3. **Google Sheet Agent** (`google-sheet-agent-n8n/`)
- AI-powered agent for Google Sheets automation
- Multi-language support (including Hindi)
- Agent-based workflow automation
- [View Details](google-sheet-agent-n8n/README.md)

### 4. **Expense Tracker Agent** (`expense-tracker-agent-n8n/`)
- Intelligent expense tracking using AI
- Google Sheets integration
- OpenAI Chat Model + Memory + Calculator tools
- [View Details](expense-tracker-agent-n8n/README.md)

### 5. **RAG using Google Drive** (`rag-using-google-n8n/`)
- Retrieval-Augmented Generation system
- Google Drive document processing
- AI-powered document search and Q&A
- [View Details](rag-using-google-n8n/README.md)

## 🛠️ Getting Started

1. **Choose a workflow** from the collection above
2. **Import the JSON file** into your n8n instance
3. **Configure credentials** and settings as per the workflow's README
4. **Test and customize** for your specific needs

## 🔧 Prerequisites

- N8N instance (self-hosted or cloud)
- Relevant API credentials (Google, OpenAI, Slack, etc.)
- Basic understanding of n8n workflow concepts

## 🤝 Contributing

We welcome contributions! Here's how you can help:

- **Add new workflows** for common use cases
- **Improve existing workflows** with better error handling
- **Enhance documentation** with setup guides and examples
- **Report issues** or suggest improvements
- **Share workflow ideas** for future development

### Contribution Guidelines

1. Fork the repository
2. Create a new folder for your workflow
3. Include the workflow JSON, README, and any relevant images
4. Submit a pull request with a clear description

## 📊 Workflow Categories

- **Communication & Notifications** - Slack, email, messaging
- **Data Processing** - Google Sheets, databases, APIs
- **AI & Automation** - Agents, RAG systems, AI integrations
- **Content Management** - News monitoring, document processing
- **Business Automation** - Expense tracking, reporting

## 🌟 Featured Workflow: Slack Notification System

This workflow demonstrates time-based conditional logic for automated Slack notifications:

```
Form Submission → IF (7-day Check) → Slack Message
                        ↓
                   (If False)
                        ↓
                      End
```

**Key Features:**
- Prevents notification spam from old submissions
- Maintains clean and relevant communication
- Automated time-based filtering
- Customizable message formatting

## 📞 Support & Questions

- **Issues**: Use GitHub Issues for bug reports
- **Discussions**: Start a discussion for questions or ideas
- **Contributions**: Submit PRs for improvements

---

**Built with ❤️ using n8n - The most powerful workflow automation platform**

*Each workflow is tested and ready for production use. Happy automating!*