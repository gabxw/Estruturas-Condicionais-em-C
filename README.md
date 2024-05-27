**Sistema de Cadastro de Alunos e Notas**

Este é um programa em C que implementa um sistema de notas para alunos. O programa permite que o usuário cadastre alunos e suas notas, altere as notas de alunos cadastrados e saia do programa.

O programa utiliza duas matrizes bidimensionais para armazenar os nomes dos alunos e suas notas, respectivamente. Além disso, utiliza vetores para armazenar o total das notas de cada aluno, a média das notas de cada aluno e o status de cada aluno (aprovado, reprovado ou em recuperação).

O programa define duas constantes para limitar o número de alunos e notas que podem ser cadastrados. Atualmente, o programa suporta até 5 alunos com 4 notas cada.

Ao iniciar o programa, o usuário é apresentado com um menu de opções. A opção 1 permite que o usuário cadastre alunos e suas notas. A opção 2 permite que o usuário altere as notas de alunos cadastrados. A opção 3 permite que o usuário saia do programa.

Ao selecionar a opção 1, o programa solicita que o usuário digite o nome de cada aluno e suas notas. O programa verifica se as notas digitadas são válidas (entre 0 e 10) e calcula a média das notas de cada aluno. Em seguida, o programa atribui um status a cada aluno com base em sua média. Os status são: aprovado (média maior ou igual a 7), em recuperação (média entre 4 e 6.9) e reprovado (média menor que 4).

Ao selecionar a opção 2, o programa solicita que o usuário digite o nome de cada aluno e suas novas notas. O programa verifica se as notas digitadas são válidas (entre 0 e 10) e atualiza a média e o status de cada aluno com base nas novas notas.

Ao selecionar a opção 3, o programa exibe uma mensagem de saída e retorna zero.

O programa utiliza a função system("cls") para limpar a tela do console e a função system("pause") para pausar a execução do programa e permitir que o usuário leia a saída antes de fechar a janela do console.

O programa também utiliza a função strcpy para copiar strings e a função scanf com o especificador %s para ler strings do usuário. É importante notar que a função scanf com o especificador %s não lê espaços em branco, incluindo quebras de linha. Portanto, é necessário utilizar a função getchar para ler e descartar a quebra de linha após ler uma string com scanf. No entanto, este programa não utiliza getchar para descartar quebras de linha, o que pode causar problemas se o usuário digitar uma string com espaços em branco ou quebras de linha.

Em resumo, este programa é uma implementação simples de um sistema de notas para alunos em C. Ele permite que o usuário cadastre alunos e suas notas, altere as notas de alunos cadastrados e saia do programa. O programa utiliza matrizes bidimensionais e vetores para armazenar os dados dos alunos e calcula a média e o status de cada aluno com base nas notas cadastradas.
