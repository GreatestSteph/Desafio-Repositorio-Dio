# Introdução ao Git e ao GitHub

##### O que é Git?

Git é um sistema de versionamento de código distribuído, ele possui o ambiente de desenvolvimento, ou seja, ele utiliza o repositório local, no seu próprio computador.

##### O que é GitHub?

GitHub é um tipo de servidor, um repositório remoto.

#### Benefícios de usar Git e GitHub:

- Controle de versão;
- Armazenamento em nuvem;
- Trabalho em equipe;
- Melhoramento de código;
- Reconhecimento.

#### Comandos a serem usados:

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

  

#### Alguns conceitos sobre o Git e o GitHub:

Ambos Git e GitHub utilizam o markdown.

Também é utilizado o SHA (Secure Hash Algorithm), ele oferece segurança ao encriptar fotos, arquivos e pastas em um tipo de código de 40 dígitos. Você pode dar uma olhada em como a Git faz a encriptação de um arquivo através do seguinte comando:

`$ openssl sha1 texto.txt`

**Observação:** Neste exemplo foi usado o texto.txt, mas pode ser utilizado qualquer arquivo.



#### Configurando o Git:

É necessário definir o autor de uma commit, para saber quem fez a modificação ou criação de um repositório.



Para definir o email do autor usa-se:

`$ git config --global user.email "seuemailaqui@gmail.com"`

Para definir o nome do autor usa-se:

`$ git config --global user.nickname "Fulano"`

Para remover o email do autor das configurações usa-se:

`$ git config --global --unset user.email`

Para remover o nome do autor das configurações usa-se:

`$ git config --global --unset user.nickname`

Para ver como o seu Git está configurado usa-se:

`$ git config --list`
