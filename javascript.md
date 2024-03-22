
1. **Manipulación del DOM**:
```javascript
// Obtener un elemento por su ID
const elemento = document.getElementById('miElemento');

// Obtener elementos por su clase
const elementos = document.getElementsByClassName('miClase');

// Obtener elementos por su etiqueta
const elementos = document.getElementsByTagName('div');

// Crear un nuevo elemento
const nuevoElemento = document.createElement('p');

// Añadir un elemento al DOM
document.body.appendChild(nuevoElemento);

// Agregar o quitar una clase a un elemento
elemento.classList.add('nuevaClase');
elemento.classList.remove('claseExistente');

// Manipular el contenido HTML de un elemento
elemento.innerHTML = 'Nuevo contenido';

// Manipular los atributos de un elemento
elemento.setAttribute('src', 'imagen.jpg');
elemento.getAttribute('src');
```

2. **Eventos**:
```javascript
// Agregar un evento a un elemento
elemento.addEventListener('click', () => {
  console.log('Se hizo clic en el elemento');
});

// Eliminar un evento de un elemento
elemento.removeEventListener('click', miFuncion);

// Evento de carga del documento
window.addEventListener('load', () => {
  console.log('El documento se ha cargado completamente');
});
```

3. **Operaciones con Arrays**:
```javascript
// Crear un array
const miArray = [1, 2, 3, 4, 5];

// Iterar sobre un array
miArray.forEach((elemento) => {
  console.log(elemento);
});

// Filtrar elementos de un array
const arrayFiltrado = miArray.filter((elemento) => {
  return elemento > 3;
});

// Mapear elementos de un array
const arrayMapeado = miArray.map((elemento) => {
  return elemento * 2;
});

// Encontrar un elemento en un array
const elementoEncontrado = miArray.find((elemento) => {
  return elemento === 3;
});
```

4. **Funciones de Temporización**:
```javascript
// Ejecutar una función después de un cierto tiempo
setTimeout(() => {
  console.log('Han pasado 3 segundos');
}, 3000);

// Ejecutar una función periódicamente
setInterval(() => {
  console.log('Se ejecuta cada segundo');
}, 1000);
```

y backend 


1. **Node.js Core Modules**:
```javascript
// Importar módulos del core de Node.js
const fs = require('fs'); // Módulo para manejar el sistema de archivos
const http = require('http'); // Módulo para crear un servidor HTTP
const path = require('path'); // Módulo para manejar rutas de archivos
const os = require('os'); // Módulo para obtener información del sistema operativo
```

2. **Crear un Servidor HTTP**:
```javascript
// Crear un servidor HTTP básico
const servidor = http.createServer((req, res) => {
  res.writeHead(200, {'Content-Type': 'text/html'});
  res.end('¡Hola Mundo desde Node.js!');
});

// Escuchar en un puerto específico
const puerto = 3000;
servidor.listen(puerto, () => {
  console.log(`Servidor en ejecución en el puerto ${puerto}`);
});
```

3. **Gestión de Archivos**:
```javascript
// Leer un archivo de manera asíncrona
fs.readFile('archivo.txt', 'utf8', (err, data) => {
  if (err) throw err;
  console.log(data);
});

// Escribir en un archivo de manera asíncrona
fs.writeFile('nuevoArchivo.txt', 'Contenido del nuevo archivo', (err) => {
  if (err) throw err;
  console.log('Archivo creado exitosamente');
});
```

4. **Módulos de terceros (NPM)**:
```javascript
// Instalar un módulo de terceros (por ejemplo, Express)
// npm install express

// Importar el módulo Express
const express = require('express');

// Crear una instancia de Express
const app = express();

// Definir una ruta
app.get('/', (req, res) => {
  res.send('¡Hola Mundo desde Express!');
});

// Escuchar en un puerto específico
const puerto = 3000;
app.listen(puerto, () => {
  console.log(`Servidor Express en ejecución en el puerto ${puerto}`);
});
```

5. **Manejo de Solicitudes y Respuestas HTTP**:
```javascript
// Manejar una solicitud GET con Express
app.get('/ruta', (req, res) => {
  res.send('Respuesta a la solicitud GET');
});

// Manejar una solicitud POST con Express
app.post('/ruta', (req, res) => {
  res.send('Respuesta a la solicitud POST');
});
```
