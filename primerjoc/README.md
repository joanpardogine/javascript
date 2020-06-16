# Creació d'un joca amb JavaScript pas a pas

## Creació de la tela (canvas) de joc

1. Crear un fitxer anomenat [index.html](pasos/index_0001.html) amb el següent contingut.

```html
<canvas id="tela" width="500" height="500" style="border: 5px solid black;"></canvas>
```

### Explicació

Es crea un objecte del tipus [**```canvas```**](https://www.w3schools.com/html/html5_canvas.asp) amb un identificador **```id="tela"```** , amb una mida de **```500 píxels```** tant d'alçada (**```height="500"```**), com d'amplada (**```width="500"```**) i un contorn continuo **```sòlid```** de color negre **```black```** i de **```5 pixels```** de gruix (**```border: 5px solid black```**).

Com pots veure, de moment, no cal escriure res més, tot el que falta, ja ho "afegirà" el navegador en carregar la pàgina.

I si obrim el fitxer **```index.html```** amb qualsevol navegador, en el nostre cas farem servir el **Chrome**, s'obté el següent resultat:
&nbsp;
----
![alt text](images/image00001.png "Fitxer index.html")
----

```html
<canvas id="tela" width="500" height="500" style="border: 5px solid black;"></canvas>
<script>
    var ctx = document.getElementById("tela").getContext("2d"); // Context => ctx
    console.log(ctx);

    ctx.fillText("Sóc aquí!",50,50);
</script>

```
