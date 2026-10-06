## Hi there 👋

Welcome to **Gatana**. Gatana is an MCP gateway that offers turn-key support for skills, SSO, and more.

Teams connect their MCP servers, REST APIs (through OpenAPI) and serverless functions once. Every approved AI agent (Claude, ChatGPT, Codex, Cursor and others) then uses them under the user's own identity, with credentials, access control and audit logs handled in one place. Gatana Cloud runs in the EU; self-hosting uses the Helm chart below.

🌐 **Website:** [gatana.ai](https://www.gatana.ai/) · 📖 **Docs:** [docs.gatana.ai](https://docs.gatana.ai/) · 💬 **Discord:** [Join us](https://discord.gg/mrEkuSUBvg)

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
