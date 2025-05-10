# 📄 Generación de Documentación con Javadoc

Javadoc es una herramienta oficial de Java que permite generar documentación técnica en formato HTML a partir de los comentarios estructurados que se incluyen en el código fuente. Es especialmente útil para mantener proyectos bien documentados, tanto para desarrolladores como para usuarios avanzados.

---

## ✏️ Ejemplo de uso con Javadoc

A continuación, se muestra un ejemplo de clase Java con comentarios de Javadoc:

```java
/**
 * Clase que representa una calculadora básica.
 * Ofrece operaciones como suma y resta.
 */
public class Calculadora {

    /**
     * Suma dos números enteros.
     *
     * @param a Primer número
     * @param b Segundo número
     * @return La suma de a y b
     */
    public int sumar(int a, int b) {
        return a + b;
    }

    /**
     * Resta dos números enteros.
     *
     * @param a Primer número
     * @param b Segundo número
     * @return La resta de a y b
     */
    public int restar(int a, int b) {
        return a - b;
    }
}

### 📘 Insignias (badges)

Las insignias son pequeños indicadores visuales que muestran el estado de un proyecto (build, cobertura, licencia, etc.). Se pueden incluir fácilmente en Markdown.

### 🧾 Tipos de documentación

- 📦 **Documentación de código**: Explica el funcionamiento interno del código, clases, métodos, etc.
- 🛠️ **Documentación técnica**: Dirigida a desarrolladores. Explica cómo instalar, configurar o usar el software.
- 👨‍💻 **Documentación de usuario**: Guías o manuales para el usuario final.

### 🗂️ Formatos de documentación

- 🌐 **HTML** – Usado por herramientas como Javadoc.
- 📝 **Markdown** – Muy común en proyectos en GitHub. Ej.: GitBook.
- 📐 **reStructuredText** – Usado en plataformas como ReadTheDocs.
- 📄 **AsciiDoc** – Otro formato para documentación técnica avanzada.