🍳 FiChef – Fichas Técnicas de Receitas Inteligentes












🧁 Sobre o Projeto

FiChef é um aplicativo web (PWA) criado para simplificar o controle de fichas técnicas culinárias, eliminando a necessidade de planilhas complexas.
Com uma interface intuitiva e totalmente funcional offline (ideal para Chromebooks), o FiChef calcula automaticamente custos, markup, rendimento, preço sugerido e ainda permite criar preparos reutilizáveis que podem ser usados como ingredientes em outras receitas.

Projetado para padarias, confeitarias, cafés, cozinhas artesanais e produtores caseiros, o FiChef traz precisão, padronização e agilidade para o seu processo de produção.

✨ Destaques

📋 Criação e edição de fichas técnicas completas

🧂 Base de ingredientes com valor unitário e fator de perda

♻️ Preparos reutilizáveis (sub-receitas que viram ingredientes)

🧮 Cálculos automáticos:

Custo total

Custo por porção

Preço sugerido via markup

Margem

📤 Exportação para CSV

🖨️ Impressão/geração de PDF

📱 Interface responsiva e fácil de usar

📴 Funciona 100% offline

📦 PWA instalável no Chromebook e no navegador

🧩 Como funcionam os Preparos (Sub-Receitas)

Receitas como Massa Básica, Molho de Tomate ou Calda podem ser marcadas como Preparo, permitindo:

Serem reutilizadas em outras fichas

Cálculo proporcional ao rendimento

Controle de custo por unidade base (g/ml/un)

Escolha entre custo dinâmico ou congelado

Evitar erros manuais típicos de planilhas

Esse recurso permite montar receitas complexas com total rastreabilidade de custo.

🧱 Tecnologias Utilizadas

React.js

TailwindCSS + shadcn/ui (UI moderna e bonita)

Vite (build rápido)

LocalStorage / IndexedDB (armazenamento local)

PWA (funciona offline e pode ser instalado)

Lucide Icons

📂 Estrutura do Projeto
FiChef/
│
├── public/
│   ├── manifest.json
│   ├── icons/
│   │   ├── icon-192.png
│   │   └── icon-512.png
│   └── index.html
│
├── src/
│   ├── components/          # Componentes reutilizáveis
│   ├── pages/
│   │   ├── Home.tsx         # Tela inicial
│   │   ├── Ficha.tsx        # Ficha técnica
│   │   └── Ingredientes.tsx # Importação e edição da base
│   ├── utils/
│   │   └── formulas.ts      # Lógica de cálculo
│   ├── types/
│   │   └── ficha.ts         # Tipos e interfaces
│   ├── App.tsx
│   └── main.tsx
│
├── package.json
├── vite.config.ts
└── README.md

🚀 Rodando o Projeto
1️⃣ Clonar o repositório
git clone https://github.com/NeuberJone/FiChef.git
cd FiChef

2️⃣ Instalar dependências
npm install

3️⃣ Executar o ambiente de desenvolvimento
npm run dev


Acesse em: http://localhost:5173

4️⃣ Gerar build de produção
npm run build

5️⃣ Publicar (gratuito)

Netlify

GitHub Pages

Vercel

💾 Importação de Ingredientes

O FiChef permite importar uma planilha .xlsx com dados como:

Item | Categoria | Subcategoria | Unidade | Volume | Valor Unitário | %Perda | Fornecedor


Isso facilita atualizar preços e manter custos sempre corretos.

🧭 Roadmap
Versão	Funcionalidades
v1.0	CRUD de fichas, cálculos, CSV/PDF, PWA
v1.1	IndexedDB + backup/restore
v1.2	Layouts de impressão customizados
v1.3	Importação de planilha de ingredientes (.xlsx)
v1.4	Sincronização com Google Drive / Sheets
v2.0	Dashboard de custos, estoque e relatórios
👤 Autor

Desenvolvido por
Neuber Jone Avelar Queiroz
📧 neuberjqueiroz@gmail.com

🎨 behance.net/neuberjone

🧠 Licença

Distribuído sob a licença MIT.