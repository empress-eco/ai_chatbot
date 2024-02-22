<div align="center">
<img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" alt="Logo" width="80" height="80">
<h1 align="center">DoppioBot: Streamline Your Conversations</h1>
<p align="center">
Transform your chat experience with AI, right from your desk interface.
<br />
<a href="https://frappe.io/blog/engineering/introducing-doppiobot-template">Explore the Docs</a>
·
<a href="https://github.com/NagariaHussain/doppiobot/issues">Report Bug</a>
·
<a href="https://github.com/NagariaHussain/doppiobot/issues/new">Request Feature</a>
</p>
</div>

## About The Project

### 📖 Overview
DoppioBot is a powerful AI chatbot designed to enhance your chat interface. Whether you're a developer looking to integrate AI into your applications or a user seeking a more interactive chat experience, DoppioBot is your solution.

### 🌟 Key Features
- Seamless chat history management with Redis
- Formatting of markdown responses including tables and lists
- Code block responses are syntax-highlighted and have a click to copy button
- A sleek loading skeleton is shown while the message is being fetched
- The prompt can be submitted through mouse as well as keyboard (`Cmd + Enter`)

### 🛠 Built With
- [Python & JavaScript](https://frappeframework.com)
- [MariaDB](https://mariadb.org/)
- [Redis](https://redis.io/)
- [LangChain](https://python.langchain.com/en/latest/)
- [OpenAI API](https://openai.com/blog/openai-api)
- [ReactJS](https://reactjs.org)
- [ChakraUI](https://chakra-ui.com)

## Getting Started

### Prerequisites
You need to have bench installed. 

### Installation
Execute the following commands to install the DoppioBot app on your Frappe site:

```sh
bench get-app NagariaHussain/doppio_bot
bench --site <your-site> install-app doppio_bot
```

Add your OpenAI API key to the `site_config.json`:

```json
"openai_api_key": "sk-your-secret-api-key"
```

Navigate to your site, use the awesome bar for **Ask DoppioBot**, and enjoy!

## Usage
DoppioBot offers an engaging chat interface, powered by the LangChain Python package.

## Contributing
We love contributions! Here's how you can contribute:

- Fork the Project
- Create your Feature Branch (git checkout -b feature/AmazingFeature)
- Commit your Changes (git commit -m 'Add some AmazingFeature')
- Push to the Branch (git push origin feature/AmazingFeature)
- Open a Pull Request

## Acknowledgments
Thanks to [Nagaria Hussain](https://github.com/NagariaHussain) for creating this amazing tool.

<!-- MARKDOWN LINKS & IMAGES -->
