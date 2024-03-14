# Análise de códigos em Javascript

### 1º Código

<a href="https://github.com/matheussantos1206/analise-codigo-js/blob/main/codigo1.html">Código 1</a>  
![](/codigo1.png)
## ``Funções JavaScript:``
> 💾 timeMsg()  
Descrição: Esta função cria um temporizador que aguarda 3 segundos antes de chamar a função alertMsg().
Uso: É chamada quando o usuário clica no link.
alertMsg():
Descrição: Esta função escreve o texto "Terminal Root" no documento.
Uso: É chamada após o temporizador de 3 segundos definido pela função timeMsg().

## ``Elementos HTML:``
> 💾 &lt;script type="text/javascript"&gt;  &lt;/script&gt;:
Descrição:
 Este bloco de código contém o JavaScript que define as funções timeMsg() e alertMsg().
&lt;a href="#" onClick="timeMsg()"&gt;  &lt;/a&gt;
Descrição: Este é um elemento de link HTML que, quando clicado, chama a função timeMsg().
Uso: O texto "Clique aqui a mensagem só aparecerá depois de 3 segundos" está visível para o usuário, e quando clicado, ele dispara a exibição da mensagem "Terminal Root" após um atraso de 3 segundos.

![](/Captura%20de%20tela%202024-03-14%20110136.png)


### 2° Código

<a href="https://github.com/matheussantos1206/analise-codigo-js/blob/main/codigo2.html">codigo2</a>
![](/codigo%202%20imagem.png)

## `` JavaScript:``

> 🖥️ Variável str:  Descrição: Esta variável armazena a string "Terminal Root". 
    Uso: A string é posteriormente modificada com a substituição da palavra "Root" por "Linux".
    str.replace():
    Descrição: Este método substitui uma substring por outra em uma string.
    Uso: É utilizado para substituir a palavra "Root" por "Linux" na string armazenada na variável str.
    document.write():

> ⌨️👨‍💻  Descrição: Este método escreve conteúdo HTML ou texto no documento.
    Uso: É usado para exibir o conteúdo da string modificada na página web.

## ``Elemento HTML:``
> 🖥️ &lt;script&gt;...&lt;/script&gt;:
    Descrição: Este bloco de código contém o JavaScript que manipula a string e escreve seu conteúdo no documento.
    Uso: O código é executado quando a página HTML é carregada, resultando na exibição da string modificada na página.