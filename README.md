# Planejamento de Testes - Gerenciador de Estoque Magnum TI  
## Versão: 1.0 
## Status do Projeto: ⚠️ Espera

## Tópicos
🔹 Descrição do projeto 

🔹 Funcionalidades

🔹 Distribuição

🔹 Pré-requisitos

🔹 Como rodar a aplicação

🔹 Testes realizados

🔹 Banco de Dados

🔹 Linguagens, dependências e libs utilizadas

🔹 Resolvendo problemas

🔹 Recursos inseridos

🔹 Desenvolvedores/Contribuintes

## Descrição do projeto
<p align="justify"> O Sistema de Gerenciamento de Estoque para Petshops é uma solução abrangente projetada para simplificar e aprimorar o controle eficiente do estoque em estabelecimentos voltados para o universo pet. Este sistema oferece uma plataforma intuitiva e funcional, desenvolvida para atender às necessidades específicas de lojas de produtos para animais, promovendo uma gestão eficaz dos produtos disponíveis.</p>
<p align="justify">Entre nossos principais recursos, destacamos o oontrole de produtos, já que é possível cadastrar e gerenciar facilmente os produtos disponíveis na loja, incluindo informações detalhadas, como nome, categoria, preço e quantidade em estoque, a atualização do estoque, possibilitando registrar entradas e saídas de produtos, mantendo sempre atualizadas as informações sobre a disponibilidade de itens na loja, e o envio de alertas de estoque baixo, alertando através do recebimento de notificações automáticas quando os níveis de estoque atingirem um patamar mínimo predefinido, evitando assim a falta de produtos essenciais.</p>

## Funcionalidades ⚙️
✔️ <b>Controle de Produtos:</b> cadastre novos produtos, especificando nome, categoria, preço e quantidade disponível ou atualize informações de produtos existentes, como preço e detalhes descritivos;

✔️ <b>Atualização de Estoque:</b> registre entradas e saídas de produtos no estoque, incluindo a quantidade recebida ou venda realizada, possibilitando a monitoração de alterações no estoque em tempo real;

✔️ <b>Alertas de Estoque Baixo:</b> configure alertas automáticos para serem notificados quando os níveis de estoque atingirem um limite pré-definido, para que seja feito o recebimento de alertas e notificações no painel administrativo do próprio software;

✔️ <b>Personalização de Relatórios:</b> personalize relatórios de acordo com as necessidades específicas da loja, filtrando dados por período;

✔️ <b>Segurança:</b> garanta a segurança dos dados sensíveis, atribuindo permissões de acesso para garantir que apenas usuários autorizados possam realizar alterações no sistema.

## Distribuição
Ainda não há definição de link para compartilhamento.

## Pré-requisitos ⚠️
<ul>
  <li>NPM (Node Package Manager);</li>
  <li>Node.js v8.0.0 ou superior;</li>
  <li>Banco de dados MySQL versão 8.0 ou superior;</li>
  <li>Java 11 ou superior;</li>
</ul>

## Como rodar a aplicação 
### 1- Clone o repositório:
   <code>git clone https://github.com/guimagarotti/planejamento-teste-magnumti.git</code>

### 2- Navegue até o Diretório do Projeto:
<p>Use o comando cd para entrar no diretório do projeto que foi clonado.</p>
    <code>cd planejamento-teste-magnumti</code>

### 3- Instale as Dependências:
<p>Execute o comando npm install para instalar as dependências do projeto listadas no arquivo package.json.</p>
    <code>npm install</code>
    
<p>Certifique-se também de que o Angular CLI (Command Line Interface) está instalado globalmente em seu sistema. Se não estiver instalado, você pode instalá-lo usando o seguinte comando:</p>
    <code>npm install -g @angular/cli</code>

### 4- Inicie o Servidor de Desenvolvimento:
<p>Execute o comando ng serve para iniciar o servidor de desenvolvimento. Este comando compila o aplicativo e inicia um servidor local. Por padrão, a aplicação estará disponível em <b>http://localhost:4200/</b>.</p>
    <code>ng serve</code>

### 5- Acesse a Aplicação:
<p>Abra seu navegador da web e vá para <b>http://localhost:4200/</b> para visualizar a aplicação Angular em execução.</p>

## Testes realizados (FALTA FAZER)
<p align="justify">Esta seção do README descreve os testes realizados durante o desenvolvimento do projeto. Os testes são uma parte crucial do ciclo de vida do software, garantindo que a aplicação atenda aos requisitos estabelecidos, funcione conforme esperado e mantenha a integridade das funcionalidades. Abaixo estão os principais aspectos que foram testados:</p>
<h3>⚡ <b>Funcionalidades Principais:</b></h3>
<p align="justify">Testes abrangentes foram conduzidos para as funcionalidades principais da aplicação. Isso inclui a verificação da correta execução de tarefas fundamentais, como o registro de produtos, monitoramento de estoque, alertas automáticos e geração de relatórios estatísticos.</p>

<ul>
  <li><b>Integração Front-End e Back-End:</b> Garantimos que as interações entre o front-end (desenvolvido com Angular, HTML, CSS, Bootstrap, JavaScript e TypeScript) e o back-end (implementado em Java, utilizando MySQL como banco de dados) ocorram de maneira suave e eficiente. Testes foram realizados para verificar a comunicação adequada entre as camadas front-end e back-end da aplicação;</li>
  <li><b>Experiência do Usuário:</b> Foi realizada uma avaliação minuciosa da experiência do usuário (UX), garantindo que a interface seja intuitiva, responsiva e forneça feedback adequado ao usuário. Testes de usabilidade foram conduzidos para identificar e corrigir possíveis pontos de confusão ou dificuldades de navegação;</li>
  <li><b>Segurança:</b> Testes de segurança foram implementados para identificar e corrigir possíveis vulnerabilidades. Isso incluiu a validação adequada de entrada de dados, prevenção contra injeção de SQL e garantia de que as práticas de segurança recomendadas fossem seguidas em todas as partes da aplicação;</li>
  <li><b>Compatibilidade entre Navegadores:</b> Verificamos a compatibilidade da aplicação em diferentes navegadores web para garantir uma experiência consistente para todos os usuários. Testes foram realizados em navegadores populares, como Google Chrome, Mozilla Firefox, Microsoft Edge e Safari. </li>
</ul>

## Banco de Dados 🗂️
Nossa base de dados se resume inicialmente a um arquivo JSON, responsável por armazenar as informações referentes à base de dados de produtos pertencentes ao estoque e níveis de usuário registrados.

## Linguagens, dependencias e libs utilizadas 📚
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/-Bootstrap-0D1117?style=for-the-badge&logo=bootstrap&labelColor=0D1117)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![Java](https://img.shields.io/badge/Java-000?style=for-the-badge&logo=java)
![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-000?style=for-the-badge&logo=windows&logoColor=2CA5E0)
[![GitHub](https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/SEUUSERNAME)

## Resolvendo Problemas
<p>Alguns problemas gerados durante o desenvolvimento do projeto, e o modo pelo qual como foram resolvidos definitivamente:</p>

⚠️ <b>Integração com o Banco de Dados:</b>
<ul>
  <li><b>Problema:</b> dificuldades na configuração e integração com o banco de dados.</li>
  <li><b>Solução:</b> revisão da documentação do banco de dados, verificação das configurações de conexão e uso de ferramentas de diagnóstico para identificar e corrigir erros de conexão.</li>
</ul>

⚠️ <b>Conflitos de Dependências:</b>
<ul>
  <li><b>Problema:</b> conflitos entre diferentes versões de bibliotecas e dependências.</li>
  <li><b>Solução:</b> atualização para versões compatíveis das bibliotecas, revisão da documentação das dependências para garantir compatibilidade e uso de ferramentas de gerenciamento de dependências, como o npm.</li>
</ul>

⚠️ <b>Colaboração na Equipe:</b>
<ul>
  <li><b>Problema:</b> Dificuldades de colaboração entre membros da equipe.</li>
  <li><b>Solução:</b> Implementação de boas práticas de controle de versão (Git), uso de plataformas de colaboração como GitHub, e comunicação efetiva entre os membros da equipe.</li>
</ul>

## Recursos inseridos 🧰 (FALTA IMAGENS)
<p>Tarefas/funcionalidades que ainda precisam ser implementadas na aplicação:</p>

📝 <b>Autorização e Controle de Acesso:</b> adicionar diferentes níveis de permissões para usuários, como administradores e funcionários, e restrinjri o acesso a determinadas funcionalidades com base nessas permissões;

📝 <b>Histórico/Log de Alterações no Estoque:</b> registrar um histórico de todas as alterações no estoque, incluindo quem fez a alteração e quando;

📝 <b>Aprimoramento da Interface do Usuário (UI) e Experiência do Usuário (UX):</b> trabalhar na melhoria da aparência e usabilidade da interface do usuário para tornar a experiência do usuário mais agradável e eficiente.

📝 <b>Documentação Detalhada:</b> elaborar documentação abrangente que explique a estrutura do código, a arquitetura do sistema, os processos de instalação e configuração, além de fornecer guias para os usuários.

## Desenvolvedores/Contribuintes:
<p>O time de desenvolvedores do projeto é composto por:</p>
<ul>
  <li>Antônio Tadeu Diniz Reche;</li>
  <li>Guilherme Cambi Magarotti;</li>
  <li>João Gabriel Garcia Lourenço;</li>
  <li>Marcus Vinicius Takeyasu de Jesus;</li>
  <li>Rodrigo Antônio de Oliveira Lopes.</li>
</ul>

## Licença
<p>Este projeto é licenciado sob a Licença MIT, permitindo o uso, modificação e distribuição do código, sujeito às condições estabelecidas na licença.</p>

## Copyright ©️ 2023 - Planejamento de Testes - Gerenciador de Estoque Magnum TI
