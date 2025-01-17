# Principais comandos Git 

Aqui serão registrados os principais comandos Git citados durante meu estudo de DevOps.


### Para criar um novo repositório:


1. Criar diretório no /home do usuário
   ```sh
   mkdir ~/<nome-do-repositorio>
   # obs: deve-se digitar o ~/ para que o diretório seja criando dentro 
   # do /home/<nomedousuario> e não em um outro diretório qualquer.
   ```
2. Entrar no diretório recém criado
   ```sh
   cd ~/<nome-do-repositorio>
   # obs: deve-se digitar o ~/ para que o usuário entre no diretório certo.
   ```
3. Agora deve-se criar o repositório no GitHub com o mesmo nome do 
   diretório ao qual ele se será conectado.
    
4. O usuário deve entrar no seu perfil do github.com e clicar no botão
   verde *new* que aparece no canto superior esquerdo da tela.

5. Retorne ao terminal e crie o repositório seguindos os comandos:
   ```sh
   echo "# <nome-do-usuario>" >> README.md
   git init
   git add README.md
   git commit -m "first commit"
   git remote add origin git@gitbub.com:<nome-do-usuario>/<nome-do-repositorio>.git
   git push -origin main (ou o nome do repositório)
   ```
