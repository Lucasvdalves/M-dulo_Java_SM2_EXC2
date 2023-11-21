# M-dulo_Java_SM2_EXC2


# Exercícios referente aos módulos de Java Lista da semana 2

1 --  a) Crie uma classe 'Funcionario' com os atributos 'nome' (String) e 'salário' (Float).
      b) Implemente um construtor que receba um argumento de nome e inicialize o atributo de 'nome' com este valor.
      c) Implemente outro construtor que receba como argumentos nome e salário e inicialize os respectivos atributos.
      d) Implemente um método público 'aumentar' que recebe como parâmetro um valor (Float). Na implementação, some este valor ao 'salário'.
      e) Implemente outro método público 'aumentar' que recebe como parâmetros um valor (Float) e uma commissão (Float). Na implementação,
      some ambos os valores ao 'salário'.

2 --  a) Crie uma classe 'Contador'.
      b) Crie um método estático (static) 'contarPalavras' que recebe uma frase (String) como argumento.
      c) Implemente o método imprimindo no console o número de palavras da frase recebida como parâmetro.
      d) Crie um método main em outra classe para testar a implementação.

3 --  a) Crie uma classe 'Contador2'.
      b) Crie um atributo privado 'frase' (String) nesta classe.
      c) Implemente um construtor que receba uma frase como parâmetro, e inicialize o atributo criado com esta frase.
      d) Implemente um método (não static desta vez) 'contarPalavras' que retorna a quantidade de palavras da frase indicada no atributo da classe.
      e) Crie um método main em outra classe para testar a implementação.

4 --  a) Crie a interface "Operavel", com os métodos depositar(double valor) e sacar(double valor).
      b) Crie a classe Abstrata Conta com o atributo "saldo" (double) e um método protegido (protected) "ObterSaldoAtual()".
      c) Crie uma classe "ContaCorrente" que implemente a interface Operavel e herde da classe Conta. Faça uma implementação dos métodos herdados.

5 -- Vamos criar uma funcionalidade de manipulação dos resultados de sorteios da mega-sena dividido em várias partes/exercícios.

     A mega-sena trata-se de um sorteio de seis números de 1 a 60, e o grande ganhador é quem acertar estes seis números sorteados.

    a) Primeiro crie uma classe 'Concurso' para representar um concurso/sorteio.
    b) Nesta classe, crie os atributos privados abaixo e os respectivos métodos getters & setters:
    private Integer numero;
    private LocalDate data;
    private int[] sorteados;
    c) Implemente também o método 'toString()' nesta classe.
    d) Adicione o construtor padrão/default, e um construtor que receba parâmetros para inicializar cada atributo desta classe.
    e) Crie uma classe 'Principal' com método 'main'. Neste método, implemente a leitura do arquivo em anexo contendo o resultados de sorteios
    da mega-sena, e para cada linha, instancie um objeto de 'Concurso' e armazene eles em um ArrayList para manipulação posterior.
    f) Imprima esta lista de concursos carregadas a partir do arquivo no console.


