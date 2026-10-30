# Agente-Y

Projeto dedicado à criação e configuração de **sites e aplicativos para venda**.

## Estrutura

```
Agente-Y/
├── sites/          # Um diretório por site (ex.: sites/loja-exemplo/)
├── apps/           # Um diretório por aplicativo (ex.: apps/app-delivery/)
├── servidor/       # Configurações de servidor, deploy e backend compartilhado
├── briefings/      # Descrição de cada projeto (cliente, objetivo, cores, fontes...)
└── assets/         # Materiais enviados pelo cliente
    ├── logos/
    ├── fontes/
    ├── fotos/
    ├── videos/
    └── referencias/  # Vídeos/prints de sites de referência
```

## Fluxo de trabalho

1. **Briefing** — copiar `briefings/_modelo.md` para `briefings/<nome-do-projeto>.md` e preencher.
2. **Assets** — salvar logos, fontes, fotos e vídeos em `assets/<tipo>/<nome-do-projeto>/`.
3. **Desenvolvimento** — criar o site em `sites/<nome-do-projeto>/` ou o app em `apps/<nome-do-projeto>/`, cada um com seu próprio `README.md`.
4. **Servidor/Deploy** — configurações em `servidor/<nome-do-projeto>/`.
5. **Versionamento** — tudo commitado e enviado para este repositório no GitHub.

## Projetos

| Projeto | Tipo | Status | Pasta |
|---------|------|--------|-------|
| _(nenhum ainda)_ | | | |
