# Criação da Chave SSH :key:

Para começar a utilizar o Git, é recomendável que crie uma chave primeiramente.

A chave SSH pode ser pública ou privada, ela permite estabelecer uma conexão entre o servidor do GitHub e da máquina local. Quando criada e ativada, ela facilmente reconhece a máquina que está sendo utilizada através de uma assinatura.



### Como criar uma chave:



1. **Abra o Git Bash e digite:** 

   `$ ssh-keygen -t ed25519 -C seu_email@gmail.com`

   **Observação:** você deve colocar seu próprio email.



2. **Você pode escolher o local aonde o seu arquivo será salvo ou apena o local padrão apertando "Enter"**

   

3. **Você pode adicionar uma frase ou senha secreta, mas se você não quiser uma senha, deixe-a em branco e pressione "Enter"**

   

4. **Após todo esse passo-a-passo, sua chave finalmente foi criada e foi salva na pasta .ssh/**



5. **Agora vá para a pasta .ssh e use o Git Bash para ler os arquivos da chave através dos seguintes comandos:** 

   `$ cat id_ed25519.pub`

   **Observação:** após digitar esse comando o git mostrará algumas informações importantes no qual é necessário copiar.

   

6. **Com a informação copiada, vá para o site do GitHub, clique em "Settings" e vá para "SSH and GPG keys". Logo clique em "New SSH key" e cole a informação copiada, não se esqueça de dar um nome para a chave usada**. 



7. **Após isso, para ativar sua chave, volte para o Git e digite esses dois comandos:**

   `$ eval $(ssh-agent -s)`

   `$ ssh-add id_ed25519`

   

   Parabéns! Com todo esse processo você conseguiu criar e ativar sua chave!

   
