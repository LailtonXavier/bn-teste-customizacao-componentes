
# bn-teste-customizacao-componentes

### Teste 
- ja que usei apenas CSS e flexbox, não vi dificuldades, abaixo explico com mais 
- criei outra arquivo CSS para não deixar meu HTML "sujo".

detalhes o desenvolvimento.
	
	creio que sejam erros: 

	linha: 131 e 136
	- temos duas classe do mesmo nome, quando acrescento uma estilização a um, 
	tambem pega na outra, com isso inteferindo de uma boa manuseamento  do elemento
	- acrescentei uma classe = center-porcent
		e para corrigir a posição centralizando, acrescentei uma classe = center-porcent-down

	- talves outro erro na classe: <div class="beon-showcase__item-badges"> </div>
	- essa classe referenciava o local da porcentagem (linha 129)
	-  essa div esta vazia (linha 418, 481, 544, 596) , excluirei pois não estou usando

	- muita classe esta chocando com outra (esta dentro de outra div, com isso impedindo 
	uma boa estilização) (linhas: 129, 130 e 135)


	- acrescentei uma classe= corect, para corrigir o quarto e ultimo produto, pois o 
	botao de 'ver mais betalhes', não estava centralizado.
