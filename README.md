# Atividade: Classes e Objetos 1

## Orientações

1. Cada uma das questões deve ser entregue dentro de um pacote. Exemplo: "questao01","questao02",...,"questaoXX".

1. Dentro de cada pacote deve ter uma classe chamada Principal que deverá ter o método main.

1. **Para todas as atividades, utilize a classe Principal para criar instâncias de objetos das classes criadas e realizar testes**.

# Atividades

1. Crie uma classe para representar alunos matriculados em uma determinada disciplina. Cada objeto deve armazenar o nome do aluno, sua matrícula, 3 notas de provas e 1 nota de um trabalho.

   - Construa um método para calcular e retornar a média final do aluno, cada prova tem peso 2 e o trabalho peso 1,5.

1. Escreva uma classe para representar os livros de uma livraria. Deverá ser possível armazenar o título do livro, a quantidade de páginas, o ano da publicação, a quantidade de páginas, o nome da editora e o nome do autor. Construa um método que imprima os detalhes do livro como uma etiqueta.

   | Livro:                                                       |
   | ------------------------------------------------------------ |
   | Título: Código limpo: Habilidades práticas do Agile Software |
   | Publicação: 2009                                             |
   | Autor: Robert C. Martin                                      |
   | Editora: Alta Books                                          |

1. Altere o código da questão anterior, adicionado classes para representar o autor e editora.

   - Para o autor deve ser possível armazenar o nome e a data de nascimento.
   - Para a editora, deve ser possível armazenar o nome, o CNPJ e o endereço.
   - Faça os ajustes na impressão da etiqueta, para que continue funcionando.
   - Construa um diagrama de classe para cada uma das classes criadas (.png)

1. Observe o diagrama de classe abaixo e implemente a classe usuário. O método autenticar deve verificar se o nome de usuário e senha fornecidos estão corretos, caso positvo deve retornar **true**, caso contrário retornar **false**.

   ![Usuario](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/IFNMG-Almenara-Classes/lista-classes-objetos/main/assets/usuario.iuml)

1. Crie classes cujos objetos devem representar figuras em software de desenho. Defina os atributos básicos para desenhar cada uma, e métodos que retornem o valor de sua área. Construa diagramas de classes para cada uma.

   - Circulo
   - Quadrado
   - Triângulo
   - Losango
   - Retângulo

1. Você foi designado para desenvolver um sistema de gerenciamento de clientes para uma empresa. O sistema precisa ser capaz de representar digitalmente cada cliente. Cada cliente deve ter informações como nome, endereço, número de telefone e e-mail. Além disso, o sistema deve permitir o registro de compras feitas por cada cliente, incluindo detalhes como o produto adquirido, a data da compra e o valor. Cada produto deve ter um nome, uma descrição e um preço.

   - Baseado na descrição acima, construa um diagrama de classes para representar as classes do sistema. Em seguida implemente cada uma das classes.

1. Você foi contratado para desenvolver um jogo de aventura em que os jogadores controlam personagens em um mundo virtual. Cada personagem precisa ter uma representação digital com várias características. Inicialmente, você deve criar a classe que representa um personagem. Os personagens devem possuir as seguintes informações:

   - **Nome**: o nome do personagem.
   - Posição: a posição do personagem no mapa, com coordenadas x e y.
   - **Pontos de vida (HP)**: a quantidade de pontos de vida que o personagem possui.
   - **Pontos de ataque (ATK)**: o poder de ataque do personagem.

   Além disso, os personagens devem ser capazes de realizar as seguintes ações:

   - **Mover-se**: o personagem pode se mover em diferentes direções no mapa. As opções são: para cima, para baixo, para a esquerda e para a direita. Ao mover-se, deve-se exibir a seguinte mensagem: "Personagem [Nome do Personagem] moveu-se para a [Direção] da posição (X,Y) para a posição (X,Y)."
   - **Atacar**: o personagem pode atacar outro personagem. Ao atacar, o personagem atacado perde pontos de vida equivalentes ao poder de ataque do atacante.

   Com base nas informações acima, identifique as classes, construa o diagrama de classe e implemente cada uma.
