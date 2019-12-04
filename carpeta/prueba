<html>
    <head>
        <meta charset="UTF-8">
        <title></title>
    </head>
    <body>
        <form method="post" name="form">
            <p>
            <input type="radio" name="boton" value="botón 1">Opción 1<br>
            <input type="radio" name="boton" value="2">Opción 2<br>
            <input type="radio" name="boton" value="3">Opción 3<br>
            <input type="submit" name="ok" value="Enviar">
            </p>
        </form>
        <?php
            //Esto muestra 3 botones radio y te dice qué botón has seleccionado
            if (isset($_POST["ok"])){
                $respuesta=$_POST["boton"];//Guarda lo que ponga en "value" del botón marcado
                echo "<p>La opción escogida es  $respuesta</p>";
            }
            // put your code here
        ?>
    </body>
</html>
