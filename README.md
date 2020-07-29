# problema-1201-URI

Operações em ABP II

Marcela nem terminou de fazer o programa anterior e o professor já lhe pediu um novo programa, com aprimoramentos sobre o programa anterior. Este novo programa é a implementação de uma Árvore Binária de Pesquisa (ou Busca) mas utilizando números inteiros agora, e que deve aceitar um comando extra (R) com relação ao programa anterior:

I n: Insere na árvore binária de pesquisa o elemento n.
INFIXA: lista os elementos já inseridos segundo o percurso infixo
PREFIXA: lista os elementos já inseridos segundo o percurso prefixo
POSFIXA: lista os elementos já inseridos segundo o percurso posfixo
P n: Pesquisa se o elemento n existe ou não na árvore.
R n: Remove o elemento n da árvore, caso ele exista.
A qualquer momento pode-se inserir um elemento, visitar os elementos previamente inseridos na ordem infixa, prefixa ou posfixa, procurar por um elemento na árvore para saber se o elemento existe ou não ou ainda retirar um elemento.

Nota: Se um elemento com duas sub-árvores (direita e esquerda) for removido, o antecessor (o elemento maior de sub-árvore esquerda, deve ocupar o seu lugar e ao tentar retirar um elemento que não existe, nenhuma mensagem deve ser apresentada.

Entrada

A entrada contém N operações utilizando números inteiros (1-106) sobre uma árvore binária de Busca, que inicialmente se encontra vazia. A primeira linha de entrada contém a inserção de algum elemento. As demais linhas de entrada podem conter quaiquer um dos comandos descritos acima, conforme exemplo abaixo. O final da entrada é determinado pelo final de arquivo (EOF).

Saída


Cada linha de entrada, com exceção das linhas que contém os comandos "I" ou "R", deve produzir uma linha de saída. A saída deve ser de acordo com o exemplo fornecido abaixo. Não deve haver espaço em branco após o último caractere de cada linha, caso contrário, sua submissão receberá Presentation Error.
