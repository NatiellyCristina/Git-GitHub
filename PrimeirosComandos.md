# Git-GitHub / Primeiros Comandos



#  Criando um novo repositório no GITHUB

1. Acesse o seu perfil no GitHub e selecione o botão `new`
   
    ![Untitled](Imagens/Untitled.png)
    
2. Adicione as informações do repositório, como título e uma breve descrição
   
    ![Untitled](Imagens/Untitled%201.png)
    
3. Escolha a visibilidade do repositório
    1. Publico:  aberto para todos os usuários da internet.
    2. Privado: aberto somente para você e usuários permitidos.
    
    ![Untitled](Imagens/Untitled%202.png)
    
4. Caso você deseje que esse repositório seja iniciado com o arquivo README deve ser selecionado a opção **Add a README file**
   
    ![Untitled](Imagens/Untitled%203.png)
    
5. Para concluir o processo clique no botão `Create repository`
   
    ![Untitled](Imagens/Untitled%204.png)
    

# Clonando o repositório

1. Depois de criar o repositório do GitHub devemos trazer o mesmo para máquina local, sendo assim clique no botão `code` e copie o https disponibilizado.

![Untitled](Imagens/Untitled%205.png)

1. Cria um novo diretório na sua máquina.
2. Acesse o `Git Bash` e navegue até o diretório criado anteriormente.
3. Adicione o comando `git clone https` (https copiado no primeiro passo)
4. Prontinho, repositório clonado para o repositório local
   
    ![Untitled](Imagens/Untitled%206.png)
    
5. Navegue até o diretório criado na sua máquina local e observe que o repositório criado no GitHub está na pasta.
6. Sendo assim, basta rodarmos o comando `cd` e entrar no mesmo, assim já podemos  gerenciar nossos projetos com o `Git` e submete-los no `GitHub`

# Adicionando arquivos ao GitHub

1. Adicione algum arquivo no diretório clonado no tópico anterior.

2. Estando com o `Git Bash` aberto e na pasta do repositório clonado, digite  o comando `git status` 

3. Observe que vai aparecer uma mensagem dizendo que temos alguns arquivos para incluirmos.

    ![Untitled](Imagens/Untitled%207.png)

4. Sendo assim, rode o comando `git add .`  ou `git add -A`  , assim iremos adicionar todos os arquivos e alterações pendentes  no  controle de versão local.

5. Para adicionar as alterações no GitHub precisar rodar o comando `git commit -m “mensagem”`.

    <aside>
    💡 Vale salientar que as mensagens de commit são muito importantes, sendo assim sempre descreva brevemente o que foi realizado e está sendo submetido.
    ![Untitled](Imagens/Untitled%208.png)

6. E em seguida digite o comando `git push origin main`, para que as informações de fato sejam enviadas.

7. Acesse o GitHub e já poderá visualizar seus arquivos e alterações.