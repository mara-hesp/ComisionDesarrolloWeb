- Se ajusta el Herobox para el responsive.


- Se agrega el mixin en _generales.scss:
@mixin titulos {
    margin-bottom: 20px;
    text-align: center;
}

h1 {
    @include titulos;
}

h2 {
    @include titulos;
}


- Se agrega el extend en _generales.scss:
.button {
    background-color: $morado;
    border: none;
    color: white;
    margin-top: 15px;
    font-size: 1em;
}

.button-foot {
    @extend .button;
    padding: 5px 10px;
}

.button-cont {
    @extend .button;
    padding: 5px 15px;
}