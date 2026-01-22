# AIDP-Project-
Building GPU-powered projects on AIDP

#  AIDP Chat - Decentralized GPU-Powered AI Chatbot

[![AIDP Network](https://img.shields.io/badge/Powered%20by-AIDP-purple)](https://aidp.store)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

> An intelligent AI chatbot powered by AIDP's decentralized GPU compute network. Experience fast, cost-effective AI inference distributed across global GPU nodes.

![AIDP Chat Demo](https://via.placeholder.com/800x400/6366f1/ffffff?text=AIDP+Chat+Interface)


##  Features

- **GPU-Accelerated AI** - Runs on AIDP's decentralized compute network
- **Globally Distributed** - Leverages GPU nodes worldwide for high availability
- **Real-time Responses** - Fast inference with live typing indicators
- **Compute Tracking** - Monitor GPU usage, response times, and performance
- **Modern UI** - Beautiful, responsive interface built with React
- **Privacy-Focused** - Decentralized architecture ensures data sovereignty
- **Mobile-Ready** - Works seamlessly on all devices


## 🎯 What is AIDP?

**AIDP** is a decentralized GPU compute network that powers AI, gaming, rendering, zero-knowledge proofs, and scientific workloads. Through staking, proofs, and decentralized routing, AIDP offers:

- High-performance compute
- Verifiable execution
- Cost-effective pricing
- Global accessibility

**Learn more:** [https://aidp.store](https://aidp.store)


## 🛠️ Tech Stack

- **Frontend:** React 18+ with Hooks
- **Styling:** Tailwind CSS
- **Icons:** Lucide React
- **AI Model:** LLaMA 2 / Mistral (configurable)
- **Compute Network:** AIDP GPU Marketplace
- **Deployment:** Vercel / Netlify ready


## 🚀 Quick Start

### Prerequisites

- Node.js 16+ and npm
- AIDP API credentials ([Get them here](https://aidp.store))

### Installation

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/aidp-chat.git
cd aidp-chat

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env
# Edit .env and add your AIDP API credentials

# Start development server
npm start
```

The app will open at `http://localhost:3000`


## ⚙️ Configuration

Create a `.env` file in the root directory:

```env
REACT_APP_AIDP_API_KEY=your_api_key_here
REACT_APP_AIDP_ENDPOINT=https://api.aidp.store/v1
REACT_APP_AI_MODEL=llama-2-7b
```

### Available AI Models

- `llama-2-7b` - Fast, efficient for chat
- `llama-2-13b` - More capable, slower
- `mistral-7b` - Great balance of speed/quality
- `gpt-j-6b` - Lightweight alternative

---

## 💡 How It Works

### AIDP GPU Compute Integration

```javascript
// Example API call to AIDP network
const response = await fetch(AIDP_ENDPOINT, {
  method: 'POST',
  headers: {
    'Authorization': `Bearer ${AIDP_API_KEY}`,
    'Content-Type': 'application/json'
  },
  body: JSON.stringify({
    model: 'llama-2-7b',
    prompt: userMessage,
    max_tokens: 256,
    temperature: 0.7,
    gpu_nodes: 'auto' // AIDP automatically routes to available GPUs
  })
});
```

### Architecture Flow

1. **User sends message** → Frontend captures input
2. **Request routed to AIDP** → Distributed GPU network receives task
3. **GPU inference** → AI model processes on available compute nodes
4. **Response streaming** → Results sent back in real-time
5. **Stats updated** → Compute usage tracked and displayed

---

## 📊 GPU Compute Metrics

The dashboard tracks:

- **Compute Used** - Total GPU-hours consumed
- **Responses Generated** - Number of AI inferences completed
- **Average Speed** - Mean response time in milliseconds
- **Cost Savings** - Comparison vs centralized providers

---

## 🎥 Demo Video

[▶️ Watch Demo Video](https://youtube.com/your-demo-link)

**Demo highlights:**
- Chat interface walkthrough
- Real-time GPU compute stats
- AIDP network integration
- Response quality demonstration


## 📸 Screenshots

### Main Chat Interface
![Chat Interface](https://via.placeholder.com/800x500/1e293b/ffffff?text=Chat+Interface)

### GPU Stats Dashboard
![GPU Stats](https://via.placeholder.com/800x300/6366f1/ffffff?text=GPU+Statistics)

---

## 🏆 AIDP Bounty Submission

This project is submitted for the **AIDP GPU Campaign** bounty.

### Submission Checklist
- ✅ Uses AIDP GPU compute network
- ✅ Public GitHub repository
- ✅ Working demo (live or video)
- ✅ Clear documentation
- ✅ AIDP Marketplace listing ready
- ✅ Social media presence

**Referrer:** [Mololuwa Victor Falomo ]


## 🔮 Future Roadmap

- [ ] Multi-language support
- [ ] Voice input/output
- [ ] Image generation capabilities
- [ ] Custom model fine-tuning
- [ ] Team collaboration features
- [ ] Mobile app (iOS/Android)
- [ ] Browser extension

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🔗 Links

- **Website:** [https://your-demo-site.vercel.app](https://your-demo-site.vercel.app)
- **AIDP Network:** [https://aidp.store](https://aidp.store)
- **Twitter/X:** [@molexyflo](https://twitter.com/molexyflo)
- **Telegram:** [Join Community](https://t.me/Aidpofficial)
- **Documentation:** [AIDP Docs](https://aidp.store)


## Acknowledgments

- **AIDP Team** for providing decentralized GPU infrastructure
- **Open-source AI community** for model development
- **Contributors** who helped improve this project


## 📧 Contact

For questions or support:
- Twitter: [@molexyflo](https://twitter.com/molexyflo)
- Email: your.email@example.com
- GitHub Issues: [Report bugs here](https://github.com/YOUR_USERNAME/aidp-chat/issues)

---

**Built with ❤️ using AIDP Decentralized GPU Compute**

*Empowering the next generation of AI applications through decentralized infrastructure.*
