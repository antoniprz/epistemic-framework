# Parte 4 — Sistema de Tipos Ontológicos

Para que una discusión sea productiva, cada término utilizado debe pasar por un "chequeo de tipos". Si intentamos realizar operaciones lógicas entre términos de tipos incompatibles (ej. tratar una ficción de C5 como un hecho de C1), el sistema colapsará en una falacia.

## 4.1 Taxonomía de Referentes
Clasificamos cada término según la naturaleza de aquello a lo que apunta en las capas (C0-C5):

| Tipo | Etiqueta | Descripción | Ejemplo |
| :--- | :--- | :--- | :--- |
| **RAW** | `v0` | El objeto en C0, antes de ser medido o nombrado. La "cosa en sí". | El espectro antes de Newton. |
| **ACCESIBLE** | `v1` | Fenómenos de C1/C2 verificados por el Pipeline. Tienen poder predictivo. | La gravedad, el oxígeno. |
| **CONVENCIÓN** | `v2` | Construcciones de C4/C5 con autores o consenso social. Son "correctas" pero no "verdaderas". | El dinero, el lenguaje, el PIB. |
| **INDEFINIDO** | `v?` | Conceptos en proceso de validación o que aún no tienen suficiente data de C1. | Agujeros de gusano, conciencia. |
| **DANGLING** | `v-err` | Punteros vacíos. Palabras que no tienen referente en ninguna capa o son circulares. | Destino, suerte, "el sistema" (como ente). |

## 4.2 La Regla de la Instancia vs. Clase
Un error común es confundir una **clase** (una etiqueta de C4) con una **instancia** (un objeto en C1).
* **Instancia (C1):** El perro que te mordió (un objeto físico con masa y comportamiento).
* **Clase (C4):** "La peligrosidad canina" (una abstracción social).
Operar sobre la clase como si fuera una instancia es un fallo de tipo que genera políticas públicas ineficientes y debates circulares.

## 4.3 El Algoritmo de Etiquetado
Antes de procesar un argumento, se debe someter cada sustantivo al siguiente test:

1.  **¿Tiene masa, energía o información medible?** -> Marcar como `v1`.
2.  **¿Desaparecería si todos los humanos dejaran de creer en ello?** -> Marcar como `v2`.
3.  **¿La definición depende exclusivamente de otras palabras sin tocar C1?** -> Marcar como `v-err`.

## 4.4 Colisión de Tipos (Type Mismatch)
La mayoría de los conflictos sociales ocurren por una colisión de tipos no detectada.
* **Error Tipo A:** Tratar un `v2` (Ficción social) como un `v1` (Realidad física). Ej: "La economía debe crecer por ley natural".
* **Error Tipo B:** Intentar modificar un `v1` (Realidad física) mediante herramientas de `v2` (Retórica). Ej: "Decretamos que la gravedad es opresiva".

## 4.5 El Estatus "Dangling" (Puntero Suelto)
Un término `v-err` es radiactivo para el conocimiento. Si una conversación incluye más de un 20% de punteros sueltos, el framework recomienda abortar la comunicación, ya que no se está intercambiando información, sino simplemente sincronizando estados emocionales (C3) sin anclaje.

---
*Este sistema de tipos permite que el framework sea auditable: si un término cambia de tipo, debe haber un commit que justifique la nueva evidencia en C1.*