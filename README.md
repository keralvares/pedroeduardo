Grupo: PEDRO HENRIQUE FERREIRA QUERALVARES, EDUARDO LUCAS BANDRAO GOMES DA SILVA
https://www.figma.com/design/7BDchTObrQP50Q5QxglR7P/Untitled?node-id=0-1&t=42tRkBn6Ez5DoRLT-1
API-própia
Documento de Requisitos - GAMERSHUB
1. Introdução
O GAMERSHUB é uma plataforma que permite aos usuários se cadastrarem, entrarem em suas contas e se inscreverem em diferentes torneios de jogos. Este documento descreve os requisitos funcionais e não funcionais do sistema.

2. Objetivos
O objetivo principal do GAMERSHUB é fornecer uma plataforma fácil de usar para que jogadores possam se inscrever em torneios, visualizar informações e acompanhar seu progresso em diferentes modalidades (solo, dupla e trio).

3. Requisitos Funcionais
3.1 Cadastro de Usuários
O sistema deve permitir que novos usuários se cadastrem fornecendo:
Nome de usuário
E-mail
Senha e confirmação de senha
O sistema deve verificar se o e-mail fornecido já está em uso e, em caso positivo, exibir uma mensagem de erro.
3.2 Login de Usuários
O sistema deve permitir que os usuários façam login utilizando:
E-mail ou nome de usuário
Senha
Caso o usuário esqueça sua senha, deve haver uma opção de recuperação via e-mail.
3.3 Inscrição em Torneios
O sistema deve listar os torneios disponíveis (solo, dupla, trio), com:
Data do torneio
Número de jogadores inscritos/total de vagas
O usuário deve poder se inscrever em torneios e receber uma confirmação.
3.4 Gerenciamento de Torneios
Administradores devem poder criar novos torneios com os seguintes dados:
Tipo do torneio (solo, dupla, trio)
Data
Número máximo de jogadores
Os administradores devem também poder editar ou excluir torneios existentes.
3.5 Edição de Perfil de Usuário
O sistema deve permitir que o usuário edite seu perfil, incluindo:
Nome de usuário
Senha
E-mail
3.6 Esquema de Inscrições
O sistema deve bloquear inscrições após o limite máximo de jogadores ser atingido.
Usuários podem cancelar sua inscrição, desde que seja feito com até 24 horas antes do evento.
4. Requisitos Não Funcionais
4.1 Desempenho
O tempo de resposta para login, cadastro e inscrição não deve exceder 2 segundos.
A página deve carregar completamente em até 3 segundos em uma conexão de 10 Mbps.
4.2 Segurança
Todas as senhas devem ser armazenadas utilizando criptografia.
As comunicações entre o cliente e o servidor devem ser realizadas utilizando HTTPS.
4.3 Usabilidade
A interface deve ser intuitiva e fácil de navegar, com botões de ação claramente identificados para inscrição em torneios, login e cadastro.
As informações sobre torneios devem ser visíveis na tela inicial para usuários logados.
4.4 Compatibilidade
O sistema deve ser compatível com os navegadores mais usados (Chrome, Firefox, Edge, Safari).
A aplicação deve ser responsiva, funcionando em dispositivos móveis e desktops.
5. Requisitos de Interface do Usuário
5.1 Página de Cadastro
Campos de entrada para:
E-mail
Nome de usuário
Senha e confirmação de senha
Botão "Criar Conta"
Link "Já tem conta? Entrar"
5.2 Página de Login
Campos de entrada para:
E-mail ou nome de usuário
Senha
Botão "Entrar"
Link "Esqueci minha senha" e "Criar conta"
5.4 Tela de Torneios Inscritos
A página de torneios deve exibir apenas os torneios nos quais o usuário está inscrito. As informações a serem mostradas incluem:

Tipo de torneio (solo, dupla, trio)
Data do torneio
Número de jogadores inscritos/total de vagas
Status do torneio (em andamento ou futuro)
Botão "Cancelar Inscrição" (caso aplicável)

5.3 Página de Torneios

Lista de torneios com:
Tipo de torneio (solo, dupla, trio)
Data do torneio
Número de jogadores inscritos/total
Botão de "Inscrever-se" para torneios com vagas disponíveis
