
# 📐 Conversor de Unidades Químicas

Este projeto é um **conversor de unidades químicas**, desenvolvido para ajudar estudantes e profissionais da área de química a realizar cálculos de conversão entre diferentes unidades. O sistema é dividido em dois componentes: um front-end em React e um back-end em NestJS.

## 🚀 Tecnologias Utilizadas

- **Back-end**: [NestJS](https://nestjs.com/)
- **Front-end**: [React](https://reactjs.org/)
- **Containerização**: [Docker](https://www.docker.com/)
- **Servidor Web**: Nginx

## 🛠️ Funcionalidades

- Conversão de diferentes unidades químicas, como mols, gramas, volume, entre outras.
- Interface intuitiva desenvolvida com React e estilizada com Bootstrap.
- API REST construída em NestJS para realizar os cálculos e retornar os resultados ao front-end.

## ⚙️ Pré-requisitos

Antes de começar, você precisará ter as seguintes ferramentas instaladas no seu computador:

- [Git](https://git-scm.com)
- [Node.js](https://nodejs.org/en/)
- [Docker](https://www.docker.com/get-started)

Além disso, será necessário ter um editor de código como [VSCode](https://code.visualstudio.com/).

## 🧑‍💻 Como Rodar o Projeto

### Passo 1: Clone o Repositório

Clone este repositório na sua máquina local:

\`\`\`bash
git clone https://github.com/FelipeAraujo01/conversorUnidades.git
\`\`\`

### Passo 2: Entre no Diretório do Projeto

Navegue até a pasta raiz do projeto:

\`\`\`bash
cd conversor_quimico
\`\`\`

### Passo 3: Suba os Containers com Docker

Com Docker instalado e configurado, rode o seguinte comando para construir e subir os contêineres:

\`\`\`bash
docker-compose up --build
\`\`\`

Isso irá iniciar tanto o front-end quanto o back-end em contêineres separados.

### Passo 4: Acesse a Aplicação

- **Front-end**: Acesse \`http://localhost\` no navegador para ver a interface do conversor.
- **Back-end**: O back-end estará rodando em \`http://localhost:3000\`.

### Passo 5: Interação com a API

Você pode testar a API diretamente acessando os endpoints através de um cliente HTTP, como o [Postman](https://www.postman.com/) ou cURL.

## 📂 Estrutura do Projeto

- \`api-conversor/\`: Código do back-end em NestJS.
- \`front_conversor/\`: Código do front-end em React.
- \`docker-compose.yml\`: Arquivo de configuração para orquestração dos contêineres.

## 🤝 Como Contribuir

1. Faça um _fork_ do projeto
2. Crie uma nova _branch_ para a sua funcionalidade: \`git checkout -b minha-funcionalidade\`
3. Faça o _commit_ das suas alterações: \`git commit -m 'Minha nova funcionalidade'\`
4. Faça o _push_ para a sua _branch_: \`git push origin minha-funcionalidade\`
5. Abra um _Pull Request_

---

## 📝 Licença

Distribuído sob a licença MIT. Veja \`LICENSE\` para mais informações.
