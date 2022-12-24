## prática de estudos javascript-DOM

### anotações
- comportamento de um formulário;
- DOM (Document Object Model);
- document.getElementById(‘id’) seleciona o elemento pelo id passado;
- document.getElementsByClassName(‘classe’) retorna um array dos elementos pelo nome da classe passada;
- document.getElementsByTagName(‘tag’) retorna um array dos elementos pelo nome da tag passada; 
- document.querySelectorAll(seletor) devolve todos os seletores com o mesmo nome; 
- data-attributes (atributo data-nome-nome) separar responsabilidades entre JS e CSS;
- arrow function ()=>{};
- método para escutar eventos no elemento: nomeVariavel.addEventListener; 
- criar elemento no DOM: nomeVariavel = document.createElement(‘li’); 
- anexar um elementro dentro do outro (elemento filho dentro do elemento pai): nomeVariavel.innerHTML = nomeVariavel + nomeVariavel.appendChild(nomeVariavel);
- IIFE (Immediately Invoked Funtion Expression);
- adicionar classe CSS utilizando o método toggle;
- atributo parentElement para subir um elemento na árvore do DOM; 
- encontrar o alvo do evento utilizando a propriedade target;
- componentes começa com letra maiúscula, import / export, proteger o código;