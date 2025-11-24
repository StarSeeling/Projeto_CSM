# Projeto_CSM
Membro: Adriel Rocha Lourenço
Aprendendo:
Javascript
php
Python

Melhorando em:
HTML/CSS
Mysql

Site sobre contratação de serviços de manutenção de computadores. Na home ha os serviços oferecidos junto com uma descrição sobre mim. Incorpora um link para realizar um loguin para facilitar o gerenciamento das solicitações assim como determinar sua natureza. A barra de navegação joga o usuario diretamente pra sessão correspondente, contendo tambem botão para realizar login. Há dois tipos de login: o de visitante e o de administrador. A diferença é que o visitante pode criar o pedido e edita-lo, porem apenas o adm pode exclui-lo. Todas as contas criadas serão do tipo visitante havendo apenas uma com nivel de acesso adm

Ferramentas utilizadas:
Visual studios code
Hosting Infinityfree

1. Entidade Escolhida e Justificativa Para a implementação do CRUD, foi escolhida a entidade "Serviços". Como o projeto Starseeling trata de manutenção e configuração de computadores, a gestão do catálogo de serviços é fundamental. Coloquei duas opções base onde o administrador precisa ter autonomia para adicionar novos tipos de reparos, atualizar preços conforme o mercado e remover serviços descontinuados.

2. Tecnologias Utilizadas:
Frontend: HTML5 semântico e CSS3 (com ênfase em Flexbox para alinhamento e design responsivo).
Backend: Linguagem PHP (versão 8.0+) para lógica de controle e manipulação de sessões.
Banco de Dados: MySQL/MariaDB para persistência dos dados.
Segurança: Uso de Prepared Statements (mysqli->prepare) para prevenir injeção de SQL e validação de sessão para proteger páginas restritas.

3. Desafios Encontrados e Soluções
Ambiente de Desenvolvimento (Arch Linux): O desenvolvimento foi realizado em um ambiente minimalista rodando PHP no Visual Studios Code.
Obstáculos: tive dificuldades em aprender a linguagem php e me adaptar a como a linguagem funciona, as vezes em um parametro usa underscore e as vezes não o conhecimento em html e css ajudou um pouco, porem foi algo que tomou tempo.
Solução: A solução foi estudar mais em sites como W3schools e ver alguns videos na internet aliado ao uso de IA generativa, e claro, tentativa e erro.

*Lógica de Edição: Preencher o formulário com dados existentes foi desafiador. Resolvido ao buscar o ID via método GET e injetar os valores nos atributos value dos inputs HTML.

Contato: adrielrochalou@gmail.com
