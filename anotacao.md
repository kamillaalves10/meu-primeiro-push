# Git e GitHub

## 08/06/2026
Mesmo após instalar o Git e outras ferramentas no terminal corretamente é possível que seu funcionamento não seja reconhecido pelo terminal Windows.  na maioroa das vezes é apenas a falta do caminho do programa a variável PATH. 
Para resolver esse problema, primriro localizamos a pasta\diretório de instalação do programa, onde devemos localizar a pasta Bin e copiar seu caminho. EX: C:/git/bin. Após obter o caminho devemos abrir o Editor de Variáveis de Ambiente do Windows, selecionar a PATH, clicar em EDITAR e então clicar em NOVO, para enfim colocar o caminho do programa.
Não esquecer de reiniciar o terminal para que as alterações tomem efeito.

## 09/06/2026

Para iniciar o Git em uma pasta, devemos abrir um terminal nela e o comando de inicialização do Git:
git init

Assim que o git for inicializado precisamos indicar os arquivos que devem ser rastreados. Para isso utilizaremos o co git mando:
git add nomeDoArquivo.js

Quando os arquivos que foram adicionados para a área de preparação são modificados, você verá algumas indicações no VSCode em forma de letras ao lado do nome do arquivo e alguns indicadores de cor ao lado de linhas alteradas.
*git commit -m ""