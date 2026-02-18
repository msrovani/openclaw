# 🦞 OpenClaw — Antigravity Fork

<p align="center">
    <picture>
        <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/openclaw/openclaw/main/docs/assets/openclaw-logo-text-dark.png">
        <img src="https://raw.githubusercontent.com/openclaw/openclaw/main/docs/assets/openclaw-logo-text.png" alt="OpenClaw" width="500">
    </picture>
</p>

<p align="center">
  <strong>EXFOLIATE! EXFOLIATE! — BEYOND LIMITS.</strong>
</p>

<p align="center">
  <a href="https://github.com/your-username/openclaw-antigravity/actions"><img src="https://img.shields.io/github/actions/workflow/status/openclaw/openclaw/ci.yml?branch=main&style=for-the-badge" alt="CI status"></a>
  <a href="https://github.com/your-username/openclaw-antigravity/releases"><img src="https://img.shields.io/github/v/release/openclaw/openclaw?include_prereleases&style=for-the-badge" alt="GitHub release"></a>
  <a href="https://discord.gg/clawd"><img src="https://img.shields.io/discord/1456350064065904867?label=Discord&logo=discord&logoColor=white&color=5865F2&style=for-the-badge" alt="Discord"></a>
</p>

---

## 🚀 Antigravity Kit: Funcionalidades Exclusivas

Este fork redefine o que é um assistente pessoal local, focando em segurança forense e eficiência extrema:

- **🧠 Gestão de Memória com Mem0**: Implementação de memória de longo prazo persistente (SQLite). O assistente evolui com você, mantendo contexto histórico entre sessões sem inflar o prompt.
- **🔍 Otimização de DB com `sqlite-vec`**: Busca semântica nativa e local. As memórias e documentos são recuperados por relevância vetorial, permitindo uma compreensão contextual profunda sem nuvem.
- **🛡️ Cadeia de Custódia de Evidências (Vault System)**: Armazenamento forense *append-only*. Perfeito para peritos e engenheiros que precisam de integridade absoluta (SHA-256) e logs de auditoria imutáveis.
- **🧹 Auto-Arquivamento de Lixo**: Motor de destilação automática. O sistema identifica e remove ruído do histórico de chat, movendo apenas o que importa para a memória estável.
- **🔋 Economia de Guerra para Tokens**: Algoritmos de poda agressiva e montagem de contexto baseada em orçamento (budget). Performance máxima com o menor consumo de recursos possível.

---

**OpenClaw** is a _personal AI assistant_ you run on your own devices.
It answers you on the channels you already use (WhatsApp, Telegram, Slack, Discord, Google Chat, Signal, iMessage, Microsoft Teams, WebChat), plus extension channels like BlueBubbles, Matrix, Zalo, and Zalo Personal. It can speak and listen on macOS/iOS/Android, and can render a live Canvas you control.

[Website](https://openclaw.ai) · [Docs](https://docs.openclaw.ai) · [Vision](VISION.md) · [DeepWiki](https://deepwiki.com/openclaw/openclaw) · [Getting Started](https://docs.openclaw.ai/start/getting-started) · [Discord](https://discord.gg/clawd)

## Instalação do Fork

Runtime: **Node ≥22**.

```bash
git clone https://github.com/your-username/openclaw-antigravity.git
cd openclaw-antigravity
pnpm install
pnpm build
openclaw onboard
```

## Arquitetura de Memória & Evidências

### Vault Local
As evidências são protegidas em `~/.openclaw/vault/` com controle rigoroso de acesso e hashing automático. Nenhuma evidência pode ser sobrescrita, garantindo a integridade da prova digital.

### Mem0 + sqlite-vec
A memória reside em `~/.openclaw/mem0.db`. O sistema de economia de tokens garante que, mesmo após meses de uso, o assistente continue respondendo instantaneamente, priorizando fatos estáveis e preferências do usuário.

---

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=openclaw/openclaw&type=date&legend=top-left)](https://www.star-history.com/#openclaw/openclaw&type=date&legend=top-left)

## Community

AI/vibe-coded PRs welcome! 🤖 Antigravity improvements are focused on local-first sovereignty.

Special thanks to the original OpenClaw team and [Peter Steinberger](https://github.com/steipete).
