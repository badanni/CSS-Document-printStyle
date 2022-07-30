# CSS Document printStyle
 CSS hoja con borde, pie de pagina y cabecera para imprimir

## Licencia
[Licencia CC-BY](https://creativecommons.org/licenses/by/4.0/deed.es)

## Uso
tag section continene la forma de la hoja
```
<section class="pagina"> <-- Crear la hoja con borde para imprimir
    <header nivel="INTERNO" formato="FAB01-01 rev 2">contenido</header> <-- Cabecera 1 linea
    <h1>Soy un titulo ejemplo</h1>
    <p>hola hola hola hola hola hola hola hola hola  hola</p>
    <figure>
        <img src="./prueba/src/logo.svg" alt="hola">
        <figcaption>hola</figcaption>
    </figure>
    <footer>Documento controlado, prohibida su reproducción parcial o total sin autorización</footer> <-- Pie de una pagina agrega numero de pagina.
</section> 
```