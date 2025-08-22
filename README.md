# Reflora App

**Reflora App** é uma aplicação móvel desenvolvida com **React Native** que permite o monitoramento em tempo real de parâmetros ambientais e agrícolas. Integrada a sensores IoT, a aplicação coleta dados como umidade do solo, temperatura, pH, condutividade elétrica e níveis de nutrientes (nitrogênio, fósforo e potássio), fornecendo informações essenciais para a gestão eficiente de cultivos.

## Funcionalidades

- **Monitoramento em tempo real**: exibe dados atualizados dos sensores conectados.
- **Alertas personalizados**: notifica o usuário quando os parâmetros estão fora dos intervalos ideais.
- **Interface intuitiva**: design amigável para facilitar a navegação e interpretação dos dados.
- **Armazenamento local**: utiliza banco de dados local para armazenamento temporário de dados.

## Tecnologias Utilizadas

- **Frontend**: React Native
- **Backend**: Node.js com Express
- **Banco de Dados**: PostgreSQL
- **ORM**: Drizzle ORM
- **Lógica de Negócio**: Classificação fuzzy para avaliação dos parâmetros

## Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/murilpcarneiro/reflora-app.git
   cd reflora-app
2. Instale as dependências:
   ```bash
   npm install
3. Inicie o aplicativo:
   ```bash
   npx expo start
4. Siga as instruções no terminal para abrir o aplicativo em um emulador ou dispositivo físico.

## Contribuições
Contribuições são bem-vindas! Para relatar problemas ou sugerir melhorias, por favor, abra uma issue ou envie um pull request.
