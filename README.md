
Aprendendo sobre BDD

![Gif_Digitando](https://github.com/ElianeOliveiradeJesus/BDD/blob/main/Gif_Digitando.gif)

# O que é BDD ?
BDD(Behavior Driven Development)
Desenvolvimento guiado por comportamento . 

O BDD é realizado antes de codificar o software ou  as funcionalidades. 
Enriquece o processo , documentação atualizada e  fácil entendimento. 
A técnica colabora com a qualidade no macro do desenvolvimento do software. 

Na estória do usuário perfeita deve ter:
1)  Ator = Quem vai usar a funcionalidade ?
2) Serviço ou produto = O que será desenvolvido ?
3) Motivo de negócio = Qual o valor agregado que a aplicação terá ?
 
Exemplos de como aplicar o BDD. 

 Cadastro com sucesso. 

   Dado que acesso a página de cadastro .
   Quando submeto o meu cadastro com login , senha e confirmação de senha. 
   Então devo ser redirecionado para área logada . 

Email não informado.

     Dado que acesso a página de cadastro .
     Quando submeto o meu cadastro sem email.
     Então devo ver "Oops!  Informe seu email".

 Senha não informada  
    Dado que acesso a página de cadastro 
    Quando submeto o meu cadastro sem a senha
    Então devo ver "Oops! Informe sua senha".

 Senha divergente  
   Dado que acesso a página de cadastro 
   Quando submeto o meu cadastro com as senhas divergentes 
   Então devo ver "Oops! Senhas não são iguais ". 

 Nenhum campo preenchido
   Dado que acesso a página de cadastro 
   Quando submeto sem preencher os campos 
   Então devo ver "Oops! Informe seu email e senha".




