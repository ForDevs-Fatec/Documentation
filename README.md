<br id="topo">
<h1 align = "center"> FATEC Profº Jessen Vidal, SJC - 5º Semestre DSM </h1>
<p align = "center">
<img src = "https://github.com/ForDevs-Fatec/Documentation/blob/main/logo.jpg" >


<p align = "center"> ForDevs é um Sistema classificador de Temas referente a atributos de produtos, serviços e processos operacionais a partir de comentários de clientes.
 

<br>

 
<!-- ÍNDICE -->
<details>
  <summary>Índice</summary>
  <ol>
    <li>
      <a href="#Sobre">Sobre o Projeto</a>
    </li>
    <li>
      <a href="#Entregas">Entregas</a>
    </li>
    <li>
      <a href="#Requisitos">Reguisitos</a>
    </li>
    <li>
      <a href="#User">User Stories</a>
    </li>
    <li>
      <a href="#Planejamento">Planejamento</a>
    </li>
     <li>
      <a href="#Tecnologias">Tecnologias</a>
    </li>
     <li>
      <a href="#Organização">Organização</a>
    </li>
    <li>
      <a href="#Equipe">Equipe</a>
    </li>
  </ol>
</details>

<span id="Sobre">

# 🎯 Sobre o projeto 
 

O projeto visa utilizar Inteligência Artificial em linguagem natural para criar classificações com maior assertividade e descobertas em relação a experiencia de compra de clientes de produtos, serviços e
processos operacionais associados através de comentários na forma de texto oriundos de múltiplos canais.

<p align="right"><a href="#topo">Voltar ao Topo</p> 

<span id="Entregas">

# ✅ Entregas 
  
#### Entregas serão realizadas nas seguintes datas:

**Sprint**  |**Status** |  **Entrega**         | **Link**
:---------: | :------:    | :-------:          | :-------:
01          | Em Desenvolvimento  | 24/09/2023  | <a href="">Sprint 1</a> |
02          | Inicio em 25/09  | 15/10/2023  | Sprint 2
03          | Inicio em 16/10 | 05/11/2023   | Sprint 3
04          | Inicio em 06/11| 26/11/2023   | Sprint 4 

 
 <p align="right"><a href="#topo">Voltar ao Topo</p> 
  
 <span id="Requisitos">

# 📌 Requisitos 

Inicialmente foram apresentados alguns requisitos funcionais e não funcionais e ao longo das Sprints houve o refinamento e o detalhamento dos requisitos. 

<img src = "https://github.com/ForDevs-Fatec/Documentation/blob/main/Backlog_Requisitos.jpg">
 
 <p align="right"><a href="#topo">Voltar ao Topo</p> 

<span id="User"> 
  
# 💡 User Stories 

<img src = "https://github.com/ForDevs-Fatec/Documentation/blob/main/Use.jpg">
 
<p align="right"><a href="#topo">Voltar ao Topo</p> 

<span id="Planejamento"> 
  
# 📝 Planejamento 

<img src = "https://github.com/ForDevs-Fatec/Documentation/blob/main/Sprints.jpg">

<p align="right"><a href="#topo">Voltar ao Topo</p> 


 <span id="Tecnologias">

# 📱 Tecnologias
  
As seguintes ferramentas, linguagens, bibliotecas e tecnologias foram usadas na construção do projeto até o momento:

![PostgreSQL](https://img.shields.io/badge/postgresql-%23007ACC.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![INSOMNIA](https://img.shields.io/badge/Insomnia-black?style=for-the-badge&logo=insomnia&logoColor=5849BE)
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)
![TYPEORM](https://img.shields.io/badge/Typeorm-black?style=for-the-badge&logo=typeorm&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-%23007ACC.svg?style=for-the-badge&logo=python&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)
![Visual Studio](https://img.shields.io/badge/Visual%20Studio-5C2D91.svg?style=for-the-badge&logo=visual-studio&logoColor=white)
 
<p align="right"><a href="#topo">Voltar ao Topo</p> 

<span id="Organização">

# 🗃️ Organização 

Os arquivos do projeto estão organizados em 3 repositórios, sendo: 
 

> ### 📁 <a href="https://github.com/ForDevs-Fatec/for-devs-web">/web</a>:
Contém o Front-end desenvolvido em React e TypeScript com construção em página única, em que o browser vai renderizar o core da aplicação apenas uma vez – todas as outras informações serão carregadas por demanda, de acordo com a necessidade do usuário, o que gera um melhor custo-benefício.

> ### 📁 <a href="https://github.com/ForDevs-Fatec/for-devs-back">/back_end</a>:
Contém o Back-end , implementado com uma arquitetura de microsserviços que consiste em uma coleção de serviços pequenos e autônomos. 
Cada serviço foi desenvolvido em torno de um conjunto de regras de negócio específico, e foi implementado de forma independente, o que possibilitará uma manutenção e evolução dos serviços de forma mais estáveis, permitindo uma maior flexibilidade de tecnologias, colocar alterações em produção.

> ### 📁 <a href="https://github.com/ForDevs-Fatec/for-devs-pln">/PLN</a>:
Contém a Pipeline com o Processamento de Linguagem Natural desenvolvido em Python.
 
> ### 📁 <a href="https://github.com/ForDevs-Fatec/Documentation">/Documentação</a>:
Documentação da API, onde inclui todos as informações necessários para rodar a aplicação em local host. Servidor foi desenvolvido em Node, usando router e express.

## :railway_track: Estrutura das Branchs

<div>
  
| Nome da Branch | Representação
| ---------------------: | :--------------------- | 
| Master | Principal branch, contém associadas a ela as versões de publicação para facilitar o acesso e a busca por versões mais antigas. |
| Develop | É uma cópia da branch principal contendo algumas funcionalidades que ainda não foram publicadas. Sendo assim, é a base para o desenvolvimento de novas features. |
| Feature | Branch que contém uma nova funcionalidade específica para a nossa aplicação. Nela temos a Promanage do nome feature/nome_do_recurso que será utilizada no nosso fluxo de trabalho. |
| Hotfix | Utilizada quando ocorre algum problema no ambiente de produção no qual a correção deve ser feita imediatamente. |
| Release | Unimos o que está pronto em nossa branch de desenvolvimento e “jogamos” para a branch principal. |

<p align="right"><a href="#topo">Voltar ao Topo</p> 
 
  
<span id="Equipe">

# 👥 Equipe
|                                                            | User                                                | Função |  |
| :--------------------------------------------------------- | :-----------------------------------------------    | :------- | :-------|
| ![](https://avatars.githubusercontent.com/u/79336346?s=30) |[Daniel Luciano](https://github.com/daniellsfilho)  | Scrum Master | [LinkedIn](https://www.linkedin.com/in/daniel-filho-3b6583209/) |
| ![](https://avatars.githubusercontent.com/u/78958795?s=30) | [Ana Carolina do Santos](https://github.com/annakks)|  Product Owner | [LinkedIn](https://www.linkedin.com/in/ana-santos-856436145/) |
| ![](https://avatars.githubusercontent.com/u/52466841?s=30) | [Bruno Pisciotta](https://github.com/bruno-pisciotta281)| Developer | [LinkedIn](https://www.linkedin.com/in/bruno-pisciotta-577216198/) |
| ![](https://avatars.githubusercontent.com/u/69692614?s=30) | [Vinicius Buarque](https://github.com/vbuarque)     | Developer | [LinkedIn](https://www.linkedin.com/in/vinicius-buarque-de-gusm%C3%A3o-catonho-9b11911a7/) |


<p align="right"><a href="#topo">Voltar ao Topo</p> 
