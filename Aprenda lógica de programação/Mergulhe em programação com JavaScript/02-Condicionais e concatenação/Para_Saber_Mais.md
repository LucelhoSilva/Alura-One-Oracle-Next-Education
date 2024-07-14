# Para saber mais: ponto e vírgula no JavaScript

No JavaScript, o uso do ponto e vírgula **;** é uma prática recomendada. A linguagem possui um mecanismo chamado "inserção automática de ponto e vírgula" (automatic semicolon insertion - ASI), que tenta adicionar ponto e vírgulas automaticamente em certos pontos do código onde eles são ausentes.

Isso significa que, em alguns casos, o JavaScript tentará "corrigir" a falta de ponto e vírgula inserindo-o automaticamente. No entanto, a interpretação do ASI pode levar a comportamentos inesperados e erros sutis, especialmente quando as regras não são claras.

Portanto, para evitar possíveis problemas e garantir a clareza do código, muitos desenvolvedores preferem adicionar explicitamente ponto e vírgula em seus programas.

Apesar da inserção automática de ponto e vírgula poder ajudar a mitigar erros de sintaxe, é uma boa prática adicionar ponto e vírgula manualmente para evitar ambiguidades e problemas de interpretação. Isso é particularmente importante em situações como quando várias instruções estão em uma mesma linha, ao usar declarações de retorno de valor ou ao minificar o código.

Em projetos colaborativos ou de grande escala, a consistência no estilo de codificação e a clareza do código são cruciais, e o uso explícito de ponto e vírgula contribui para um código mais legível e menos sujeito a erros de interpretação por parte dos programadores e do próprio mecanismo de ASI.

- [Leitura complementar da documentação sobre o JavaScript.](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Lexical_grammar#automatic_semicolon_insertion)

- Quer saber o que a comunidade recomenda? [Leia mais neste link do Stack Overflow.](https://pt.stackoverflow.com/questions/3341/utilizar-ou-n%C3%A3o-ponto-e-v%C3%ADrgula-no-fim-das-linhas-em-javascript)
