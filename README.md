# GraceConverter
Uma ferramenta para a conversão de tabelas para o formato aceito pelo Grace.

---

Copiar valores de tabela para o formato do Grace é o inferno. Esse programa faz isso para você. Copie sua tabela para o campo de cima e instantaneamente a versão convertida estará disponível no campo de baixo para copiar e ser feliz.

* Copie apenas os dados. Não inclua os títulos.

![Imagem provando que funciona](https://github.com/DasGeist/GraceConverter/raw/master/out.png "Exemplo feito com o programa")


Tabela para testes:

| X | Y |
| --- | --- |
| 10 ± 2 | 1 ± 10⁻³ |
| 20 ± 4  |  2 ± 10⁻³ |
| 5 ± 1 | 5 \* 10⁻¹ ± 10⁻³ |
| 10⁴ ± 2 \* 10³ | 10³ ± 10⁻³ |
| 5 \* 10⁻² ± 10⁻³ | 5 \* 10⁻³ ± 10⁻³ |

Quando copiada, o resultado é 

>10 ± 2 	1 ± 10⁻³<br>
>20 ± 4 	2 ± 10⁻³<br>
>5 ± 1 	5 * 10⁻¹ ± 10⁻³<br>
>10⁴ ± 2 * 10³ 	10³ ± 10⁻³<br>
>5 * 10⁻² ± 10⁻³ 	5 * 10⁻³ ± 10⁻³<br>

Para facilitar o processamento, só precisamos separar cada item (\[alguma coisa\] ± \[outra coisa\])em uma linha, ou seja

>10 ± 2 	<br>1 ± 10⁻³<br>
>20 ± 4 	<br>2 ± 10⁻³<br>
>5 ± 1 	<br>5 * 10⁻¹ ± 10⁻³<br>
>10⁴ ± 2 * 10³ 	<br>10³ ± 10⁻³<br>
>5 * 10⁻² ± 10⁻³ 	<br>5 * 10⁻³ ± 10⁻³<br>

Pronto. Agora é só colar no programa.
