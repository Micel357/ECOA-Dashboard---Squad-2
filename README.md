# ECOA Dashboard — Squad 2

Interface React para visualização e gestão de indicadores ESG (ambientais, sociais e de governança).

## Estrutura

```text
.
├── src/
│   ├── assets/          # Imagens e estilos importados pelo React
│   ├── componentes/     # Componentes reutilizáveis
│   ├── screens/         # Telas por funcionalidade
│   ├── App.jsx          # Rotas e composição da interface
│   └── main.jsx         # Entrada do React
├── public/              # Arquivos estáticos servidos por URL
├── assets/              # Recursos originais preservados
├── index.html
├── package.json
├── package-lock.json
└── vite.config.js
```

O projeto usa React, React Router e Vite. Os arquivos de configuração e dependências ficam na raiz conforme as convenções do Node.js e do Vite.

## Executar

```bash
npm ci
npm run dev
```

Para gerar a versão de produção: `npm run build`. Para executar o lint: `npm run lint`.

Este repositório contém o frontend. Não há um servidor backend próprio na árvore atual.
