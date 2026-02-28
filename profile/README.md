## Hi there 👋

Welcome to **Gatana** — an agentic connectivity platform.

Gatana lets individuals and organizations centralize, manage and secure their agentic connectivity — from MCP servers, AI sandboxes, credentials and authorization to hosted tools and federated identity.

🌐 **Website:** [gatana.ai](https://www.gatana.ai/) · 📖 **Docs:** [docs.gatana.ai](https://docs.gatana.ai/) · 💬 **Discord:** [Join us](https://discord.gg/6TvjvmSP)

---

| Language | Repo | Description |
|---|---|---|
| TypeScript/JavaScript | https://github.com/gatana-ai/gatana-js | SDK & CLI |
| Python | https://github.com/gatana-ai/gatana-python | SDK & LangChain Sandbox Backend |

---

### Quick Start

**CLI**
```bash
npm install -g gatana
gatana config login my-org
gatana get servers
```

**JavaScript / TypeScript**
```bash
npm install gatana-sdk
```
```ts
import { Gatana } from 'gatana-sdk';
const client = new Gatana();
const servers = await client.api.getMcpServers();
```

**Python**
```bash
pip install gatana-langchain
```
```python
import gatana_langchain
print(gatana_langchain.__version__)
```

---

### License

All repositories are licensed under the [MIT License](https://opensource.org/licenses/MIT).
