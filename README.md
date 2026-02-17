# Ejercicios de Validación XML con XML Schema (XSD)

Este repositorio contiene la resolución de dos ejercicios prácticos para la validación de documentos XML utilizando esquemas XSD. El objetivo es definir la estructura, los tipos de datos y las jerarquías necesarias para asegurar la integridad de la información.

## 🚀 Tecnologías utilizadas
* **XML**: Lenguaje de marcado para el almacenamiento de datos.
* **XSD (XML Schema Definition)**: Lenguaje para definir las reglas de validación.
* **VS Code**: Editor utilizado para el desarrollo y validación.

---

## 📂 Contenido del Repositorio

### Ejercicio 1: Nota Recordatoria
Validación de una estructura sencilla de mensajería.

* **Estructura**: Un elemento raíz `<nota>` con cuatro elementos hijos de tipo texto.
* **Archivos**:
  * `nota.xml`: Contiene los datos y la referencia al esquema.
  * `nota.xsd`: Define las reglas de validación (secuencia obligatoria).



### Ejercicio 2: Matrícula Universitaria
Validación de una estructura compleja con elementos anidados y atributos.

* **Estructura**:
  * Raíz `<matricula>`.
  * Bloque `<personal>` con datos del alumno y una lista de `<domicilios>`.
  * Bloque `<pago>` con información sobre el tipo de matrícula.
* **Características especiales**:
  * Uso de atributos (`tipo`) en el elemento domicilio.
  * Cardinalidad (`maxOccurs="unbounded"`) para permitir múltiples domicilios.
* **Archivos**:
  * `matricula.xml`: Documento con los datos del alumno Juan Pardo Martín.
  * `matricula.xsd`: Esquema con tipos complejos y atributos requeridos.
