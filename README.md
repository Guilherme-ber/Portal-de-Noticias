# 📰 Portal de Notícias

Este é um projeto colaborativo de um portal de notícias online. A proposta é criar uma plataforma moderna, responsiva e funcional onde usuários possam acessar conteúdos atualizados sobre diversos temas. Nosso foco é a cidade de Rio Pomba.

---

## 📌 Objetivos iniciais

- Criar um site de fácil navegação e leitura.
- Aplicar práticas de desenvolvimento ágil com Git e GitHub.
- Trabalhar com versionamento organizado (branches, PRs, revisões).
- Envolver time multidisciplinar (dev, design, financeiro).

---

## 👥 Equipe

- PO (Product Owner): Guilherme Bernardino Reis
- Devs: Andrei, Guilherme, Isaque, João, João Matheus, Plínio, Richard, Vinícius
- Designers: Andrei, Guilherme, Luan, Richard, Vinícius
- Financeiro: Andrei, Henrique, José Márcio

---

## 🚀 Primeiros passos para colaboradores

1. Aceite o convite para colaborar.
2. Clone o repositório:
   ```bash
   git clone https://github.com/SeuUsuario/portal-noticias.git
   cd portal-noticias
   ````

3. Crie uma branch para sua tarefa:

   ```bash
   git checkout -b nome-da-branch
   ```
4. Faça alterações, commit e push:

   ```bash
   git add .
   git commit -m "descrição da alteração"
   git push origin nome-da-branch
   ```
5. Abra um **Pull Request** no GitHub para revisão.

---

## ✅ Tecnologias previstas

* HTML, CSS, JavaScript
* Frameworks front-end (React)
* Integração com APIs de notícias
* Firebase, PHP
* Figma

---

## 📂 Estrutura do Projeto

### 🧱 Base Inicial
- `/src`: arquivos de código-fonte
- `/public`: recursos públicos (imagens, ícones, etc.)
- `README.md`: este documento

---

### 🧭 Planejamento de Estrutura

workspace/portal  
│  
├── public/                  # Arquivos públicos (ícones, imagens, favicon, etc.)  
│   ├── images/  
│   ├── icons/  
│   └── index.html  
│  
├── src/  
│   ├── assets/              # Fontes, imagens e recursos estáticos  
│   ├── components/          # Componentes reutilizáveis React  
│   ├── pages/               # Páginas da aplicação  
│   ├── services/            # APIs, Firebase, etc.  
│   ├── styles/              # Estilos  
│   ├── utils/               # Funções utilitárias  
│   ├── App.jsx              # Componente principal  
│   ├── index.js             # Ponto de entrada  
│   └── routes.jsx           # Configuração de rotas  
│  
├── .gitignore               # Arquivo para ignorar arquivos/pastas no Git (não é necessário se preocupar agora)  
└── README.md                # Este documento

---

## 🧩 Padrões de Código

* **Metodologia CSS**:
  Utilizar o padrão **BEM** (Block Element Modifier) para nomeação de classes.

* **Organização de pastas**:
  Estrutura inicial recomendada: `components/`, `pages/`, `assets/`, `services/`, `styles/`, `utils/`.

* **Padrão Mobile-First**:
  O layout deve ser construído primeiro para dispositivos móveis e adaptado para telas maiores.

* **Acessibilidade**:
  Uso de boas práticas como:

  * Contraste adequado de cores
  * Texto legível
  * Uso de `alt` em imagens
  * Navegação por teclado
  * Testes com ferramentas como WAVE

* **Boas práticas de código**:

  * HTML semântico
  * CSS modularizado e reaproveitável
  * Responsividade e clareza visual
  * Componentização no React
  * Um arquivo CSS para cada arquivo .jsx

---

## 📘 Padrão de Git (Commits e Branches)

- **Criar branch**:

  ```bash
  git branch nome-da-branch
  git checkout nome-da-branch
  git checkout -b nome-da-branch # para criar e mudar de uma vez
  ```

- **Commit**:

  ```bash
  git add .
  git commit -m "mensagem clara do que foi feito"
  ```

- **Push e pull**:

  ```bash
  git push origin nome-da-branch
  git pull
  ```

- **Outras boas práticas**:

  - `git log` — histórico  
  - `git diff` — comparação de alterações  
  - `git reset` — remover do stage  
  - `git merge` — mesclar branches  
  - `git branch -d nome` — deletar branch local  
  - `git remote add origin <url>` — adicionar remoto  
  - `git remote -v` — ver remotos configurados

---

## 🔌 Extensões recomendadas no VS Code e navegador

### 🧠 No VS Code:

- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint): Ajuda a manter o código limpo, identificando erros e padrões de má prática em JavaScript/React.

- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode): Formata automaticamente seu código, mantendo uma padronização visual (espaços, quebras de linha, etc.).

### 🌐 No navegador:

- [Responsive Viewer](https://chromewebstore.google.com/detail/responsive-viewer/inmopeiepgfljkpkidclfgbgbmfcennb?hl=pt-BR&utm_source=ext_sidebar): Simula visualizações de diferentes dispositivos ao mesmo tempo (celular, tablet, desktop), ideal para testar o layout responsivo.

- [Material Icons for GitHub](https://chromewebstore.google.com/detail/material-icons-for-github/bggfcpfjbdkhfhfmkjpbhnkhnpjjeomc?hl=pt-BR&utm_source=ext_sidebar): Adiciona ícones visuais aos repositórios no GitHub, facilitando a navegação e identificação de arquivos e pastas.

- [Retire.js](https://chromewebstore.google.com/detail/retirejs/djkbihbnjhkjdocoafobidefhephglfd): Detecta bibliotecas JavaScript desatualizadas ou vulneráveis no código de páginas web. Útil para análise e segurança durante o desenvolvimento.

---

## 🔗 Links úteis 
   * Códigos prontos: https://github.com/WebdevShefali/Web-Dev-Resources?tab=readme-ov-file#web-development-resources
---

> 🛠️ Este README está em construção e será atualizado conforme o projeto evoluir.
