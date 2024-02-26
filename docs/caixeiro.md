<p align="center" width="100%">
    <img width="25%" src="/img/caixeiro_gerado_por_ia.png"> </p>

<h1 style="text-align:center"> O que é um Caixeiro Viajante?</h1>

## Contexto Histórico
Imagine um tipo de vendedor que não fica esperando você chegar à loja, mas vai até você, esteja você em casa, na empresa ou até mesmo naquele cantinho afastado no meio do nada.
O caixeiro-viajante é o mercador ambulante que vende produtos fora das regiões onde eles são produzidos, isto é, que percorre as ruas e estradas a vender seus produtos, principalmente manufaturados. 
Uma antiga profissão, tornou-se fundamental em uma época em que não havia facilidade do transporte entre cidades; os caixeiros-viajantes eram então a única forma de transportar produtos entre diferentes regiões fora das grandes cidades.
Comercializavam uma vasta categoria de produtos, visitavam residências, empresas e lojas em cidades, vilarejos e fazendas. Precisavam viajar longas distâncias e ter habilidades de comunicação e persuasão para negociar seus produtos. 
Eram os verdadeiros artistas da negociação, precisando dominar a arte da comunicação e persuasão para convencer as pessoas a comprarem seus produtos. 

<p align="center" width="100%">
    <img width="40%" src="/img/caixeiro_antigo1.jpg"> 
       <img width="38.4%" src="/img/caixeiro_antigo3.jpg"> 

</p>

Há uma publicação da Universidade Estadual do Maranhão, que relata alguns detalhes interessantes do contexto histórico deste afamado vendedor. 
A Publicação é uma dissertação de Mestrado Profissional, que tem o título: [Cultura material e imaterial do Caixeiro Viajante](https://repositorio.uema.br/bitstream/123456789/1574/2/PRODUTO%20-%20Ant%C3%B4nio%20Lopes%20Vieira%20Filho_c_Ficha_Catalogr%C3%A1fica_CORRIGIDA%20P%C3%93S%20ENTREGA.pdf)
Recomendo a leitura!


*O caixeiro viajante vestia bota de cano alto, conhecida por Musterreiter Stüfel, 
provida de grandes esporas, bombacha, mais apropriada para semanas de 
cavalgadas, camisa xadrez, lenço ao pescoço e chapéu de aba larga para proteção 
contra a canícula, além do poncho ou capa de chuva - que A. J. Renner logrou 
impermeabilizar na década de 1880, especialmente para o caixeiro viajante, que 
também ele foi. Completava a indumentária o relho de cabo curto na mão direita 
e guaiaca na cintura, onde guardava o dinheiro e também a pistola (FLORES, 2000 
apud MÜHLEN, 2018, p. 125)*


## Contexto Matemático

O problema do Caixeiro Viajante, ou Travelling Salesman Problem - TSP, é um problema clássico da otimização em matemática e da ciência da computação, que consiste em encontrar o menor caminho que permite visitar um conjunto de cidades e retornar à cidade de origem. O problema pode ser expresso matematicamente como um problema de programação linear inteira, no qual a função objetivo é a soma das distâncias entre as cidades visitadas e as restrições impõem que cada cidade seja visitada exatamente uma vez e que o percurso termine na cidade de origem.

Quando o de pontos N (“cidades”) é pequeno, o problema pode ser resolvido por meio de força bruta, listando todas as rotas possíveis para conferir qual é a mais curta. Mas isso logo se torna inviável quando N aumenta, mesmo com computadores poderosos, porque o número de rotas possíveis é dado pelo fatorial N! = 1 x 2 x … x N, o qual cresce muito rapidamente.

Na Tabela abaixo, é possível verificar que no caso de poucos pontos (vértices) o problema do caixeiro viajante não é tão complicado, porém, quando o problema tem mais pontos, a contagem dos caminhos possíveis já é um número enorme. No caso de 20 pontos é uma quantidade tão grande de cálculos que é impossível resolvê-lo em tempo real.


<p align="center" width="100%">
    <img width="72%" src="/img/contagem_de_permutações.png"> 
</p>

O problema do Caixeiro Viajante é um exemplo de problema de otimização combinatória, no qual a solução ótima é obtida através da avaliação de todas as possíveis rotas e seleção daquela com o menor custo. Como o número de possíveis rotas cresce exponencialmente com o número de cidades, o problema do Caixeiro Viajante é considerado um problema NP-difícil, o que significa que é muito difícil encontrar uma solução ótima em tempo hábil para problemas com um grande número de cidades.

Existem diversas técnicas matemáticas e algoritmos de otimização que podem ser utilizados para resolver o problema do Caixeiro Viajante, como algoritmos genéticos, meta-heurísticas, programação dinâmica, entre outros. A escolha do método depende do tamanho do problema, da complexidade das restrições e da qualidade desejada da solução.


