# La-Biodiversidad
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biodiversidad</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #e9f5e9;
            color: #333;
            padding: 20px;
        }
        h1 {
            color: #4CAF50;
        }
        #moreInfo {
            display: none;
            margin-top: 20px;
            border: 1px solid #4CAF50;
            padding: 10px;
            background-color: #f1f1f1;
        }
        img {
            max-width: 100%;
            height: auto;
            border: 2px solid #4CAF50;
            margin-top: 10px;
        }
        ul {
            margin: 10px 0;
            padding-left: 20px;
        }
    </style>
</head>
<body>

    <h1>La Biodiversidad: Un Patrimonio Natural</h1>
    <p>
        La biodiversidad es la variedad de vida en la Tierra, que incluye la diversidad de especies, 
        la diversidad genética y la diversidad de ecosistemas. Este patrimonio natural es esencial para 
        el equilibrio de nuestro planeta y la supervivencia de todos los seres vivos.
    </p>
    <img src="https://example.com/imagen1.jpg" alt="Diversidad de especies">

    <button onclick="showMoreInfo()">Mostrar más información</button>
    
    <div id="moreInfo">
        <h2>Importancia de la Biodiversidad</h2>
        <p>
            La biodiversidad es vital por diversas razones:
        </p>
        <ul>
            <li><strong>Recursos Naturales:</strong> Proporciona alimentos, medicinas y materiales.</li>
            <li><strong>Estabilidad de Ecosistemas:</strong> Mantiene el equilibrio de los ecosistemas.</li>
            <li><strong>Adaptación y Resiliencia:</strong> Ayuda a los ecosistemas a adaptarse a los cambios.</li>
        </ul>
        <img src="https://example.com/imagen2.jpg" alt="Ecosistemas diversos">

        <h3>Tipos de Biodiversidad</h3>
        <p>
            Existen tres niveles principales de biodiversidad:
        </p>
        <ul>
            <li><strong>Diversidad de especies:</strong> Se refiere a la variedad de especies en un ecosistema.</li>
            <li><strong>Diversidad genética:</strong> Variedad de genes dentro de una misma especie.</li>
            <li><strong>Diversidad de ecosistemas:</strong> Diferentes hábitats y comunidades en un área determinada.</li>
        </ul>

        <h3>Amenazas a la Biodiversidad</h3>
        <p>
            La biodiversidad enfrenta varias amenazas, entre ellas:
        </p>
        <ul>
            <li><strong>Deforestación:</strong> La tala de árboles reduce el hábitat natural de muchas especies.</li>
            <li><strong>Contaminación:</strong> Sustancias químicas afectan la salud de los ecosistemas.</li>
            <li><strong>Cambio Climático:</strong> Afecta patrones de clima y hábitats.</li>
            <li><strong>Especies Invasoras:</strong> Especies no nativas que desplazan a las nativas.</li>
        </ul>
        <img src="https://example.com/imagen3.jpg" alt="Amenazas a la biodiversidad">

        <h3>Conservación de la Biodiversidad</h3>
        <p>
            La conservación de la biodiversidad es esencial para el futuro del planeta. Algunas estrategias incluyen:
        </p>
        <ul>
            <li><strong>Creación de Áreas Protegidas:</strong> Reservas y parques nacionales para proteger hábitats.</li>
            <li><strong>Restauración de Ecosistemas:</strong> Recuperar áreas degradadas mediante reforestación y rehabilitación.</li>
            <li><strong>Educación y Conciencia:</strong> Informar a la población sobre la importancia de la biodiversidad.</li>
        </ul>

        <h3>Acciones Personales para Proteger la Biodiversidad</h3>
        <p>
            Todos podemos contribuir a la conservación de la biodiversidad:
        </p>
        <ul>
            <li>Reducir el uso de plásticos y reciclar.</li>
            <li>Apoyar productos sostenibles y de comercio justo.</li>
            <li>Participar en programas de reforestación y limpieza de ecosistemas.</li>
        </ul>
    </div>

    <script>
        function showMoreInfo() {
            const moreInfo = document.getElementById('moreInfo');
            if (moreInfo.style.display === 'none' || moreInfo.style.display === '') {
                moreInfo.style.display = 'block';
            } else {
                moreInfo.style.display = 'none';
            }
        }
    </script>

</body>
</html>
