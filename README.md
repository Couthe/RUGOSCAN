
# RugoScan 🌊📊

O **RugoScan** é uma aplicação web desenvolvida com  [React](https://react.dev/), voltada para a leitura, visualização e análise de arquivos `.INP` do EPANET diretamente no navegador. A ferramenta permite interpretar parâmetros hidráulicos, como diâmetro, comprimento, rugosidade e consumo, facilitando o trabalho técnico em campo ou em escritório.

---

## 🚀 Como rodar o projeto localmente

### 1. Clone o repositório

```bash
git clone https://github.com/Couthe/rugoscan.git
cd rugoscan
```

### 2. Instale as dependências

Para baixar a pasta `node_modules` e todas as dependências listadas no `package.json`, execute:

```bash
npm install
```

> **⚠️ Importante**: Certifique-se de ter o [Node.js](https://nodejs.org/) instalado (versão recomendada: 18.x ou superior).

### 3. Inicie o servidor de desenvolvimento

```bash
npm run dev
```

O Vite abrirá o projeto no navegador, geralmente no endereço:

```
http://localhost:5173
```

---

## 🧱 Tecnologias principais

- [Vite](https://vitejs.dev/)
- [React 18](https://reactjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [EPANET-JS](https://github.com/modelcreate/epanet-js)
- [jsPDF](https://github.com/parallax/jsPDF)
- [Recharts](https://recharts.org/)
- [MUI](https://mui.com/)

---

## 📁 Estrutura do projeto

```bash
├── public/               # Arquivos estáticos
├── src/
│   ├── features/         # Funcionalidades do app (ex: Parser, Relatórios)
│   ├── shared/           # Componentes reutilizáveis, helpers, estilos
│   ├── routes/           # Sistema de rotas
│   ├── App.jsx
│   └── main.jsx
├── package.json
└── vite.config.js
```

---

## 🛠️ Scripts úteis

- `npm run dev` — Inicia o servidor local
- `npm run build` — Gera a versão de produção
- `npm run preview` — Visualiza o build localmente

