<h1 align="center">Sistema de Gestão de Previdência</h1>
<h3 align="center">Este repositório contém os componentes do sistema de Gestão de Previdência, que permite gerenciar contribuintes, contribuições, benefícios e empréstimos para um regime próprio de previdência.</h3>

<h2 align="center"> Visão Geral </h2>

Um dos nossos clientes, que opera um regime próprio de previdência, nos solicitou um novo sistema para gerenciar algumas de suas operações. Este sistema é composto pelos seguintes serviços:

1. [**Gestão de Contribuintes**](https://github.com/Projeto-previdencia-privada/Gestao-Contribuintes)

2. [**Gestão de Contribuições**](https://github.com/Projeto-previdencia-privada/Gestao-Contribuicao)

3. [**Gestão de Benefícios**](https://github.com/Projeto-previdencia-privada/Gestao-Beneficios)

4. [**Gestão de Empréstimos**](https://github.com/Projeto-previdencia-privada/Gestao-Emprestimos)
   
5. [**Footer e Header padrão do projeto**](https://github.com/Projeto-previdencia-privada/Footer-Header-Padrao)

Cada serviço é independente, possui sua própria infraestrutura, e se comunica com os demais por meio de APIs.

Cada serviço possui um README.md específico com instruções detalhadas sobre como configurar e executar cada serviço.

<h2 align="center"> Serviços </h2>

<h3 align="center">1. Gestão de Contribuintes</h3>

- Permite o cadastro, alteração, listagem e desativação (lógica) de contribuintes.
- o sistema permite a geração de árvores genealógicas.

<h3 align="center">2. Gestão de Contribuicao</h3>
- Gerenciamento das categorias de contribuintes por meio da API.

- Valor Corrigido de contribuições referentes a meses ou anos anteriores, considerando o percentual do salário mínimo à época e o valor vigente no momento do registro

<h3 align="center">3. Gestão de Benefícios</h3>

- Inserção de novos benefícios e alteração do tempo de contribuição necessário
- Recebimento de solicitações de benefícios, cálculo do tempo de contribuição, e decisão sobre a concessão do benefício
- Cálculo do valor do benefício com base no percentual definido no cadastro do benefício

<h3 align="center">3. Gestão de Empréstimos</h3>


- Verifica se o somatório das parcelas existentes e a nova parcela ultrapassa 30% do valor do benefício, rejeitando o empréstimo se necessário
- Registro do empréstimo caso aprovado
- Serviço para obter o valor consignável


<h3 align="center">Linguagens e Ferramentas utilizadas no projeto:</h3>
<p align="center"> 
<a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a>
<a href="https://www.docker.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/> </a>
<a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> 
<a href="https://www.java.com" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a>
<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a>
<a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a>  
<a href="https://www.postgresql.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/>  </a> 
<a href="https://reactjs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/> </a> 
<a href="https://spring.io/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/springio/springio-icon.svg" alt="spring" width="40" height="40"/> </a> 
<a href="https://nodejs.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/>  </a>
<a href="https://www.nginx.com" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nginx/nginx-original.svg" alt="nginx" width="40" height="40"/>  </a>
<a href="https://vitejs.dev/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vite/vite-original.svg" alt="vite" width="40" height="40"/> </a>
</p>











