# Apuntes sobre Optimización de Código
## Introducción a la Optimización de Código
La optimización de código se refiere a mejorar el rendimiento, la legibilidad y la mantenibilidad del código sin alterar su comportamiento funcional.

### Hediondez del Código (Code Smell)
El término "hediondez del código" se refiere a indicios en el código que podrían sugerir problemas más profundos, aunque no son necesariamente errores. Algunos ejemplos son:
- Código duplicado.
- Funciones o métodos demasiado largos.
- Nombres de variables poco descriptivos.

### Refactorización
La refactorización es el proceso de reestructurar el código sin cambiar su funcionalidad. Algunas técnicas incluyen:
- Renombrar variables.
- Eliminar código redundante.
- Extraer métodos de funciones largas.

### Análisis Estático de Código
Los analizadores estáticos de código, como **linters**, se utilizan para detectar problemas potenciales sin ejecutar el código.

#### Herramientas de Análisis:
- **Lint** (para C).
- **SonarQube** (para Java).
- **ESLint** (para JavaScript).

### Análisis Dinámico
El análisis dinámico se realiza durante la ejecución del código, como la ejecución de pruebas unitarias.

#### Herramientas de Análisis Dinámico:
- **JUnit** (para Java).
- **Mocha** (para JavaScript).