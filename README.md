# app-gym
Aplicativo para personal trainer



# BACKEND

- **Aplicação multi tenant**, ou seja, todo usuário que efetuar o registro na plataforma irá visualizar apenas as informações referentes a sua empresa, como alunos, exercicios, treinos, rotinas, agendas etc.
  
- **Planos de pagamento**, Teste gratis, Semestral, Anual.
  O administrador do sistema irá definir os planos de pagamento que ficarão salvos na tabela **PlanoGeral**

**###########################**

  Cada novo registro, o **usuário/personal** terá 10 dias de uso no plano Teste gratis. Os planos adquiridos pelos usuários/personal ficarão atrelados na tabela **planoUsuario**
  ![image](https://github.com/user-attachments/assets/9a6e5a9e-f4fe-4f2d-adc9-fe14015d6bec)

- **Registro de novos usuários/personal**
   ![image](https://github.com/user-attachments/assets/d7bc3044-ffa9-4314-a409-1bb8bc0af350)

-  **Login Personal**
    ![image](https://github.com/user-attachments/assets/779bb256-a504-4e44-af99-174f07184fa4)
   
-  **Alterar senha quando estiver conectado na plataforma**
  ![image](https://github.com/user-attachments/assets/0be6e491-6f84-4ab7-87ee-09d55dbb2a01)
  ![image](https://github.com/user-attachments/assets/1a0fac8d-1ee9-4461-926c-d9c29645af53)

- **Alterar a senha quando não lembra-la**
 ![image](https://github.com/user-attachments/assets/1636f363-cd27-4163-8533-64567865fa3f)
 ![image](https://github.com/user-attachments/assets/b396a89f-5d29-47a9-8972-92c3ac98abf2)

**###########################**

 - **Cadastro de alunos** Apenas o personal conseguirá efetuar o cadastro dos alunos, e apenas os personais do respectivo tenant conseguirão visualizar os alunos cadastrados.
   ![image](https://github.com/user-attachments/assets/db54d545-5245-476e-82af-3315bce90a08)
   
    Não será possivel cadastrar o mesmo e-mail/aluno no mesmo tenant
  ![image](https://github.com/user-attachments/assets/9be99211-285b-4e17-836e-29297dcc4826)

    O aluno não terá acesso ao cadastro de alunos, porém existe uma valição impedindo esta ação.
   ![image](https://github.com/user-attachments/assets/0752041c-6f91-4f1a-ae22-da07e166b2ff)

   Finalizado o cadastro, o alumo também terá acesso ha plataforma, porém com restrições de funcionalidades.
   ![image](https://github.com/user-attachments/assets/d46652de-2123-4a66-a339-2d9fc56b7764)









  

