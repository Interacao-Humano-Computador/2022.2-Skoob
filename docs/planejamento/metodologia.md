# Metodologia

## Introdução
Visando aprimorar a agilidade da equipe, e utilizar de técnicas que são conhecidas pelo grupo, foi definido que iremos utilizar metodologias ágeis, especificamente o Scrum.
</br>
O Scrum é um framework para desenvolvimento ágil tanto de software como de outras áreas. Derivado do manifesto ágil, se tornou o principal a ser utilzado para a organização e gerencia de grandes projetos, visando sempre a otimização do time, e entregas rápidas e contínuas de releases, assim como mostra a <i>Figura 1</i>.

</br>

### Fluxo do Scrum

![scrum Fluxo](./assets/planejamento/scrum.png)
<figcaption align="center">Figura 1: Fluxo do Scrum (Fonte: <a href="https://ezdevs.com.br/scrum-na-pratica-entendendo-o-fluxo/" target="_blanck">Ezdevs</a>, 2022)</figcaption>

</br>

## Política de commit

<p align="justify">&emsp;&emsp;Para maior controle sobre as alterações que são feitas nos documentos, será definido uma política de commit para organizarmos as alterações que são feitas, e quem as executou.  
De acordo com o que foi definido pela equipe, a mensagem do commit deve ser igual a mensagem de modificação deixada no histórico de versionamento do arquivo para que caso seja nescessário encontrar seu commit no repositório.  
Também foi recomendado que não seja editado mais de um arquivo de página por commit, pois logo o commit englobará os dois arquivos e será mais complicado saber o que foi modificado em cada um.  
Segue o modelo a ser seguido:</p>

```git
git commit -m "Mudança que foi feita no arquivo"
```

<p align="justify">&emsp;&emsp;Caso seja necessário usar co-authored, será utilizado normalmente sem nenhuma restrição.</p>

## Política de revisão

<p align="justify">&emsp;&emsp;Para que nenhum arquivo fique com alguma informação faltando ou errada, foi definido que a cada nova modificação feita nos arquivos, será escolhido pelo autor um outro membro da equipe para executar a revisão e apontar os pontos que precisarão ser modificados caso necessário. Se tornando obrigatório a requisição de um revisor desde a sprint 1 onde foi acordado tal exigência.</p>


## Referências

> Site Ezdevs - <a href="https://ezdevs.com.br/scrum-na-pratica-entendendo-o-fluxo/">https://ezdevs.com.br</a>

</br>

## Histórico de versão
| Versão | Data | Descrição  | Autor        | Revisor |
| :-----: | :----: | :----------: | :------------: | :--------: |
| 0.1 | 15/11/2022 | Criado arquivo sobre metodologias | Wildemberg Sales | João Pedro Alves |
| 0.2 | 18/11/2022 | Ajustado links e títulos | Wildemberg Sales | João Pedro Alves |
| 0.3 | 22/11/2022 | Ajustado figura sobre scrum | Wildemberg Sales | João Pedro Alves |