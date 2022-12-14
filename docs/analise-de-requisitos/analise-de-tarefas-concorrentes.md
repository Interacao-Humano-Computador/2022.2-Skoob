# Árvores de Tarefas Concorrentes

## Introdução

<p align="justify">Uma análise de tarefas é utilizada para se ter um entendimento sobre qual é o trabalho dos usuários, como eles o realizam e por quê. Nesse tipo de análise, o traba-
lho é deﬁnido em termos dos objetivos que os usuários querem ou precisam atingir.</p>
<p align="justify">Em IHC, a análise de tarefas pode ser utilizada nas três atividades habituais: para
análise da situação atual (apoiada ou não por um sistema computacional), para o
(re)design de um sistema computacional ou para a avaliação do resultado de uma
intervenção que inclua a introdução de um (novo) sistema computacional.</p>

## Árvores de Tarefas Concorrentes

<p align="justify">O modelo de árvores de tarefas concorrentes foi criado
para auxiliar a avaliação e o design de IHC. Nesse modelo,
existem quatro tipos de tarefas:</p>
<ul>
<li>tarefas do usuário, realizadas fora do sistema;</li>
<li>tarefas do sistema, em que o sistema realiza um processamento sem interagir
com o usuário;</li>
<li>tarefas interativas, em que ocorrem os diálogos usuário–sistema;</li>
<li>tarefas abstratas, que não são tarefas em si, mas sim uma representação de
uma composição de tarefas que auxilie a decomposição.</li>
</ul>
<p align="justify">Essas tarefas podem ser vizualidas na figura 1 e a hierarquia delas na figura 2. A hierarquia deve ser lida como "para considerar T1 como tendo sido realizada, as tarefas T2 e T3 de-
vem ter sido realizadas"</p>

<img src= "../assets/arvore2.png" >
<figcaption align='center'>
    Figura 1: Representação dos tipos de tarefas.
    <br>
</figcaption>

<img src= "../assets/hierarquia.png" >
<figcaption align='center'>
    Figura 2: Representação da sua hierarquia.
    <br>
</figcaption>

## Diagrama de Análise de Tarefas Concorrentes

<p align="justify">No site Skoob, foram escolhida três tarefas para serem analisadas como mostra nas figuras 3, 4 e 5.</p>

<img src= "../assets/escreverUmaFrase.png" width="670" align='center' >

<figcaption align='center'>
    Figura 3: Árvore de tarefas concorrentes referente a escrever uma frase que goste.
    <br>
</figcaption>

<img src= "../assets/addLivroLido.png" width="670" align='center' >

<figcaption align='center'>
    Figura 4: Árvore de tarefas concorrentes referente a adicionar um livro como lido.
    <br>
</figcaption>

<img src= "../assets/avaLivro.png" width="670" align='center' >

<figcaption align='center'>
    Figura 5: Árvore de tarefas concorrentes referente a avaliar um livro lido.
    <br>
</figcaption>

## Histórico de versão

| Versão |    Data    |                 Descrição                  |            Autor             |  Revisor   |
| :----: | :--------: | :----------------------------------------: | :--------------------------: | :--------: |
|  1.0   | 02/12/2022 |       Criação da analise de tarefas        | Hellen Fernanda e Caio Vitor | João Pedro |
|  1.1   | 04/12/2022 | Finalizando Árvore de tarefas concorrentes |       Hellen Fernanda        | João Pedro |

## Refências

> Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Autopublicação.
