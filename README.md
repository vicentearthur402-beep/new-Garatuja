# GARATUJA - ARTHUR IA 25

## [HTML]
Linguagem de marcação utilizada em sites web, definindo elementos como texto, links, videos, etc.

## [CSS]

Linguagem de estilo para estilizar o HTML.

# [JS X JAVA X TS]
## JAVASCRIPT
JavaScript é uma linguagem leve e dinâmica, usada principalmente para criar interatividade em páginas web. Roda direto no navegador e também no servidor (com Node.js). É flexível, mas isso também pode gerar mais erros se o código crescer muito.

## Exemplo:

<pre>function somar(a, b) {
  return a + b;
}

console.log(somar(5, 3));</pre>

## TYPESCRIPT
TypeScript é basicamente um “JavaScript melhorado”. Ele adiciona tipagem (ou seja, você define tipos de variáveis, funções, etc.), o que ajuda a evitar erros antes mesmo de rodar o código. No final, o TypeScript é convertido em JavaScript para funcionar no navegador. É muito usado em projetos grandes porque organiza melhor o código.

## Exemplo:
<pre>
  function somar(a: number, b: number): number {
  return a + b;
}

console.log(somar(5, 3));
</pre>

## JAVA
Java já é outra coisa. É uma linguagem mais antiga, forte e totalmente tipada, usada principalmente para sistemas grandes, backend, aplicativos Android e aplicações corporativas. Não roda direto no navegador como JavaScript. Precisa de uma máquina virtual (JVM) para executar.

## Exemplo:

<pre>
  public class Main {
    public static int somar(int a, int b) {
        return a + b;
    }

    public static void main(String[] args) {
  
        System.out.println(somar(5, 3));
    }
}
</pre>

# Programação Orientada ao Objeto

## Classe
Estrutura que define um molde para criar objetos.
Em TypeScript, utiliza a palavra-chave class.

## Objeto
Instância de uma classe.
Representa um elemento com estado (atributos) e comportamento (métodos).

## Atributo
Variável definida dentro de uma classe.
Armazena dados relacionados ao objeto.

## Método
Função definida dentro de uma classe.
Representa ações ou comportamentos do objeto.

## Getters e Setters
Métodos especiais para acessar (get) e modificar (set) atributos.
Permitem controle e validação no acesso aos dados.

## Construtor
Método especial chamado ao criar um objeto.
Usado para inicializar atributos da classe.

## Herança
Permite que uma classe herde propriedades e métodos de outra.
Utiliza a palavra-chave extends no TypeScript.

## Encapsulamento
Restrição de acesso direto aos dados da classe.
Utiliza modificadores como public, private e protected.

## Polimorfismo
Capacidade de métodos terem comportamentos diferentes.
Pode ocorrer via sobrescrita (override) ou interfaces.
