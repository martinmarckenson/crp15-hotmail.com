OCTYPE html>
<!--
To change this license header, choose License Headers in Project Properties.
To change this template file, choose Tools | Templates
and open the template in the editor.
-->
<html>
    <head>
        <title>contacts</title>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel='stylesheet' type='text/css' href=css/estilos.css>
    </head>
    <body>
        <div id="cabecera">
            <div id="menu">
            <ul>
            <li><a href="index.html">Find a Hotel</a></li>
            <li>Plan an Event</li>
            <li>Residences</li>
            <li>Contacts</li>
            </ul>
                </div>
            </div>
            <h1>Formulario de contacto</h1>
            <form>
                <div>
                <label for='nombre'>Your Name</label>
                <input type='text' id='nombre'/>
                </div>
                
                <div>
                <label for='Telefono'>Phone</label>
                <input type='text' id='telefono'/>
                </div>
                
                <div>
                <label for='correo'>Email</label>
                <input type='text' id='Correo'/>
                </div>
                
                <div id="select">
                <label for="so">What you need?</label> <br/>
                <select id="so" name="so">
                <option value="" selected="selected">- Choose -</option>
                <option value="Help">Help</option>
                <option value="Find us">Find us</option>
                <option value="Feedback">Feedback</option>
                <option value="Other">Other</option>
                </select>
                
                </div>
                
                  <div>
                <label for='asunto'>Observation:</label>
                  <textarea id='asunto' cols='50' rows='10'></textarea>
                </div>
                <div>
                <button type='submit'> Enviar</button>
                </div>
                
            </form>
     <div id="pie">
            USA and Canada only - Four Seasons Reservations
            +1 (8099459456).</br>
            <img src="imagenes/img2.png"/>
            <img src="imagenes/img3.png" />
            <img src="imagenes/img4.png"/>
        </div>
    </body>
</html>

