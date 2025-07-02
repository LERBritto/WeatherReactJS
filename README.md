# WeatherReactJS

Aplicativo web de previsão do tempo desenvolvido em React com Vite.

🧩 Tecnologias usadas
Liste o stack:

markdown
Copiar
Editar
- **React** (via Vite)
- **Vite** — bundler rápido e moderno
- **ESLint** — linting para manter o código consistente
- (Opcional) **API pública de previsão meteorológica**
🚀 Como rodar localmente
bash
Copiar
Editar
# Clone o repositório
git clone https://github.com/LERBritto/WeatherReactJS.git
cd WeatherReactJS

# Instale dependências
npm install
# ou
yarn

# Execute em modo dev
npm run dev
# ou
yarn dev

# Build de produção
npm run build
# ou
yarn build
⚙️ Variáveis de ambiente
Explique as variáveis em .env, como uma VITE_WEATHER_API_KEY, e onde obter a chave da API (ex.: OpenWeatherMap).

🧑‍💻 Estrutura do projeto
Explique brevemente as pastas e arquivos principais:

bash
Copiar
Editar
/src
  ├─ App.jsx       # componente principal
  ├─ components/   # UI (input, cards)
  └─ services/     # chamada à API
public/ .env .gitignore package.json vite.config.js
✔️ Funcionalidades
⚡ Pesquisa por cidade

🌡️ Exibe dados atuais (temperatura, clima, umidade…)

📅 Previsão 5–7 dias (se implementado)

Tratamento de erros (cidade não encontrada)