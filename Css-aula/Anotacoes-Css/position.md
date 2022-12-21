# Position

<position> = DataType(valores).


Representa um conjunto de coordenadas 2D:
- top, right, bottom, left e center

* Usado para alguns tipos de propriedades como o background-position.
  
* Não confundir com a propriedade `position`;

🖥️Exemplo:
-------------------------------------------------------------------------

```html
    <!--Estilo-->
    <style>
        .box {
                 width:  300px;
                 height: 300px;
                 background-repeat: no-repeat;
                 background-image: url(http://source.unsplash.com/random);
                 background-position: right 50px;
            }
    </style>

    <!--Caixa-->
    <div class="box">

    </div>

```

* O exemplo acima mostra o uso do Datatype<position > dentro da propriedade "background-position", com os seguintes valores "right 50px", direcionando a imagem;