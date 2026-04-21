# 🤖 N8N-Workflows

A curated collection of AI-powered N8N automation workflows focused on cybersecurity, threat intelligence, and market monitoring.

## 📁 Workflows

### 🛡️ Security & Threat Intelligence

| Workflow | Description |
|----------|-------------|
| **AI Powered - Phishing Analysis Agent** | Automated phishing email/URL analysis using AI to detect malicious indicators, extract IOCs, and generate risk scores |
| **AI Powered - SOC Agent** | Security Operations Center assistant that triages alerts, correlates events, and provides analyst-ready summaries |
| **AI Powered - Threat Feeds Generator** | Aggregates and processes threat intelligence feeds, normalizes IOCs, and pushes structured data to your SIEM or ticketing system |
| **AI Powered - Threat Hunter** | Proactive threat hunting workflow that queries logs and endpoints for known TTPs (Tactics, Techniques & Procedures) |

### 📈 Market Intelligence

| Workflow | Description |
|----------|-------------|
| **AI Powered - Stock Market News** | Monitors financial news sources, summarizes market-moving events, and delivers AI-curated briefings |

## 🚀 Getting Started

### Prerequisites

- [N8N](https://n8n.io/) (self-hosted or cloud) — v1.0+
- An AI provider API key (OpenAI, Anthropic, etc.)
- Relevant integrations depending on the workflow (e.g., VirusTotal, Slack, SIEM)

### Installation

1. **Clone or download** this repository.
2. In your N8N instance, go to **Workflows → Import**.
3. Upload the desired `.json` file.
4. Configure the **credentials** and **environment variables** required by the workflow.
5. Activate and test the workflow.

## ⚙️ Configuration

Each workflow may require its own set of credentials. Common ones include:

- `OPENAI_API_KEY` / `ANTHROPIC_API_KEY` — for AI model calls
- `VIRUSTOTAL_API_KEY` — for phishing/threat analysis
- Slack / email credentials — for alerting and notifications
- SIEM / ticketing system credentials — for SOC and threat feed workflows

Refer to the individual workflow nodes for the full list of required credentials.

## 🤝 Contributing

Contributions are welcome! To add a new workflow:

1. Fork this repository
2. Add your `.json` workflow file with a descriptive name following the `AI Powered - <Name>.json` convention
3. Update this README with a description of your workflow
4. Open a Pull Request

## 📄 License

This project is open source. See [LICENSE](LICENSE) for details.

---

> Built with [N8N](https://n8n.io/) • Powered by AI

---

**Suneel Baba**  
Security Engineer — Dream11
