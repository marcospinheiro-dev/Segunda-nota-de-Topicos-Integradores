#### 1. Por que devemos fazer testes automatizados nas aplicações que desenvolvemos?
Aumenta a eficiência do processo de testagem.
Então, os testes automatizados economizam tempo e conseguem captar mais detalhadamente os possíveis erros, aumentando assim a eficiência do teste e da entrega final.
#### 2. O que são testes unitários?
São testes que verificam se uma parte específica do código, costumeiramente a nível de função, se está funcionando corretamente. Em um ambiente orientado a objetos é usualmente a nível de classes e a mínima unidade de testes inclui construtores e destrutores.
#### 3. O que são testes automatizados?
É um procedimento que permite que o sistema seja testado de forma padronizada e repetitiva, com o mínimo envolvimento de mão de obra manual. Nesse sentido, as ferramentas de automação não substituem o papel da equipe responsável por realizar os testes manuais no sistema.
#### 4. Escolha uma pirâmide de testes e descreva com suas palavras cada secção da pirâmide.
A divisão mais comum entre as várias Pirâmides, é aquela representada por 3 níveis:

A Base - Teste Unitário

O Meio - Teste de Integração

O Topo - Testes Ponta a Ponta

Os níveis estão relacionados ao objetivo e ao objeto de teste, seja de forma manual ou automatizada.

O teste Unitário é feito nas menores partes do código, pois, caso outros testes falhem, então será possível saber o local exato da falha. Algo considerado muito importante na programação, são as boas práticas e dentro dos testes unitários, uma BP é que esses testes sejam criados e executados pelos desenvolvedores, outra coisa
importante é que esses testes servirão para novos desenvolvedores que estejam entrando no time possam entender melhor o código e poderem pensar em soluçoes.

Levando em consideração que um sistema tem várias partes, o Teste Unitário testa parte das partes, porém precisamos ter certeza que essas partes estão se comunicando, interagindo entre si de forma correta, nesse momento passamos a um nível mais avançado que poderá nos dar essa precisão, o Teste de Integfração.

Por fim, o Teste de Ponta a Ponta (E2E),será a nível de usuário, saber se realmente o sistema atende aos requisitos solicitados no projeto, por ser um teste mais complexo, deve-se atentar às partes mais importantes do produto, à regra de negócio. Os testes servirão para confirmar a intenção real do sitema, a geração de todas as informações necessárias ao negócio, bem como, o armazenamento no banco de dados dos registros solicitados pelo cliente.
