## Porcentagem css

As porcentagens são valores bem flexíveis
Em muitos casos é tratado da mesma maneira que as distâncias <length>
Sempre será relativo a algum valor

🖥️ Exemplo:
---------------------------------------------------------------------

```html
    <!--Estilo-->
    <style>
        li {
            font-size: 80px;
        }
    </style>
    <!--Listas-->
    <ul>
	<li>One</li>
	<li>Two</li>
	<li>Three
		<ul>
			<li>Three A</li>
			<li>Three B</li>
			<ul>
				<li>Three B 2</li>
			</ul>
		</ul>
	</li>
</ul>
```
 * Acima existe 3 lista uma dentro da outra, e temos a tag "style" para a estilizacao, bom o valor de comprimento 
  %(porcentagem) segue uma hierarquia, ele pegara a referencia de tamanho da tag acima da tag selecionada, no exemplo acima a primeira lista esta pegando a referencia de tamanho no caso a "font-size" da propria pagina html = 16px (definido pelo proprio navegador), acima esta definido que sera 80%, ou seja a primeira lista pegara 80% de 16px, que em seguida a segunda lista dentro da primeira lista pegara 80% dos 80% pego dos 16px da propria pagina, e assim sucessivamente.