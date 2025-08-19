# README — WebApp de Gamificação

## 🚀 Visão Geral
Este projeto é um protótipo de **Web‑App de Gamificação para Turmas**, construído com **React + Vite + TypeScript + TailwindCSS**, e publicado via **GitHub Pages**.

URL de produção: [https://anacginocencio.github.io/gamifica](https://anacginocencio.github.io/gamifica)

---

## 📂 Estrutura do Projeto
```
gamifica/
├─ src/
│  ├─ App.tsx          # Entrada principal
│  ├─ GamificacaoApp.tsx # Componente principal de gamificação
│  ├─ main.tsx
│  ├─ index.css        # Tailwind CSS importado
├─ package.json        # Scripts e dependências
├─ vite.config.ts      # Configuração com base /gamifica/
├─ tailwind.config.js  # Configuração do Tailwind
├─ postcss.config.js   # Configuração do PostCSS
```

---

## ⚙️ Como rodar localmente

1. **Clonar o repositório:**
```bash
git clone https://github.com/anacginocencio/gamifica.git
cd gamifica
```

2. **Instalar dependências:**
```bash
npm install
```

3. **Rodar localmente:**
```bash
npm run dev
```
Abra no navegador: [http://localhost:5173](http://localhost:5173)

---

## ▶️ Como executar os scripts do `package.json`

No arquivo `package.json` estão definidos os scripts para controlar o projeto. Você deve rodá‑los usando `npm run <script>` dentro da pasta do projeto.

- `npm run dev` → Inicia o servidor local de desenvolvimento (http://localhost:5173)
- `npm run build` → Cria uma versão de produção na pasta `dist/`
- `npm run preview` → Abre a build de produção localmente para testar
- `npm run deploy` → Publica automaticamente a pasta `dist/` no GitHub Pages (branch `gh-pages`)

---

## 🌐 Deploy no GitHub Pages

### Primeiro Deploy
```bash
npm run build
npm run deploy
```
Esse comando publica a pasta `dist/` no branch `gh-pages`.

Acesse: [https://anacginocencio.github.io/gamifica](https://anacginocencio.github.io/gamifica)

### Atualizações Futuras
Sempre que fizer mudanças:
```bash
git add .
git commit -m "atualização"
git push origin main
npm run build && npm run deploy
```

---

## 📚 Tecnologias Utilizadas
- [React](https://react.dev/)
- [Vite](https://vitejs.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [TailwindCSS](https://tailwindcss.com/)
- [GitHub Pages](https://pages.github.com/)

---

✅ Agora você já sabe como executar cada script do `package.json` e publicar seu app!
# gamifica
aplicação para gamificação de turmas
