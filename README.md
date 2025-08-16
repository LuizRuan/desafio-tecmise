TecMise — Dashboard de Gestão Escolar (Frontend)

O TecMise é um sistema moderno de gestão escolar, desenvolvido em Vue 3 + Nuxt 3, integrado a uma API RESTful em Go com PostgreSQL.
O frontend é responsivo, seguro e fácil de usar, oferecendo recursos de CRUD, autenticação e personalização de perfis.

✨ Funcionalidades

🔑 Login seguro por usuário

🧑‍🎓 Gestão de Estudantes (cadastro, edição, listagem, exclusão)

📚 Gerenciamento de Anos/Turmas (CRUD completo)

🖼️ Upload de avatar/foto com preview imediato

✅ Validação de dados (nome, CPF, e-mail etc.)

📱 Responsividade total (desktop, tablet e mobile)

🔒 Dados isolados por usuário (multicontas seguras)

🚀 Pronto para deploy em produção

🚀 Pré-requisitos

Node.js ^22.17.1

npm ^10.9.2

Nuxt CLI 3.27.0 (opcional, recomendado rodar via npm scripts)

⚠️ O backend em Go precisa estar rodando em http://localhost:8080 ou a URL configurada via .env.

⚡ Instalação Rápida
1. Clone o repositório
[git clone https://github.com/seuusuario/tecmise.git](https://github.com/LuizRuan/desafio-tecmise)
cd tecmise/frontend

2. Instale as dependências
npm install

3. Configure as variáveis de ambiente

Crie ou edite o arquivo .env na raiz do frontend:

NUXT_PUBLIC_API_URL=http://localhost:8080

4. Execute em modo desenvolvimento
npm run dev


👉 Acesse: http://localhost:3000

🛠️ Scripts principais

npm run dev → Inicia em modo desenvolvimento

npm run build → Gera a versão de produção

npm run preview → Roda localmente o build de produção

📁 Estrutura de Pastas
frontend/
├── components/        # Componentes Vue (modais, tabelas, inputs)
├── pages/             # Páginas Nuxt (login, dashboard, etc)
├── plugins/           # Plugins Nuxt opcionais
├── public/            # Arquivos estáticos (favicons, imagens)
├── nuxt.config.ts     # Configuração principal do Nuxt
├── package.json       # Dependências e scripts
└── ...

🌎 Variáveis de Ambiente
Variável	Descrição	Exemplo
NUXT_PUBLIC_API_URL	URL da API backend (Go)	http://localhost:8080
🐞 Troubleshooting

❌ Erro ao instalar dependências
→ Verifique se está usando Node 22+ e npm 10+.
→ Sempre use npm install (não use yarn).

🔗 Erro de CORS / API não responde
→ Confirme se o backend Go está rodando e configurado para aceitar o frontend.

⚠️ Problemas no build de produção
→ Certifique-se de definir corretamente as variáveis .env no ambiente de deploy (Vercel, Netlify, Render, etc).

💡 Dicas & Recomendações

Sempre iniciar o backend antes do frontend.

Para deploy em produção, configure as variáveis .env corretas.

Navegadores modernos oferecem a melhor experiência de uso.

👥 Contribuição & Contato

Contribuições são muito bem-vindas 🚀

Abra uma issue para reportar bugs ou sugerir melhorias.

Faça um pull request para contribuir diretamente.

Autor: Luiz Ruan 


📜 Licença

Este projeto está sob a licença MIT — veja LICENSE.
