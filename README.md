# app-gym
Aplicativo para personal trainer



# BACKEND

**Aplicação Multi-Tenant**
O sistema é construído como uma aplicação multi-tenant, o que significa que cada usuário registrado na plataforma só pode visualizar informações relacionadas à sua própria empresa, como alunos, exercícios, treinos, rotinas, agendas, etc.

**Planos de Pagamento**
Planos disponíveis: Teste gratuito, Semestral, e Anual. O administrador do sistema é responsável por definir os planos de pagamento, que são armazenados na tabela PlanoGeral.

Plano de Teste: Cada novo usuário/personal registrado terá acesso a um plano de Teste Gratuito de 10 dias. Após o término do período de teste, os planos adquiridos serão associados ao usuário/personal na tabela planoUsuario.

  ![image](https://github.com/user-attachments/assets/9a6e5a9e-f4fe-4f2d-adc9-fe14015d6bec)

**Registro de Novos Usuários/Personais**
O registro de novos usuários/personais é simples e intuitivo.

   ![image](https://github.com/user-attachments/assets/d7bc3044-ffa9-4314-a409-1bb8bc0af350)

**Login Personal**
    ![image](https://github.com/user-attachments/assets/779bb256-a504-4e44-af99-174f07184fa4)
   
**Alteração de Senha (Conectado)**
Usuários podem alterar suas senhas diretamente na plataforma quando estão conectados.
  ![image](https://github.com/user-attachments/assets/0be6e491-6f84-4ab7-87ee-09d55dbb2a01)
  ![image](https://github.com/user-attachments/assets/1a0fac8d-1ee9-4461-926c-d9c29645af53)

**Recuperação de Senha (Quando Esquecida)**
Existe um fluxo dedicado para a recuperação de senha caso o usuário a tenha esquecido.
 ![image](https://github.com/user-attachments/assets/1636f363-cd27-4163-8533-64567865fa3f)
 ![image](https://github.com/user-attachments/assets/b396a89f-5d29-47a9-8972-92c3ac98abf2)

**###########################**

**Cadastro de Alunos**
Apenas personal trainers têm permissão para cadastrar novos alunos. Além disso, somente os personal trainers do respectivo tenant podem visualizar os alunos cadastrados.
   ![image](https://github.com/user-attachments/assets/db54d545-5245-476e-82af-3315bce90a08)
   
**Restrições de Cadastro:**
Não é permitido cadastrar o mesmo e-mail para mais de um aluno no mesmo tenant.
  ![image](https://github.com/user-attachments/assets/9be99211-285b-4e17-836e-29297dcc4826)

**Validação de Permissões:**
Alunos não têm acesso ao cadastro de novos alunos. Caso tentem acessar essa funcionalidade, uma validação impedirá a ação.
   ![image](https://github.com/user-attachments/assets/0752041c-6f91-4f1a-ae22-da07e166b2ff)

**Acesso Restrito:**
Após o cadastro, os alunos terão acesso à plataforma, mas com funcionalidades restritas.
   ![image](https://github.com/user-attachments/assets/d46652de-2123-4a66-a339-2d9fc56b7764)

**###########################**

**Cadastro de Exercícios**
Apenas personal trainers têm permissão para cadastrar novos exercícios. Similarmente, apenas os personal trainers do respectivo tenant podem visualizar os exercícios cadastrados.
    ![image](https://github.com/user-attachments/assets/a05c6c14-c9ed-4442-9159-8fa375615279)

**Formas de Execução:**
Um mesmo exercício pode ter várias formas de execução. Essas variações podem ser associadas ao exercício, facilitando a montagem dos treinos, onde o personal trainer pode selecionar a forma de execução mais adequada para cada aluno.

**Tentativa de cadastro com o login do aluno.**
    ![image](https://github.com/user-attachments/assets/81cf6f94-fdbd-4fa7-817d-91e3b2f6f33a)








  

