# Cap. 05 - Baby Steps

Descrição sobre a natureza modal do VIM

* **INSERÇÃO**: digitar coisas.
* **NORMAL**: pequenas alterações e navegar pelo texto.
* **VISUAL**: quando queremos — por alguma razão — selecionar texto.

Ao apertarmos a tecla *w*:

* **INSERÇÃO**: insere o caractere *w*(capitão óbvio).
* **NORMAL**: move o cursor para o **início** da próxima palavra.
* **VISUAL**: equivalente ao movimento do modo normal, porém seleciona o texto no processo.

## Movimentos básicos do modo normal

hjkl
movimentos(em ordem): esquerda, baixo, cima, direita.

* Entrar no insert mode: *i*
* Voltar ao modo normal: *\<ESC>*, \<Ctrl-C> ou \<Ctrl-[>

## A questão de copiar com Ctrl-C

No modo VIM, Ctrl-C faz com que saiamos do modo de inserção. Então como copiamos texto?
Resposta: *y* (*yank*)

### E para colar?

Ctrl-V nos envia para o modo de *Visualização de block*. No VIM, usados o *paste* do vim (*p*).

## Buscando texto

Esquecer o *Ctrl-F* para buscar texto. Aqui usamos, no modo *normal*, `/\<Termo-a-ser-procurado>
