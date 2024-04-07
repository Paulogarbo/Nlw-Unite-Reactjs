# Nlw Unite: Pass.in
Desenvolvida durante a Nlw Unite da <a href="https://www.rocketseat.com.br/" target="_blank">Rocketseat</a> a pass.in é uma ferramenta de gerenciamento de participantes de eventos.

## Funcionalidades
- Persistência de estados de URL
- Painel de controle para os organizadores
- Visualização de data de cadastro e check-in 
- Busca/Filtragem de usuários em tempo real do banco de dados

## Demonstração
![Demonstração](./Preview/Pass-in.gif)

## Tecnologias Utilizadas
- ReactJs
- TypeScript
- Tailwind

## Bibliotecas
- DayJs
- Lucide
- Tailwind-merge
- FakerJs (foi removida depois da ligação com o back-end)

## Como Usar

1. **Clone os Repositórios**:
   - Clone este repositório do frontend em sua máquina local:
     ```bash
     git clone https://github.com/paulogarbo/Nlw-Unite-Reactjs.git
     ```
   - Clone também o repositório do backend em outra pasta:
     ```bash
     git clone https://github.com/rocketseat-education/nlw-unite-nodejs.git
     ```

2. **Instale as Dependências**:
   - No diretório do frontend, instale as dependências usando o npm:
     ```bash
     cd Nlw-Unite-Reactjs
     npm install
     ```
   - Em seguida, vá para o diretório do backend e instale as dependências:
     ```bash
     cd ../nlw-unite-nodejs
     npm install
     ```

3. **Configure o Banco de Dados**:
   - Crie um arquivo `.env` no diretório do backend e adicione o seguinte código:
     ```bash
     DATABASE_URL = "file:./dev.db"
     ```

4. **Seeding do Banco de Dados**:
   - No terminal, execute o comando a seguir no diretório do backend para popular o banco de dados com dados de exemplo:
     ```bash
     npx prisma db seed
     ```

5. **Inicie os Servidores**:
   - Primeiro, inicie o servidor do backend:
     ```bash
     npm run dev
     ```
   - Em seguida, inicie o servidor do frontend:
     ```bash
     cd ../Nlw-Unite-Reactjs
     npm start
     ```

6. **Acesse a Aplicação**:
   - Abra seu navegador e acesse o link que ela irá gerar para usar a aplicação.

Siga esses passos para configurar e iniciar a aplicação localmente em sua máquina.

## Autor

Paulo Alex 

## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).
