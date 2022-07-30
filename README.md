# CSS Document printStyle
 CSS hoja con borde, pie de pagina y cabecera para imprimir

## Ejemplo

```
<section class="pagina"> <-- Crear la hoja con borde para imprimir
    <header pre_izq="Nivel de acceso:" izq="INTERNO" pre_der="Formato:" der="FAB01-01 rev 2">Centro</header> <-- Cabecera 1 linea
    <h1>Soy un titulo ejemplo</h1>
    <p>hola hola hola hola hola hola hola hola hola  hola</p>
    <figure>
        <img src="./prueba/src/logo.svg" alt="hola">
        <figcaption>hola</figcaption>
    </figure>
    <footer>Izquierda</footer> <-- Pie de una pagina agrega numero de pagina en la derecha.
</section> 
<section class="pagina">
    <header izq="12">Centro</header>
    <p>hola hola hola holahola hola hola hola hola</p>
    <end>Centro</end> <-- Muestro mensaje  "-->FIN DE ARCHIVO<--"
    <footer>Izquierda</footer>
</section>
```