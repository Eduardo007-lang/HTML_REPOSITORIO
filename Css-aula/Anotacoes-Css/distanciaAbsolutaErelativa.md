## Distancia absolutas <length>

Sao fixas e nao alteram o seu valor

  Unidade  | Nome                | Equivalência         |
|----------|---------------------|----------------------|
| cm       | Centímetros         | 1cm = 96px/2.54      | 
| in       | Inches (polegadas)  | 1in = 2.54cm = 96px  | 
| px       | Pixels              | 1px = 1/96th of 1in  | 

* O mais comum usado e a unidade de pixel(px);

## Distancia Relativa <length>

São relativas a um outro valor, pode ser o elemento pai, ou root, ou o tamanho da tela.
Benefício: Maior adaptação aos diferentes tipos de tela.

| Unidade  | Relativo a                                    |
|----------|-----------------------------------------------|
| em       | Tamanho da font do elemento pai               |
| rem      | Tamanho da font do elemento raiz (root/html)  | 
| vw       | 1% da viewport wid                            |  
| vh       | 1% da viewport height                         |

* Normalmente o tamanho da font padrão do navegador é de 16px e para mudar esse valor temos que fazer a alteração no root ou no elemento html.

* Caso o "em" nao encontra o elemento pai(o elemento acima do elemento selecionado) sera usado o elemento raiz da pagina como referencia.

* Exemplo: 

```css
    :root {
        font-size: 18px;
    }
    /* OU */

    html {
        font-size: 14px;
    }
```
