# Introdução ao Git e Github

### SHA 1: Algoritmo de encriptação. 

- Gera chaves criptografadas de 40 caracteres.  
- Cada modificação no arquivo gera uma nova chave

### Objetos internos do Git:

**Blobs:** objeto que contém metadados usados pelo git (armazena o SHA 1 do arquivo)

**Trees:** armazenam os blobs. Guardam o nome dos arquivos. Apontam para blobs ou para outras trees. Ao alterar o sha1 do blob, seu sha1 também é modificado

**Commits:** apontam para trees, para o último commit, para commits parentes, autor, mensagem, timestamp. Proporcionam segurança ao criar uma espécie de linha do tempo do arquivo.

### Chaves SSH e Tokens:

**Chave SSH:** Conexão segura entre duas máquinas. Ao criar uma chave SSH, o clone de repositório deve ser via caminho SSH. 

**Token:** Token pessoal é gerado no Github e mantido na máquina. 

github > developer settings > personal access token



