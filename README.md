<img alt="logo ilum" src="Ilum_Horizontal_com assinatura (1).png" />

# Bioinformática: Análise básica de DNA bacteriano

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
Utilizando os exemplos disponibilizados pelo projeto, obtem-se os seguintes gráficos:

- Gráfico da distribuição de bases nitrogenadas do DNA da <i>Pseudomona aeruginosa</i> 
   <img width="492" height="353" alt="image" src="https://github.com/user-attachments/assets/50b70e43-3d42-48da-9857-e080a9717c48" />

- Histograma da distribuição do tamanho das proteínas da <i>Pseudomona aeruginosa</i>
  <img width="522" height="352" alt="image" src="https://github.com/user-attachments/assets/6716cdaf-5733-44e2-bc59-9efa2349ffec" />
  
- Gráfico da distribuição de aminoácidos do genoma da <i>Pseudomona aeruginosa</i>
<img width="478" height="307" alt="image" src="https://github.com/user-attachments/assets/b6f21e28-dbff-4a76-9eae-53c7841aa4ee" />

- Gráfico da comparativo do Conteúdo GC(%) X Frequência de aminoácidos ricos em GC do DNA de 4 bactérias: <i>Pseudomona aeruginosa</i>, <i>Streptococcus pneumoniae</i>, <i>Neisseria gonorrhoeae</i> e <i>Mycobacterium tuberculosis</i>
  <img width="444" height="428" alt="image" src="https://github.com/user-attachments/assets/73cfb1b2-aa2e-4f56-8c8b-ee8659ab9ca0" />


## Referências
- GC-content - an overview | ScienceDirect Topics. Disponível em: <https://www.sciencedirect.com/topics/biochemistry-genetics-and-molecular-biology/gc-content>.
- MURAD, A. Onconews - Entendendo o código genético universal e sua leitura. Disponível em: <https://www.onconews.com.br/site/atualizacao-cientifica/drops-de-genomica/entendendo-o-codigo-genetico-universal-e-sua-leitura.html>. Acesso em: 23 jun. 2026.
- DNA -TRANSCRIÇÃO Transcrição é a síntese de uma molécula de RNA a partir de um molde de DNA. [s.l: s.n.]. Disponível em: <https://arquivos.ufrrj.br/arquivos/2023221100840d3687705daf7fc128d85/Aula_-_DNA_-_Transcrio__e__Tipos_de_RNA.pdf>. Acesso em: 23 jun. 2026.

## Desenvolvedora do projeto
- [Heloísa Sampaio Carvalho ](https://github.com/helo-sampc)
<img alt="minha_foto" src="minnha foto.jpeg" width = "100px"/>

## Professores responsáveis
<table>
  <tr>
    <td align="center">
      <a href="https://github.com/drcassar">
        <img src="https://avatars.githubusercontent.com/u/9871905?v=4" width="100px;" alt="Foto do Daniel no Github" style="border-radius:100%;"/><br>
        <b>Prof. Dr. Daniel R. Cassar</b>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/llemos">
        <img src="https://avatars.githubusercontent.com/u/1894434?v=4" width="100px;" alt="Foto do Leandro no Github" style="border-radius:100%;"/><br>
        <b>Prof. Dr. Leandro Nascimento Lemes</b>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/jamesmalmeida">
        <img src="https://ilum.cnpem.br/wp-content/uploads/2022/05/CF_3214-scaled-2053x2053.jpg" width="100px;" alt="Foto do James no site da ILUM" style="border-radius:100%;"/><br>
        <b>Prof. Dr. James Moraes de Almeida</b>
      </a>
    </td>
  </tr>
</table>

## Agradecimentos
Dedico meus agradecimentos ao professores responsáveis pela disciplina e seus esforços em fornecer suporte na elaboração do projeto
