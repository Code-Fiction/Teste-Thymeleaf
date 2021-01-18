Teste para Desenvolvedor Back-end Java - Thymeleaf

Olá ! Bolamos esse teste pra entender melhor como você aborda o problema proposto, e como você gosta de codificar. Tentamos aproximar o máximo possível da nossa realidade, utilizando tecnologias que usamos e que facilmente podem ser encontrados tutoriais na internet. Caso não consiga ou queira fazer algum passo, não tem problema. Não vamos te desqualificar por isso. Nesse caso você pode comentar sobre o ponto e o porquê não o fez. Esperamos que goste!

Seguem as tarefas. As tarefas consideradas bônus, caso não tenha tempo ou prefira não fazer, por favor comentar como faria ou como seria a arquitetura técnica:

Criar API para USERS. Deve permitir essas funções: criar/editar/deletar/listar users, fazer login, logout. Deve ter função de alterar senha, e enviar link de ativação ao criar. Utilizar Spring BOOT.;
Deve ter internacionalização, suportando 3 linguagens (inglês, português e espanhol). Deve ter um campo “Language” no user que escolhe a linguagem. Baseado na linguagem que está salvo, enviar o email de ativação de link e o de esqueci minha senha. De preferência usar o Thymeleaf pra isso;
DB pode ser a vontade (sugestão h2, postgres ou mongo);
Adicionar swagger, devemos poder fazer todo o flow pelo swagger ( login, CRUD da task, logout). Dica: documentar todos os campos;
Não esquecer dos unit tests;
Entregar o link do repositório em modo privado (preferência gitlab) com readme.MD com instruções de como rodar localmente e resumo técnico;
Escrever o Readme.md Instruções do flow de login e de como rodar o app;
Bônus: Criar dockerfile e docker-compose.yaml pra fazer o deploy local como container do docker; Bônus: Deploy em algum cloud provider (preferência AWS, pode ser no EC2 mesmo, ou Azure ou Heroku);
