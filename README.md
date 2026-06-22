#                                  Bioinformática: Análise básica de DNA bacteriano

## Descrição do Projeto
Este projeto foi desenvolvido como parte da disciplina de Práticas em Ciência de Dados, lecionada durante o 1° semestre do curso de Bacharelado em Ciência e Tecnologia, em 2026, pelos docentes Prof. Dr. Daniel Roberto Cassar, Prof. Dr. James Moraes de Almeida e Prof. Dr. Leandro Nascimento Lemos. As ferramentas criadas nesse projeto tem como objetivo realizar uma análise básica do DNA bacteriano a partir da leitura de um arquivo FASTA que contém o genoma completo de uma bactéria em fomato de sequência de nucleotídeos. A ideia do projeto surgiu do desejo de relacionar os conceitos estudados nas disciplinas de Ciência da Vida com os de Ciência de Dados aprendidos no primeiro semestre, a fim de introduzir conhecimentos sobre bioinformática. Nesse sentido, foram utilizadas ferramentas e funcionalidades do Python para processar strings, armazenar dados em listas e dicionários e plotar gráficos que interpretam características genômicas. Dessa forma, o projeto em questão pauta-se na análise gráfica de três parâmetros principais: a distribuição das bases nitrogenadas, a distribuição do tamanho das proteínas e a proporção global de aminoácidos. Além disso, ao final da análise, elabora-se um gráfico comparativo do conteúdo GC e da frequência de certas bases nitrogenadas em relação aos genomas de quatro bactérias distintas. 


## Conteúdos do repositório
Este repositório possui todos códigos necessários contidos no Notebook Jupyter "Analisador_DNA_bacteriano", bem como os arquivos de exemplo necessários para o seu bom funcionamento. Tais arquivos de exemplo devem, necessariamente, estar na mesma pasta do Notebook.

## Bibliotecas utilizadas
 - Matplotlib: biblioteca de baixo nível utilizada para plotagem de gráficos
   - pyplot: submódulo do Matplotlib que fornece ferramentas simples e intuitivas para criar, personalizar e exibir dados bidimensionais
 - NumPy: biblioteca usada para trabalhar com arrays, facilitando a plotagem dos gráficos.

## Funcionamento

A ferramenta funciona a partir da inserção do nome de um arquivo do tipo FASTA (ele deve estar contido na mesma pasta no Notebook Jupyter) que contém uma sequência de nucleotídeos/bases nitrogenadas de um DNA bacteriano, representando seu genoma.
O usuário tem liberdade de escolher utilizar os exemplos de arquivos oferecidos pelo código ou fazer o download de seus próprios arquivos e submetê-los na pasta para usar no código.

As entradas de dados para análise do DNA abrangem dois *inputs*: o primeiro *input*, com a inserção de apenas um arquivo, gera três gráficos sobre métricas importantes na bioinformática — distribuição das bases nitrogenadas, distribuição do tamanho das proteínas e a proporção global de aminoácidos —, já o segundo *input*, com a inserção de mais três arquivos além daquele inserido anteriormente, gera um gráfico comparativo do conteúdo GC e da frequência de certas bases nitrogenadas em relação ao DNA de quatro bactérias distintas. A inserção dos nomes dos arquivos deve seguir as condições necessárias impostas no código.

A inserção dos nomes dos arquivos fora das condições e limitações descritas no código acarreta erros ou gráficos que não condizem com a análise proposta pelo código

## Gráficos gerados

## Referências
- GC-content - an overview | ScienceDirect Topics. Disponível em: <https://www.sciencedirect.com/topics/biochemistry-genetics-and-molecular-biology/gc-content>.


## Desenvolvedora do projeto
- 





