# Anotações Git/GitHub



git e github - comandos básicos p/ um bom desempenho no terminal
----------------------------------------------------------------

cd .. -> sair da pasta
cls -> pra limpar a tela
dir -> mostrar aa pastas e arquivos
mkdir (nome da pasta) -> para criar pasta
rmdir (nome da pasta) /S /Q -> remover a pasta com arquivo dentro

------------------------

## Objetos internos do Git

Blobs -> tipo do objeto, tamanho da string, \0, conteúdo do arquivo
contém metados do git

Tree -> armazenam blobs

commit -> tree, parente, autor, mensagem, timestamp

commit -> tree -> blobs

------------------

Chave SSH e Token
------------------

chave SSH -> forma de estabelecer conexão segura e criptada
tem sempre duas chaves, publica e privada
autoriza a maquina que vc usa a colocar códigos no github

token -> uma chave gerada que sempre pedi login senha
(o mais fácil quando se tem uma maquina de confiança é o SSH)

------------------------------------

Iniciando o Git e criando um commit
------------------------------------

git init - para criar um repositório dentro de
uma pasta.

## Mudanças no arquivo do código

Depois que fizer uma mudança no arquivo é só dar um 

git add * (para adicionar as mudanças)



Agora precisa commitar as mudanças

git commit -m "adiciona receita pavê"



git push origin master

As vezes pode abrir para colocar login e senha do github novamente

para atualizar no github