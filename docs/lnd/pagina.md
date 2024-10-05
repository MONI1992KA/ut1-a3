# UT1-A2 - Introducción a Markdown

## Contenido
- [Pregunta 1](#pregunta-1)
- [Pregunta 2](#pregunta-2)
- [Pregunta 3](#pregunta-3)
- [Pregunta 4](#pregunta-4)
- [Pregunta 5](#pregunta-5)
- [Pregunta 6](#pregunta-6)
- [Pregunta 7](#pregunta-7)
- [Pregunta 8](#pregunta-8)


---

## Pregunta 1
**¿Qué es Markdown y para qué se utiliza? Investiga el origen y los principales usos del lenguaje Markdown. ¿En qué contexto se desarrolló y por qué?**

**Respuesta:**  
<p style="text-align: justify;">
Markdown es un lenguaje de marcado ligero creado por John Gruber en 2004. Se utiliza principalmente para formatear texto de manera sencilla y legible, permitiendo a los usuarios escribir usando una sintaxis fácil que se puede convertir a HTML.
Markdown se desarrolló para facilitar la escritura de contenido en la web sin complicaciones. Su simplicidad permite a los autores enfocarse en el contenido más que en el formato.
Principales usos son la documentación técnica, Blogs, archivos README en proyectos de software y notas y lista
</p>

---

## Pregunta 2
**¿Cuáles son las características principales de Markdown que lo hacen diferente de otros lenguajes de marcas de presentación? Compara Markdown con HTML. ¿Qué ventajas e inconvenientes tiene Markdown frente a HTML?**

**Respuesta:**  
Markdown es diferente de otros lenguajes de marcado como HTML debido a su sencillez y legibilidad. Comparación entre Markdown y HTML:

| Característica      | Markdown | HTML       |
|-------------|------|--------------|
| Legilidad  | Alta   | Baja       |
| Complejidad   | Baja   | Alta    |
| Conversión a HTML| Directa y fácil   | Requiere más esfuerzo     |

Ventajas de Markdown:
-	Más fácil de aprender.
-	Más rápido para escribir.
-	Legible sin renderizar.

Inconvenientes:
-	Menos flexibilidad para diseño avanzado.
-	Funciones limitadas en comparación con HTML.

---

## Pregunta 3
**¿Qué aplicaciones o plataformas utilizan Markdown? Busca ejemplos de plataformas populares donde se utilice Markdown, como GitHub, blogs, o gestores de contenido. ¿Por qué crees que esas plataformas han adoptado Markdown?**

**Respuesta:**  
Algunas plataformas populares que utilizan Markdown incluyen:

-   GitHub: para documentación de proyectos y archivos README.
-	WordPress: en algunos plugins y editores.
-	Notion: para tomar notas y organizar información.

Razones para adoptar Markdown

-	Sencillez y eficiencia en la edición.
-	Facilita la colaboración entre usuarios técnicos y no técnicos.
puedes escribir una respuesta detallada a la pregunta. Puedes incluir ejemplos, datos o cualquier información relevante.

---

## Pregunta 4
**¿Cuáles son las etiquetas o símbolos más comunes que se utilizan en Markdown para dar formato a un texto? Proporciona ejemplos prácticos de:**

**Respuesta:**  
-	Párrafos:  ## Párrafos
-	Encabezados (de distintos niveles): ## Encabezados  ### Encabezado de nivel 3
-	Texto en negrita:
 ```
*cursiva* , _cursiva_ 
```
-	Listas: se pueden usar (-,*, o +) 
-	Una tabla: 
```
| Nombre   | Edad | Ciudad |
|----------|------|------------- |
| Juan     | 30   | Madrid        |
| María    | 25   | Barcelona |
| Pedro    | 28   | Valencia    |
```
-	Enlace que permita acceder a otro documento: texto de enlace con [ ] y URL con ( ). 

Ejemplo: Puedes consultar más sobre Markdown en [Wikipedia - Markdown](https://es.wikipedia.org/wiki/Markdown).

## Pregunta 5
**¿Cómo se puede visualizar y convertir un archivo escrito en Markdown a otros formatos, como HTML o PDF? Busca herramientas o aplicaciones que permitan convertir Markdown a otros formatos, y explica cómo funcionan.**

**Respuesta:**  

Gracias a varias herramientas podemos convertir Markdown a otros formatos:

+ Pandoc
<p style="text-align: justify;">
Descripción: Pandoc es una herramienta de línea de comandos muy potente que puede convertir documentos en diferentes formatos, incluyendo Markdown, HTML y PDF.
Funciona con comandos en la terminal. Por ejemplo, para convertir un archivo Markdown a HTM. (pandoc archivo.md -o archivo.htmlL.)
</p>

+ Visual Studio Code con Extensiones
<p style="text-align: justify;">
Descripción: Visual Studio Code es un editor de código que soporta Markdown a través de extensiones.
Funciona:
Instalación: Descarga Visual Studio Code desde su sitio oficial.
Extensión: Instala la extensión "Markdown PDF" desde el marketplace.
Uso: Abre el archivo Markdown, luego usa el comando para exportar a PDF (Ctrl + Shift + P y escribe "Markdown PDF: Export (pdf)").
</p>

+ Dillinger 
<p style="text-align: justify;">
Descripción: Dillinger es un editor de Markdown en línea que permite exportar a varios formatos.
Funciona: copia y pega tu contenido en el editor, luego usa la opción de exportar para guardarlo como HTML o PDF.
</p>

## Pregunta 6
**¿Qué ventajas tiene escribir documentación o notas en Markdown frente a usar procesadores de texto como Microsoft Word o Google Docs? Analiza las diferencias y las ventajas que puede tener escribir en un lenguaje de marcas sencillo como Markdown en lugar de usar un procesador de texto tradicional.**  

**Respuesta:**  
Markdown es más sencillo y legible, permitiendo que el enfoque esté en el contenido en lugar del formato. Los archivos son portátiles y fáciles de abrir en cualquier editor, reduce la dependencia de software específico, lo que también minimiza problemas de compatibilidad.

## Pregunta 7
**¿Existen diferentes "sabores" o variaciones de Markdown? Investiga si hay diferentes versiones o extensiones de Markdown, como GitHub Flavored Markdown (GFM). ¿En qué se diferencian de la versión estándar?**  

**Respuesta:**  
Esta son algunas de las variaciones que existen de Markdown:
+	GitHub Flavored Markdown (GFM)

Diferencias: GFM incluye características adicionales como tablas, listas de tareas, y sintaxis para mencionar usuarios y referencias a problemas. También permite el uso de HTML en mayor medida y una mejor integración con el control de versiones de GitHub.

+	Markdown Extra

Diferencias: Esta versión añade soporte para tablas, notas al pie y mejor manejo de HTML, así como la capacidad de definir encabezados de niveles múltiples con mayor flexibilidad.

+	CommonMark

Diferencias: CommonMark busca estandarizar la sintaxis de Markdown, creando un formato más predecible y consistente. Se basa en la versión original de Markdown, pero define reglas claras para cada elemento y proporciona una especificación formal.

+	MultiMarkdown

Diferencias: Añade soporte para tablas, referencias bibliográficas y metadatos. También permite la salida a diferentes formatos, como LaTeX y HTML, lo que es útil para publicaciones académicas.

+	Markdown-it

Diferencias: Es un parser de Markdown altamente extensible y rápido que permite la creación de plugins para añadir funcionalidades personalizadas, como la mejora en la gestión de imágenes, listas y más.

+	Pandoc Markdown

Diferencias: Utilizado principalmente en el contexto de Pandoc, esta variante soporta un conjunto extenso de características, incluyendo referencias bibliográficas, soporte para múltiples formatos de salida y un gran número de extensiones.

## Pregunta 7
**¿Cómo puede ser útil Markdown en el trabajo colaborativo en proyectos de software? Investiga  cómo Markdown es utilizado en entornos de colaboración, como en la documentación de proyectos de software en GitHub o la creación de archivos README.**

**Respuesta:**  
<p style="text-align: justify;">
Markdown es ampliamente utilizado en entornos de colaboración, como GitHub, debido a su simplicidad y legibilidad. Permite crear documentación estructurada y fácil de entender, y su formato se integra bien con sistemas de control de versiones. Esto facilita la colaboración en tiempo real y asegura consistencia en la presentación de proyectos. Además, se puede convertir fácilmente a HTML, lo que lo hace ideal para documentación en línea.
</P>