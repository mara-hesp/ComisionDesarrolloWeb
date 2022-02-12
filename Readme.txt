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


- Se agrega SEO:
	*index.html
<title>LiteHome | Ilumina tus espacios</title>
<meta name="description" content="Compra lámparas e ilumina tus espacios. Promociones y envíos a domicilio">
<meta name="keywords" content="LÁMPARAS, DECORACIÓN, HOGAR, ILUMINACIÓN">

	*productos.html
<title>Productos | LiteHome</title>
<meta name="description" content="Busca las mejores lámparas por categorías o por espacios.">
<meta name="keywords" content="LÁMPARAS, DECORACIÓN, HOGAR, ILUMINACIÓN, TECHO, COLGANTES, PARED, EXTERIOR, PISO, MESA, ESCRITORIO, ESPACIOS, COCINA, COMEDOR, RECÁMARA, BAÑO">

	*soluciones.html
<title>Soluciones | LiteHome</title>
<meta name="description" content="Ilumina proyectos arquitectónicos, centro de distribución a empresas, venta al público en general">
<meta name="keywords" content="LÁMPARAS, DECORACIÓN, HOGAR, ILUMINACIÓN, SOLUCIONES, PROYECTOS, DISTRIBUCIÓN, B2B, B2C">

	*nosotros.html
<title>Nosotros | LiteHome</title>
<meta name="description" content="Conoce nuestra historia y al equipo de LiteHome">
<meta name="keywords" content="LÁMPARAS, HISTORIA, EQUIPO">

	*contacto.html
<title>Contacto | LiteHome</title>
<meta name="description" content="Ponte en contacto con nosotros">
<meta name="keywords" content="CONTACTO, MENSAJE, DIRECCIÓN">
