# BTA Labs — Contexto para Claude Code

## Projeto
Labs estáticos para os cursos Blue Team Army hospedados no GitHub Pages.
Repositório: bta-labs (monorepo)
URL base: https://blueteamarmy.github.io/bta-labs/

## Design System BTA
- Cores: --bg #060a12, --blue #1e90ff, --cyan #00e5ff, --green #00e676
- Fontes: Rajdhani (headings), Exo 2 (body), Share Tech Mono (terminal/mono)
- Referência visual: https://blueteamarmy.github.io/bta-lab-linux/

## Estrutura
/engines/   → motores reutilizáveis por módulo
/mod1-lab/  → Lab Módulo 1 (conteúdo existente do lab Linux)
/mod2-lab/ até /mod9-lab/ → labs a desenvolver

## Regras
- Tudo HTML/CSS/JS estático — sem dependências de servidor
- Dados dos labs em JSON local
- Cada motor em /engines/ deve ser reutilizável via parâmetros
