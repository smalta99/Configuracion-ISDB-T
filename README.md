!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Configuración ISDB-T</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Configuración de Parámetros ISDB-T</h1>
        <form id="config-form">
            <div class="general-settings">
                <h2>Configuración General</h2>
                <label for="guardInterval">Tiempo de Guarda:</label>
                <select id="guardInterval" name="guardInterval" required>
                    <option value="1/4">1/4</option>
                    <option value="1/8">1/8</option>
                    <option value="1/16">1/16</option>
                    <option value="1/32">1/32</option>
                </select>
            </div>
            <div class="layer">
                <h2>Capa 1</h2>
                <label for="segments1">Número de Segmentos:</label>
                <input type="number" id="segments1" name="segments1" required>
                
                <label for="modulation1">Modulación:</label>
                <select id="modulation1" name="modulation1" required>
                    <option value="qpsk">QPSK</option>
                    <option value="16qam">16-QAM</option>
                    <option value="64qam">64-QAM</option>
                </select>

                <label for="codeRate1">Tasa de Código:</label>
                <select id="codeRate1" name="codeRate1" required>
                    <option value="1/2">1/2</option>
                    <option value="2/3">2/3</option>
                    <option value="3/4">3/4</option>
                    <option value="5/6">5/6</option>
                    <option value="7/8">7/8</option>
                </select>
            </div>
            <div class="layer">
                <h2>Capa 2</h2>
                <label for="segments2">Número de Segmentos:</label>
                <input type="number" id="segments2" name="segments2" required>
                
                <label for="modulation2">Modulación:</label>
                <select id="modulation2" name="modulation2" required>
                    <option value="qpsk">QPSK</option>
                    <option value="16qam">16-QAM</option>
                    <option value="64qam">64-QAM</option>
                </select>

                <label for="codeRate2">Tasa de Código:</label>
                <select id="codeRate2" name="codeRate2" required>
                    <option value="1/2">1/2</option>
                    <option value="2/3">2/3</option>
                    <option value="3/4">3/4</option>
                    <option value="5/6">5/6</option>
                    <option value="7/8">7/8</option>
                </select>
            </div>
            <div class="layer">
                <h2>Capa 3</h2>
                <label for="segments3">Número de Segmentos:</label>
                <input type="number" id="segments3" name="segments3" required>
                
                <label for="modulation3">Modulación:</label>
                <select id="modulation3" name="modulation3" required>
                    <option value="qpsk">QPSK</option>
                    <option value="16qam">16-QAM</option>
                    <option value="64qam">64-QAM</option>
                </select>

                <label for="codeRate3">Tasa de Código:</label>
                <select id="codeRate3" name="codeRate3" required>
                    <option value="1/2">1/2</option>
                    <option value="2/3">2/3</option>
                    <option value="3/4">3/4</option>
                    <option value="5/6">5/6</option>
                    <option value="7/8">7/8</option>
                </select>
            </div>
            <button type="submit">Guardar Configuración</button>
        </form>

        <div id="result">
            <h2>Resultado de la Configuración</h2>
        </div>
    </div>

    <script src="scripts.js"></script>
</body>
</html>
