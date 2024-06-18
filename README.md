# PROYECTO DE MI BOUTIQUE
En este proyecto lo que podras lograr es poder agregar productos, editar y eliminar. Solo podras ver la estructura por si quieres editar o lo que llegues a gustar. 
aqui te dejo algunos de mis codigos para que puedas checar.
* {
	font-family: sans-serif;
}

body {
	background-color: #fcfcfc;
	margin: 0;
	padding: 0;
	height: 100vh;
	width: 100%;
	display: flex;
}

header {
	display: flex;
	flex-direction: column;
	height: 100%;
	width: 160px;
	margin-bottom: 2.5em;
	background-color: #c5c5c5;
}

.pirncipal {
	width: 100%;
}

h2 {
	margin-left: 30px;
}

img {
	width: auto;
	height: 150px;

}

input[type="submit"],
button {
	font-size: 14px;
	text-align: center;
	width: 120px;
	background-color: #000000;
	color: #ffffff;
	padding: 6px 10px;
	border-radius: 30em;
	text-decoration: none;
	cursor: pointer;
	overflow: hidden;
	border: none;
	box-shadow: 6px 6px 12px #c5c5c5;
	position: relative;
	z-index: 1;
}

hr {
	width: 96%;
}

a {
	text-decoration: none;
}

.contenedor_productos {
	float: left;
	min-height: 287px;
	background: #c5c5c5;
	position: relative;
	margin: 1%;
	box-shadow: 2px 2px 2px 1px rgba(0, 0, 0, 0.2);
	border-radius: 5px;
	text-align: center;
	padding: 20px 40px;
	margin-bottom: 4%;
	max-width: 248px;
}

.contenedor_general {
	display: grid;
	grid-template-columns: repeat(4, 1fr);
	width: 80%;
	text-align: center;
	margin: 0 auto;
}

.imagen_peque {
	width: 50px;
	height: auto;
	border-radius: 30%;
	border: #E0E0E0 1px solid;
	padding: 5px;
	vertical-align: middle;
	margin-right: 14px;
}



input[type="text"] {
	min-width: 50px;
	height: 30px;
	font-size: 18px;
	margin-right: 10px;
	margin-top: 5px;
}

.name {
	max-width: 200px!important;
	margin-right: 0!important;
	margin-top: 0!important;
}

.inner-car {
	display: flex;
	justify-content: center;
	align-items: center;
	flex-direction: column;
	margin-top: 5px;
	height: 100vh;
	width: 100%;
	height: auto;
	padding: 1em 0 0 0;
}

.inner-car i {
	margin: 0 20px;
}

.uil {
	transform: scale(2.5);
}

.pagar {
	width: 100%;
	height: 2em;
	display: flex;
	justify-content: center;
	align-items: center;
	margin: 8px 0 0;
}

.pagar a {
	text-align: center;
	background: transparent;
	border: none;
	color: #000;
	text-decoration: none;
}

.inner-cart {
	overflow: auto;
	border: 1px solid black;
	box-sizing: border-box;
	position: absolute;
	transform: translate(-4em, -4em);
	z-index: 100;
	border: 1px solid black;
	background-color: rgb(197, 196, 196);
	width: 340px;
	max-height: 510px;
	font-size: 16px;
	font-weight: 700;
	border-radius: 10px;
	padding: 20px;
}


.producto {
	display: flex;
	justify-content: center;
	align-items: center;
	max-width: 325px;
}

.pro-img {
	display: flex;
	flex-direction: column;
}

.info {
	display: flex;
}

#title-cart {
	font-size: 25px;
}

.cart i {
	transition: transform .25s ease;
	margin-bottom: 2em;
}

.cart i:hover {
	transform: scale(3);
}

.add {
	display: flex;
	justify-content: center;
	align-items: center;
}

.add i {
	transition: transform .25s ease;
}

.add:hover {
	i {
		transform: scale(3);
	}
}

/*-----Modal----*/

.container-modal {
    width: 100%;
    height: 100vh;
    position: fixed;
    top: 0;
    left: 0;
    background-color: hsla(0, 0%, 29%, 0.808);
    display: flex;
    justify-content: center;
    align-items: center;
    z-index: 100;
}

.content-modal {
	display: flex;
	justify-content: center;
	align-items: center;
    width: 100%;
    max-width: 800px;
    padding: 20px;
    background-color: transparent;
    border-radius: 4px;
    color: #2b2b2b;
}

.content-modal h2 {
    margin-bottom: 15px;
}

.cerrar-modal {
    width: 100%;
    height: 100vh;
    position: absolute;
    top: 0;
    left: 0;
    z-index: -1;
}

.productos_modal {
	float: none;
	min-height: 220px;
}
/*------*/
.hidden {
	display: none!important;
}

.FormCajaLogin {
    width: 100%;
    height: 100%;
    display: grid;
	place-content: center;
    background: rgb(0, 0, 0);
    background: radial-gradient(circle, rgba(0, 0, 0, 1) 0%, rgba(23, 0, 0, 1) 10%, rgba(45, 0, 0, 1) 20%, rgba(68, 0, 0, 1) 30%, rgba(90, 0, 0, 1) 40%, rgba(113, 0, 0, 1) 50%, rgba(135, 0, 0, 1) 60%, rgba(158, 0, 0, 1) 70%, rgba(180, 0, 0, 1) 80%, rgba(203, 0, 0, 1) 90%, rgba(255, 0, 0, 1) 100%);
}

.grupo-entradas {
    position: absolute;
    display: grid;
    width: 100%;
    transition: .5s;
}

.FormLogin {
    background-color: #f2f2f2;
    margin: auto auto auto auto;
    border-radius: 6px;
    color: #000;
    border: 0.1em solid black;
    width: 400px;
    height: 400px;
    position: relative;
    padding: 2px;
    overflow: hidden;
}

.TextoCajas {
    font-weight: bold;
    margin-top: 4%;
    margin-bottom: 4%;
    color: #000;
    text-align: left;
}

.CajaTexto {
    width: 80%;
    padding: 10px;
    font-size: 1em;
    border-radius: 5px;
    border: 1px solid black;
    color: black;
}

.BtnRegistrar {
    width: 80%;
    text-decoration: none;
    padding: 10px 30px;
    cursor: pointer;
    border: 0;
    border-radius: 10px;
    border: 1px solid black;
    font-size: 18px;
    color: white;
    background-color: green;
    font-weight: bold;
    margin-bottom: 5%;
    margin-top: 7%;
}

div .BtnLogin {
    width: 80%;
    text-decoration: none;
    padding: 10px 30px;
    cursor: pointer;
    border: 0;
    border-radius: 10px;
    border: 1px solid black;
    font-size: 18px;
    color: white;
    background-color: #000;
    font-weight: bold;
    margin-top: 7%;
    margin-bottom: 5%;
}

.botondeintercambiar {
    width: 240px;
    margin: 35px auto;
    position: relative;
    box-shadow: 0 0 6px 0.5px black;
    border-radius: 30px;
}

.botoncambiarcaja {
    padding: 10px 30px;
    cursor: pointer;
    background: transparent;
    border: 0;
    outline: none;
    position: relative;
    font-weight: bold;
    font-size: 16px;
}

#btnvai {
    top: 0;
    left: 0;
    position: absolute;
    width: 130px;
    height: 100%;
    background-color: #1C62C1;
    border-radius: 30px;
    transition: .5s;
}

#frmlogin {
    bottom: 10%;
    left: 50px;
}

#frmregistrar {
    left: 450px;
}
<?php
if (!empty($_POST['regisDatos'])) {
    require_once("./clase.php");

    $db = new DBControl();

    $name = $_POST['name'];
    $pre = $_POST['preci'];

    $rutacompleta = "./img/";
    $fileimg = opendir(".".$rutacompleta);
    if (isset($_FILES['img']) && $_FILES['img']['size'] > 0) {
        $sqlCode = "SELECT cod FROM productos ORDER BY cod DESC LIMIT 1";
        if ($result = $db->nfilas($sqlCode) > 0) {
            $result = $db->vaiQuery($sqlCode);
            $cod = $result[0]["cod"];

            $number = (int)substr($cod, 1);
            $new_number = $number + 1;
            $new_code = 'a' . str_pad($new_number, 6, '0', STR_PAD_LEFT);

            $_FILES['img']['name'] = $new_code . '.png';
        } else {
            $_FILES['img']['name'] = 'a000001.png';
            $new_code = 'a000001';
        }

        $archivo         = $_FILES['img']['tmp_name'];
        $nombrearchivo     = $_FILES['img']['name'];
        $tipoarchivo     = GetImageSize($archivo);
        // 1=>'GIF'
        // 2=>'JPEG'
        // 3=>'PNG'	

        if (!move_uploaded_file($archivo, ".".$rutacompleta . $nombrearchivo)) {
            echo "<script> alert('Error.\\nNo se ha podido cargar el archivo.');</script>";
        }

        $code = $new_code;
        $img     = $rutacompleta . $_FILES['img']['name'];
        $sql = "INSERT INTO productos (cod, nom, pre, img) VALUES ('$code', '$name', '$pre', '$img')";

        $db->query($sql);
    } else {

    }

    // Consulta para actualizar la tabla


    // validar si la consulta dio un resultado

    // Cerrar la conexion
    $db->close();

    echo "<script>window.location.href = 'index.php'</script>";
}
