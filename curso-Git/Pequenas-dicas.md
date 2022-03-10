## Dicas de códigos do git

- `git add "arquivos"` Este comando adiciona o(s) arquivo(s) em um lugar que chamamos de INDEX, que funciona como uma área do git no qual os arquivos possam ser enviados ao Github. É importante saber que ADD não está adicionando um arquivo novo ao repositório, mas sim dizendo que o arquivo (sendo novo ou não) está sendo preparado para entrar na próxima revisão do repositório.


- `git commit -m "comentário qualquer" ` Este comando realiza o que chamamos de “commit”, que significa pegar todos os arquivos que estão naquele lugar INDEX que o comando `add` adicionou e criar uma revisão com um número e um comentário, que será vista por todos.


- `git push` Push (empurrar) é usado para publicar todos os seus commits para o github. Neste momento, será pedido a sua senha.


- `git status` Lista todos os arquivos novos ou modificados para serem commitados.
- `git reset [arquivo] `Deseleciona o arquivo, mas preserva seu conteúdo.
- `git diff` Mostra diferenças no arquivo que não foram realizadas.
- `git diff --staged `Mostra a diferença entre arquivos selecionados e a suas últimas  versões.
- `git commit -m "[mensagem descritiva]" `Grava o snapshot permanentemente do arquivo no histórico de versão.