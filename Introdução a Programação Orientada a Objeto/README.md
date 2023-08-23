# Programação Orientada a Objetos

**O que é?**

Programação Orientada a Objetos é um paradigma de programação que se baseia na criação de objetos que possuem características (atributos) e comportamentos (métodos). Esses objetos interagem entre si para realizar ações e solucionar problemas. É uma forma de programar que busca simular o mundo real, modelando objetos que estão presentes nele.

**Exemplo usando uma caneta:**

Se formos criar metodos e atributos para uma caneta o que seria cada uma dessas coisas?, Vamos lá!, Os atributos de uma caneta é tudo aquilo que ela possui já os métodos são aquilo que ela pode fazer.

**Caneta**

**Atributos**:

- Cor: Azul
- Marca: Bic
- Ponta: 0,5

**Métodos**:

- Tampar
- Destampar
- Escrever
- Desenhar

Com esse exemplo vemos que a caneta ela possui métodos e atributos.

Dentro desse paradigma de orientação a objetos os atributos e métodos possuem níveis de segurança, no qual são eles público (public), protegido (protected), e privado (private), que são mais conhecidos como modificadores de acesso.

Os modificado de acesso servem para que seja definidos a visibilidade dos métodos ou atributos.

**Public**: Todo o sistema pode ter acesso a esse método ou atributo.

**Protected**: O modificador de acesso protected é usado em Programação Orientada a Objetos para definir que um atributo ou método só pode ser acessado dentro da própria classe e por suas subclasses. Isso é útil para implementar hierarquia de classes e garantir que métodos e atributos sejam acessíveis somente dentro dessa hierarquia.

**Private**: O modificador de acesso private é usado em Programação Orientada a Objetos para definir que um atributo ou método só pode ser acessado dentro da própria classe. Isso garante a segurança e a integridade dos dados, evitando que outros objetos ou classes possam acessar ou modificar essas informações diretamente.

Se formos definir em um código vamos ter como exemplo um código que defina um atributo “Nome”

public String nome;

O “public” é o nosso modificado de acesso.

O “String” é o nosso tipo da variável.

O “Nome” é o nome que foi dado a variável ( a varia pode recebe qualquer nome que não seja uma palavra reservada ).

Obs: As palavras reservadas são palavras que a linguagem usa para que seja criada os trechos de código. 

Ex: LocalDate, String, int… Dentre outras palavras que foram definas.

**Obs.2**: Existe um 4 modificado de acesso que é o default, ele é usado automaticamente pela IDE, que é quando vc não coloca qual você vai usar, logo ele atribui como public.

**Quais são os fundamento?**

Dentro do Paradigma da Orientação a Objeto, temos 4 fundamentos  no quais precisamos aprender sendo eles:

- Abstração
- Encapsulamento
- Herança
- Polimorfismo

Sabendo da Existência deles partiremos para a explicação de cada um:

**Abstração:** Quando vemos o conceito de abstração, pode parecer um monstro de 7 cabeças, mas o principal conceito é muito simples, a Abstração dentro do POO se refere a você retirar aquilo que é desnecessário, lembrando que!, Quando falamos de tirar o que não é necessário  e você  entender o seu problema, e com o diagnostico você saber quais informações são importantes e quais não são.

**Encapsulamento**: Quando vamos falar sobre encapsulamento temos que citar os modificadores de acesso que existem, sendo eles public, protected e private, eles servem para moderar os níveis de acesso como foi explicado lá no começo, quando vemos um controle remoto, nos temos acesso aos botões, mas não temos a placa de comando do controle, a menos que ela quebre ou que você abra o controle, mas de maneira normal a única parte que podemos mexer é o os botões, então o encapsulamento se refere a você limitar o acesso a algumas partes do código, deixando disponível apenas aquilo que o usuário deve ter acesso.

**Herança**: Quando falamos da herança, queremos falar sobre, uma classe mãe que tem outras classes filhas, essas classes filhas são identificadas através da palavra “extends” quando uma classe tiver a palavra extends, significa que ela está herdando os métodos e atributos de uma outra classe, vale ressaltar que tudo que a classe mãe tem, as classes filhas terão, mas a classe mãe não possui tudo que a classe filha possui. 

**Polimorfismo**: Com o polimorfismo já fica mais tranquilo, já que ele apenas se refere as várias formas de fazer uma determinada função, por exemplo uma função de fazer uma soma de 2 termos, ela pode ser feita de várias formas, que no final o resultado vai ser o mesmo, então não existe uma forma certa ou errada, apenas formas diferentes de se fazer uma mesma coisa.