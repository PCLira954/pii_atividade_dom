1) O que é o DOM e a que ele se aplica
DOM (Document Object Model) é a interface de programação para documentos HTML e XML. Ele representa a página para que programas possam alterar a estrutura do documento, seu estilo e conteúdo.

Principais conceitos:

Cada elemento HTML é representado como um nó (node).

Podemos acessar, modificar, adicionar ou remover esses nós usando JavaScript.

5) Diferença entre textContent, innerText e innerHTML

textContent: Retorna todo o texto, incluindo elementos escondidos. Ex:	element.textContent = "Olá!"
innerText :	Retorna texto visível (considera CSS).	Ex: element.innerText = "Olá!"
innerHTML	: Retorna/define o HTML interno.	Ex: element.innerHTML = "<b>Olá!</b>"
