# mundo-gatos
primero
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Todo sobre los Gatos</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #f5f5f5;
            color: #333;
        }

        header {
            background-color: #ffcc80;
            padding: 15px;
            text-align: center;
        }

        nav button {
            background: none;
            border: none;
            font-size: 16px;
            font-weight: bold;
            margin: 0 15px;
            cursor: pointer;
            color: #333;
        }

        nav button:hover { color: #e65100; }

        section {
            display: none;
            max-width: 1000px;
            margin: 30px auto;
            background: white;
            padding: 25px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            line-height: 1.6;
        }

        section.active { display: block; }

        h2 { color: #e65100; }

        .imagenes {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin-top: 15px;
        }

        .imagenes img {
            width: 32%;
            border-radius: 8px;
            height: 200px;
            object-fit: cover;
        }

        footer {
            text-align: center;
            padding: 15px;
            background-color: #ffcc80;
            margin-top: 40px;
        }
    </style>
</head>
<body>

<header>
    <h1>Todo sobre los Gatos 🐱</h1>
    <nav>
        <button onclick="mostrarSeccion('inicio')">Inicio</button>
        <button onclick="mostrarSeccion('info')">Información General</button>
        <button onclick="mostrarSeccion('cuidados')">Cuidados Básicos</button>
        <button onclick="mostrarSeccion('comportamiento')">Comportamiento</button>
        <button onclick="mostrarSeccion('alimentacion')">Alimentación</button>
    </nav>
</header>

<section id="inicio" class="active">
    <h2>Bienvenido al mundo felino</h2>
    <p>Los gatos han acompañado al ser humano durante miles de años. Son animales independientes, elegantes y muy inteligentes, capaces de crear fuertes lazos con sus dueños.</p>
    <p>En esta página descubrirás información importante sobre su vida, cómo cuidarlos, entender su comportamiento y brindarles la alimentación adecuada para que vivan felices y saludables.</p>
    <div class="imagenes">
        <img src="https://images.unsplash.com/photo-1518791841217-8f162f1e1131">
        <img src="https://images.unsplash.com/photo-1574158622682-e40e69881006">
        <img src="https://images.unsplash.com/photo-1543852786-1cf6624b9987">
    </div>
</section>

<section id="info">
    <h2>Información General</h2>
    <p>El gato doméstico es un mamífero carnívoro que pertenece a la familia de los felinos. Es conocido por su agilidad, equilibrio y capacidad para moverse sigilosamente.</p>
    <p>Su esperanza de vida suele estar entre los 12 y 18 años, aunque con buenos cuidados pueden superar esa edad. Poseen una visión nocturna excelente y un oído muy sensible.</p>
    <p>Los gatos duermen muchas horas al día porque conservan energía como instinto natural de caza. También son animales territoriales y marcan su espacio mediante olores y comportamientos específicos.</p>
    <div class="imagenes">
        <img src="https://images.unsplash.com/photo-1495360010541-f48722b34f7d">
        <img src="https://images.unsplash.com/photo-1511044568932-338cba0ad803">
        <img src="https://images.unsplash.com/photo-1519052537078-e6302a4968d4">
    </div>
</section>

<section id="cuidados">
    <h2>Cuidados Básicos</h2>
    <p>El bienestar de un gato depende de la atención que reciba diariamente. No solo necesitan comida, sino también higiene, afecto y atención médica.</p>
    <ul>
        <li><strong>Salud:</strong> Llevarlo al veterinario al menos una vez al año.</li>
        <li><strong>Vacunas:</strong> Mantener su calendario de vacunación al día.</li>
        <li><strong>Higiene:</strong> Limpiar su arenero diariamente y cepillar su pelaje.</li>
        <li><strong>Ambiente:</strong> Espacios tranquilos, cama cómoda y rascadores.</li>
        <li><strong>Estimulación:</strong> Juegos diarios para evitar el estrés y el aburrimiento.</li>
    </ul>
    <div class="imagenes">
        <img src="https://images.unsplash.com/photo-1555685812-4b943f1cb0eb">
        <img src="https://images.unsplash.com/photo-1595433562696-1f4b0dbe9cbe">
        <img src="https://images.unsplash.com/photo-1507149833265-60c372daea22">
    </div>
</section>

<section id="comportamiento">
    <h2>Comportamiento</h2>
    <p>Los gatos utilizan el lenguaje corporal para comunicarse. Una cola erguida suele indicar felicidad, mientras que orejas hacia atrás pueden mostrar miedo o molestia.</p>
    <p>El ronroneo generalmente significa que el gato está relajado, aunque también puede aparecer cuando siente dolor como mecanismo de calma.</p>
    <p>Es normal que rasquen superficies, ya que esto mantiene sus uñas sanas y marca territorio. También disfrutan trepar y observar desde lugares altos.</p>
    <div class="imagenes">
        <img src="https://images.unsplash.com/photo-1526336024174-e58f5cdd8e13">
        <img src="https://images.unsplash.com/photo-1517457373958-b7bdd4587205">
        <img src="https://images.unsplash.com/photo-1517849845537-4d257902454a">
    </div>
</section>

<section id="alimentacion">
    <h2>Alimentación</h2>
    <p>Los gatos son carnívoros obligados, por lo que necesitan proteínas animales para mantenerse sanos. Existen alimentos secos y húmedos especialmente formulados para sus necesidades.</p>
    <p>La cantidad de comida depende de su edad, peso y nivel de actividad. Es importante evitar la sobrealimentación para prevenir la obesidad.</p>
    <p><strong>Alimentos prohibidos:</strong> chocolate, cebolla, ajo, uvas, pasas y huesos cocidos.</p>
    <p>El agua fresca debe estar siempre disponible, ya que muchos gatos no beben suficiente y pueden desarrollar problemas urinarios.</p>
    <div class="imagenes">
        <img src="https://images.unsplash.com/photo-1583511655857-d19b40a7a54e">
        <img src="https://images.unsplash.com/photo-1568640347023-a616a30bc3bd">
        <img src="https://images.unsplash.com/photo-1518717758536-85ae29035b6d">
    </div>
</section>

<footer>
    Tenencia responsable de mascotas • © 2026
</footer>

<script>
function mostrarSeccion(id) {
    document.querySelectorAll("section").forEach(sec => sec.classList.remove("active"));
    document.getElementById(id).classList.add("active");
}
</script>

</body>
</html>
