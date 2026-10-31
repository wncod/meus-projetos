# Instruções para Claude Code

## Estilo de resposta
- **Direto e conciso** — sem introduções longas
- **Uma ação por vez** — executa, verifica, avisa
- **Se der erro 2x** — muda abordagem, não insiste
- **Português (PT-BR)** — sempre
- **Respostas rápidas** — foco no essencial, sem enrolação

## Modelo preferido por tipo de tarefa
- **Arquitetura/planejamento/complexo** → Opus
- **Código/debug/tasks rotina** → Sonnet
- **Formatação/limpeza/rápido** → Haiku

## Git/GitHub
- SSH para autenticação (padrão profissional)
- `gh` (GitHub CLI) como fallback no Windows
- Commits limpos, mensagens claras
- Branch `main` padrão

## Qualidade de código
- Estrutura profissional desde o início
- .gitignore apropriado
- README completo
- Licença (MIT) se público

---

*Configuração global em: `~/.claude/CLAUDE.md`*