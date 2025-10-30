<h1 align="center"> ClassManager </h1>
<p align="center">
  <img src="Img/ImagemProjeto.png" width="500">
</p>

---

## 📚 Sumário

### [📌 Sobre o projeto](#sobre)
### [🧰 Tecnologias Utilizadas](#TecnologiasUtilizadas)
### [💻 Como utilizar o ClassManager](#ComoRodar)
### [📷 Imagens do sistema](#ImagensDoSistema)
### [📞 Contato e Créditos](#CreditosEContato)


<a id="sobre"></a>

## 📌 Sobre o projeto

### O ClassManager é um sistema de gestão acadêmica, desenvolvido como parte do projeto Framework II da faculdade. Ele permite cadastrar e gerenciar disciplinas, professores e aulas, oferecendo uma interface moderna e intuitiva para controle escolar.

### 🧩 O projeto segue a arquitetura Full Stack, com o back-end desenvolvido em Node.js (utilizando Express, Sequelize, JWT e Swagger) e o front-end em Next.js com React e TailwindCSS. O banco de dados utilizado é o MySQL, configurado via Docker Compose para facilitar a implantação e portabilidade do sistema.

### 💡 O objetivo principal foi aplicar conceitos avançados de desenvolvimento web, integração entre front e back, autenticação com JWT e documentação de API. Além disso, foi implementado um pipeline automatizado com GitHub Actions para publicação das imagens no Docker Hub.

###  A estrutura do projeto foi pensada para ser modular, organizada e escalável — com separação clara entre rotas, controladores, modelos e middlewares, garantindo facilidade de manutenção e entendimento do código.

<a id="TecnologiasUtilizadas"></a>

## 🧰 Tecnologias Utilizadas

### ⚙️ **Back-End**

<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white"/>  
<p>Ambiente de execução JavaScript responsável por toda a lógica do servidor e integração entre as partes do sistema.</p>

<img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white"/>  
<p>Framework web usado para criar as rotas da API, middlewares e gerenciar as requisições HTTP.</p>

<img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white"/>  
<p>Implementa autenticação baseada em tokens, garantindo segurança no acesso às rotas da API.</p>

<img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black"/>  
<p>Ferramenta de documentação que permite testar e visualizar as rotas da API de forma prática e interativa.</p>

---

### 🗄️ **Banco de Dados**

<img src="https://img.shields.io/badge/Sequelize-2E8B57?style=for-the-badge&logo=sequelize&logoColor=white"/>  
<p>ORM que facilita a comunicação entre o back-end e o banco de dados, simplificando a criação de tabelas e operações CRUD.</p>

<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>  
<p>Banco de dados relacional utilizado para armazenar todas as informações do sistema, como professores, disciplinas e aulas.</p>

---

### 🖥️ **Front-End**

<img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white"/>  
<p>Framework React que estrutura o front-end, trazendo desempenho, roteamento otimizado e renderização moderna.</p>

<img src="https://img.shields.io/badge/React.js-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>  
<p>Biblioteca JavaScript usada na construção de componentes reutilizáveis e responsivos para a interface do usuário.</p>

<img src="https://img.shields.io/badge/TailwindCSS-38B2AC?style=for-the-badge&logo=tailwindcss&logoColor=white"/>  
<p>Framework CSS que simplifica a estilização com classes utilitárias, garantindo um design limpo e responsivo.</p>

---

### ☁️ **Infraestrutura e DevOps**

<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>  
<p>Utilizado para containerizar o projeto, permitindo rodar o banco de dados, API e front-end de forma integrada e portátil.</p>

<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>  
<p>Ferramenta de automação CI/CD que realiza o build e publica as imagens do projeto automaticamente no Docker Hub.</p>


<a id="ComoRodar"></a>
## 💻 Como rodar o programa 

✅ 1. Baixe o arquivo docker-compose.yml e o arquivo de exemplo de variáveis .env.example neste repositório.

✅ 2. Renomeie o arquivo .env.example para .env
Preencha as variáveis conforme suas preferências.

✅ 3. Certifique-se de ter o Docker instalado na sua máquina.
<br>[Link para o site do docker](https://www.docker.com/products/docker-desktop/)

✅ 4. Na pasta onde baixou os dois arquivos (docker-compose.yml e .env.example), execute:
<br>docker compose up

✅ 5. Aguarde a inicialização dos containers. Após subir:
- Front-end: http://localhost:3000
- API com Swagger: http://localhost:3001/api-docs
- Painel MySQL (opcional): http://localhost:8081

✅ 6. Pronto para usar
Crie usuários, faça login e cadastre disciplinas, professores e aulas pela interface.

<a id="ImagensDoSistema"></a>

## 📷 Imagens do sistema

<table>
  <tr>
    <td align="center"><strong>início</strong></td>
    <td align="center"><strong>Login</strong></td>
  </tr>
  <tr>
    <td><img src="Img/Inicio.png" width="400"/></td>
    <td><img src="Img/Login.png" width="400"/></td>
  </tr>
  <tr>
    <td align="center"><strong>Cabeçalho Logado</strong></td>
    <td align="center"><strong>Cabeçalho Login</strong></td>
  </tr>
  <tr>
    <td><img src="Img/CabeçalhoLogado.png" width="400"/> <img src="Img/CabeçalhoLogadoMobile.png" width="400"/></td>
    <td><img src="Img/CabeçalhoLogin.png" width="400"/> <img src="Img/CabeçalhoLoginMobile.png" width="400"/></td>
  </tr>
  </tr>
    <tr>
    <td align="center"><strong>Rodapé</strong></td>
    <td align="center"><strong>CRUD</strong></td>
  </tr>
  <tr>
    <td><img src="Img/Rodapé.png" width="400"/></td>
    <td><img src="Img/CRUD.png" width="400"/></td>
  </tr>
  <tr>
    <td align="center"><strong>Criar</strong></td>
    <td align="center"><strong>Listar</strong></td>
  </tr>
  <tr>
    <td><img src="Img/Criar.png" width="400"/></td>
    <td><img src="Img/Listar.png" width="400"/></td>
  </tr>
  <tr>
    <td align="center"><strong>Deletar</strong></td>
    <td align="center"><strong>Atualizar</strong></td>
  </tr>
  <tr>
    <td><img src="Img/Excluir.png" width="400"/></td>
    <td><img src="Img/Atualizar.png" width="400"/></td>
  </tr>
</table>

<a id="CreditosEContato"></a>

## 📞 Créditos e Contato

<h3> Desenvolvido por <a href= https://rincon23.github.io/>Enzo Rincon</a></h3> 

<p>📍 Localização: São Paulo 
<p>💼 Áreas de interesse: Desenvolvimento Fullstack.
<p>📢 Aberto a oportunidades profissionais na área de desenvolvimento

---

### 📬 Como entrar em contato?

<p>Curtiu o projeto? Quer dar um feedback, trocar ideia sobre tecnologia ou até falar de vagas?</p>
<p>Tô sempre aberto a conversar! É só me chamar nos links aí embaixo 👇</p>

<table> 
    <tr>
        <td><strong>📧 E-mail:</strong></td> 
        <td><a href="mailto:enzorincon2003@gmail.com">enzorincon2003@gmail.com</a></td> 
    </tr>
    <tr> 
        <td><strong>💼 LinkedIn:</strong></td> 
        <td><a href="https://www.linkedin.com/in/enzorincon">linkedin.com/in/enzorincon</a></td> 
    </tr> 
    <tr> 
        <td><strong>📷 Instagram:</strong></td> 
        <td><a href="https://www.instagram.com/enzo.rincon">@enzo.rincon</a></td> 
    </tr> 
    <tr> 
        <td><strong>🌐 Portifólio:</strong></td> 
        <td><a href="https://rincon23.github.io/">https://rincon23.github.io/</a></td> 
    </tr> 

</table>

---

⭐ Obrigado por visitar este projeto! ⭐
