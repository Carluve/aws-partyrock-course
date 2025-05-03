# 🧠 Buenas Prácticas para el Uso de **AWS PartyRock**

<iframe width="560" height="315" src="https://www.youtube.com/embed/7Vyzb-mKZ04" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

Hola, mi nombre es **Javier Martínez** y soy instructor técnico en AWS. En esta guía vamos a hablar sobre las **buenas prácticas para el uso de PartyRock**, una potente herramienta de prototipado de aplicaciones basadas en inteligencia artificial generativa.

Este documento es un extracto instructivo de una sesión en video donde cubrimos conceptos clave, funciones útiles, y sobre todo, recomendaciones para construir aplicaciones efectivas, creativas y funcionales usando PartyRock.

---

## 🎉 ¿Qué es PartyRock?

**PartyRock** es una plataforma que permite a cualquier usuario, sin necesidad de conocimientos profundos de programación, **aprender y practicar con inteligencia artificial generativa** a través de la creación de aplicaciones interactivas.

### Puedes pensar en PartyRock como:

- 🧪 Un entorno para **experimentar y construir prototipos de aplicaciones**.
- 🤖 Un laboratorio para **aprender sobre IA generativa** mediante la práctica.
- ⚡ Una forma divertida y accesible de **familiarizarse con modelos de IA** como los que ofrece Amazon Bedrock.

---

## 🧰 Crear una Aplicación: Primeros Pasos

1. Haz clic en el botón **“Generar una aplicación”**.
2. Escribe lo que deseas construir. Ejemplo:

   ```
   Quiero una app que genere resúmenes de libros basándose en el título, autor y notas personales. Además, quiero un chatbot para hacer preguntas sobre el contenido.
   ```

3. ¿No sabes por dónde empezar? Usa la función **“Inspírame con ejemplos”** para ver prompts de inspiración.

---

## ✏️ Refinar tu Aplicación

Una vez generada tu aplicación inicial:

- Puedes modificar widgets: redimensionar, renombrar, traducir, reorganizar, etc.
- Usa el botón **"Edit"** en cada widget para cambiar su comportamiento.
- Los elementos en la pantalla son **widgets**, y se agrupan en un **canvas** de trabajo visual.

### Ejemplos de ediciones comunes:
- Cambiar títulos en inglés a español.
- Reducir espacio en blanco.
- Reorganizar campos de entrada y salida para mayor usabilidad.

---

## 🧩 Tipos de Widgets

PartyRock ofrece múltiples tipos de widgets que puedes combinar:

### 🔹 Widgets de Entrada
- **User Input**: campo de texto para que el usuario escriba.
- **Document**: permite subir archivos como `.pdf`, `.csv`, `.txt`.

### 🔸 Widgets Estáticos
- Texto informativo, instrucciones para el usuario, títulos y secciones.

### 🔹 Widgets de IA Generativa
- **Texto generado** (output textual a partir de prompts).
- **Imágenes generadas** (a partir de descripciones).
- **Chatbots** interactivos con instrucciones personalizadas.

---

## 🧠 Buenas Prácticas con Widgets de IA Generativa

### 1. Elegir el Modelo Correcto

No todos los modelos son iguales. PartyRock te permite escoger modelos de distintas capacidades:

- 🔹 **Modelos pequeños (Micro)**: ideales para tareas simples como generar facturas.
- 🔸 **Modelos avanzados (Sonnet, Claude, etc.)**: útiles para tareas más creativas o complejas.

> 💡 Consejo: Utiliza el modelo **más eficiente** posible para tu tarea. Ahorra recursos y evita agotar tus créditos gratuitos.

---

### 2. Configurar los Parámetros del Modelo

- **Temperatura**: controla la creatividad del modelo.  
  - Baja (≈0): resultados más predecibles y estructurados.  
  - Alta (≈1): resultados más creativos o impredecibles.

- **Top-p**: define el rango de probabilidad de las palabras que puede usar.

#### Ejemplos:
Para generar facturas:
```
Temperatura: 0.1  
Top-p: 0.2
```

Para escribir cuentos o ideas creativas:
```
Temperatura: 0.9  
Top-p: 0.8
```

---

## ✍️ Ingeniería de Prompts: Cómo Escribir Buenas Instrucciones

La calidad del prompt define la calidad del resultado.

### Recomendaciones:

1. **Sé claro y específico.**
2. **Incluye el contexto** donde se usará el contenido generado.
3. **Define el formato esperado** (ej: respuesta en lista, párrafos, JSON).
4. **Usa ejemplos** (*few-shot prompting*) para orientar al modelo.
5. **Divide tareas complejas en pasos** (*chain-of-thought prompting*).
6. **Filtra lo que no debe aparecer** (contenido sensible, inapropiado, etc.).

### Ejemplo de Prompt:
```
Genera una factura para el cliente [NOMBRE_CLIENTE] con los datos del vehículo proporcionado.
Sigue este formato: [Ejemplo de factura].
Evita cualquier lenguaje ofensivo o inapropiado.
```

---

## 📌 Funciones Útiles para una Mejor Experiencia

### 🎵 Playlists
Agrupa tus aplicaciones favoritas o prototipos en listas personalizadas.

### 🌀 Remix
Duplica aplicaciones públicas para modificarlas y usarlas como base propia.

### 📸 Snapshots
Guarda el estado exacto de una ejecución: entrada, salida y configuración del modelo.

### 📤 Compartir
Puedes decidir si tu app es:

- **Pública**: cualquiera puede verla.
- **Compartida por link**: solo quienes tengan el enlace.
- **Privada**: solo tú puedes acceder.

---

## 📚 Leer la Documentación

Antes de sumergirte a crear sin parar, dedica unos minutos a revisar la documentación:

- **PartyRock Guide**: guía oficial y concisa sobre el uso de la plataforma.
- **FAQs**: respuestas a preguntas frecuentes.
- **Ejemplos prácticos**: para entender cómo otras personas están utilizando PartyRock.

---

## 🔄 Mantente al Día

- Consulta la sección **"What's New"** para ver cambios recientes en la plataforma.
- Revisa el **roadmap público**, donde AWS publica lo que viene para PartyRock.
- Nuevos modelos como **Amazon Nova** se incorporan continuamente.

---

## 💰 Gestión de Créditos

PartyRock tiene un modelo de créditos gratuitos diarios. Consideraciones:

- **Verifica tu consumo** en el área de **Backstage**.
- Modelos más grandes consumen más rápido tus créditos.
- Puedes desactivar el uso compartido de datos desde esta misma sección si trabajas con información sensible.

---

## 🤝 Comunidad y Colaboración

PartyRock es más que una herramienta: es un espacio para crear, compartir y aprender.

### Recomendaciones:
- Comparte tus aplicaciones si no contienen información privada.
- Explora las creaciones de otros usuarios para inspirarte.
- Remix, mejora y personaliza ideas existentes.

---

## 🧭 En Resumen: ¡Crea, Explora y Disfruta!

> La mejor manera de aprender a usar PartyRock es **usándolo**.

✅ Diseña ideas nuevas  
✅ Experimenta con prompts  
✅ Prueba diferentes modelos  
✅ Comparte lo que haces  
✅ Aprende de los demás

---

## 🙌 Gracias

¡Espero que esta guía te haya sido útil!  
Ahora es tu turno: entra a PartyRock, diseña tu primera aplicación, compártela y diviértete aprendiendo sobre inteligencia artificial generativa.
