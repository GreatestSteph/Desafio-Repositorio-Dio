# Comandos do Git :book:

O Git possui comandos com diversas funções, na aulas foram mostradas as seguintes:

- Listar pastas;
- Criar pastas ou deletar pastas; 
- Criar, mover ou deletar arquivos;
- Navegar entre as pastas;
- Criação e ativação da chave SSH;
- Iniciar um repositório;
- Criar uma commit;
- Salvar um repositório no GitHub;
- Ver status do seu repositório;
- Saber a qual repositório ou se ele já existe;
- Clonar um repositório do GitHub na sua máquina.



1. **Listar pastas:** 

   Para mostrar pastas ocultas você deve digitar:

   `$ ls -a`

   Para mostrar pastas, que não estão ocultas, você deve digitar:

   `$ ls`

   

2. **Criar ou deletar pastas:**

   Para criar pastas no seu computador você deve digitar:

   `$ mkdir nomedasuapasta`

   Para deletar uma pasta do seu computador você deve digitar:

   `$ rm -r nomedasuapasta`

   Para deletar uma pasta do seu repositório GitHub você deve digitar:

   `$ git rm -r nomedasuapasta`

   

3. **Criar, mover ou deletar qualquer tipo de arquivos:**

   Para criar um arquivo você deve digitar:

   `$ echo > nomearquivo.txt`

   Para mover um arquivo do local atual para determinada pasta, você deve digitar:

   `$ mv nomearquivo.md ./nomepasta/`

   Para deletar um arquivo você deve digitar:

   `$ rm nomearquivo.txt`

   Para deletar um arquivo do seu repositório GitHub, você deve digitar:

   `$ git rm nomearquivo.txt`

   

4. **Navegar entre pastas:**

   Para ir para uma pasta dentro do local no qual você se encontra, você deve digitar:

   `$ cd nomedapasta/`

   Para voltar para uma pasta anterior você deve digitar:

   `$ cd ..`

   

5. **Iniciar um repositório:**

   Deve se iniciar um repositório dentro da pasta escolhida, através do comando:

   `$ git init`

   

6. **Para criar uma commit você pode usar esses comandos:**

   Este seleciona todos arquivos para a commit:

   `$ git add *` 

   Este seleciona qualquer um arquivo, de uma determinada pasta, que deve fazer parte da commit:

   `$ git add nomedoarquivo.txt ./nomedapasta/`

   Este cria a commit:

   `$ git commit -m "escreva aqui o que foi feito nessa commit"`

   Caso haja um erro na commit, você deve usar esse comando e depois solucionar o problema manualment:

   `$ git pull origin master`

   

7. **Salvar um repositório no GitHub, após fazer uma commit:**

   Primeiro você deve acessar o GitHub, ir em" Repositories" e clicar em "New", lá você dará um nome e descrição para seu repositório.

   Após criado, você terá que acessar o Git para passar o seu repositório local no GitHub, com os seguintes comandos:

   `$ git remote add origin git@github.com:seu-nome/nome-do-seu-respositorio.git`

   `$ git push origin master`

   

8. **Ver status do respositório:**

   Para isso você pode usar o seguinte comando:

   `$ git status` 

   

9. **Saber a qual repositório ou se ele já existe:**

   `$ git remote -v`

   

10. **Clonar um repositório do GitHub na sua máquina:**

    `$ git clone https://github.com/nome-usario/nome-do-repositorio`
