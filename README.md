# creative-specialist

Plugin para [Claude Code](https://claude.com/claude-code) que reúne, em um só lugar, as skills de design mais usadas do ecossistema: front-end, design system, identidade visual, UI/UX e acessibilidade.

**38 skills · 7 agentes · 4 comandos**

## Instalação

```bash
/plugin marketplace add ThiagoNascBarros/creative-specialist
/plugin install creative-specialist@creative-specialist
```

As skills ficam disponíveis com o prefixo `creative-specialist:` (ex.: `/creative-specialist:impeccable`).

## Conteúdo

| Origem | Skills / agentes / comandos | Licença |
|---|---|---|
| [anthropics/skills](https://github.com/anthropics/skills) | `frontend-design`, `theme-factory`, `canvas-design` | Apache-2.0 |
| [vercel-labs/agent-skills](https://github.com/vercel-labs/agent-skills) | `web-design-guidelines`, `composition-patterns`, `react-best-practices`, `react-view-transitions` | MIT |
| [leonxlnx/taste-skill](https://github.com/leonxlnx/taste-skill) | `taste-skill`, `soft-skill`, `minimalist-skill`, `brutalist-skill`, `stitch-skill`, `gpt-tasteskill`, `redesign-skill`, `brandkit`, `image-to-code-skill`, `imagegen-frontend-web`, `imagegen-frontend-mobile`, `output-skill` | MIT |
| [pbakaus/impeccable](https://github.com/pbakaus/impeccable) | `impeccable` + 4 agentes `impeccable-*` | Apache-2.0 |
| [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | `ui-ux-pro-max`, `design-system`, `design`, `brand`, `ui-styling`, `banner-design`, `slides` | MIT |
| [shadcn-ui/ui](https://github.com/shadcn-ui/ui) | `shadcn` | MIT |
| [arvindrk/extract-design-system](https://github.com/arvindrk/extract-design-system) | `extract-design-system` | MIT |
| [wshobson/agents](https://github.com/wshobson/agents) (plugin `ui-design`) | 9 skills, agentes `ui-designer`, `design-system-architect`, `accessibility-expert`, comandos `/design-review`, `/design-system-setup`, `/create-component`, `/accessibility-audit` | MIT |

Os commits de origem de cada fonte estão em [`third-party-licenses/SOURCES.txt`](third-party-licenses/SOURCES.txt), e as licenças originais em [`third-party-licenses/`](third-party-licenses/).

## Modificações em relação às fontes

- Caminhos de scripts do UI UX Pro Max ajustados de `.claude/skills/…` para `${CLAUDE_PLUGIN_ROOT}/skills/…`.
- Hooks do Impeccable **não incluídos** (baixam e executam um binário a cada sessão/edição). A skill funciona sob demanda.
- Omitidos: `taste-skill-v1` (obsoleta) e `brand-guidelines` da Anthropic (específica da marca Anthropic).

## Créditos

Todo o conteúdo pertence aos respectivos autores, redistribuído sob suas licenças. Este repositório apenas agrega e empacota.
