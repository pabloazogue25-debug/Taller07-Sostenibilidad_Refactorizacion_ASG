# AEE UD06.Auditoría ASG y Refactorización Sostenible

## ÍNDICE
1. [Fase 1: Inventario y Dimensión Ambiental (A)](#fase-1-inventario-y-dimensión-ambiental-a)
2. [Fase 2: Dimensión Social y Equidad (S)](#fase-2-dimensión-social-y-equidad-s)
3. [Fase 3: Dimensión de Gobernanza y Ética (G)](#fase-3-dimensión-de-gobernanza-y-ética-g)
4. [Fase 4: Propuesta de Refactorización (Green Coding)](#fase-4-propuesta-de-refactorización-green-coding)

---

# Fase 1: Inventario y Dimensión Ambiental (A)

## 1.1 Medición inicial mediante Website Carbon

[www.mkpersons.com](https://www.websitecarbon.com/website/mkpersons-com/)

Tras la investigación observamos que esta página web obtiene una calificación de carbono D y que es más limpia que el 52% de todas las páginas web a nivel mundial.

También vemos que solo se producen 0,25 gramos de CO₂ cada vez que alguien visita esta página web y que parece utilizar energía estándar.

Si este sitio web utilizara alojamiento web ecológico, emitiría un 9% menos de CO₂.

---

## 1.2 Identificación de Bloatware

Tras realizar mediciones con la herramienta Lighthouse que nos proporciona Chrome obtenemos una media de 64 en rendimiento, lo que indica que necesita una refactorización para mejorar su carga.

Observamos también una accesibilidad de 67, lo que indica que existen malos contrastes de colores o estructuras de encabezados deficientes.

Obtenemos una media de 54 en mejores prácticas, lo que indica que la web usa código obsoleto.

En SEO obtenemos un 85, lo que indica que está bien optimizada para motores de búsqueda.

A tener en cuenta que el elemento más grande de la pantalla tarda 13 segundos en aparecer.

![Lighthouse rendimiento](https://github.com/user-attachments/assets/2dbc3faa-e93d-4991-a02e-4774ec8d04a6)

También observamos en la imagen inferior que tenemos 3 archivos muy pesados (entre 2.500 KB y 3.500 KB), lo que ralentiza mucho la carga.

![Archivos pesados](https://github.com/user-attachments/assets/9d712589-d069-4f34-ba49-cbee57a6b213)

---

## 1.3 Conclusión y Análisis

Llegamos a la conclusión de que la página web elegida necesita una refactorización de código para aumentar su rendimiento y reducir su impacto ambiental.

Sufre una inflación de software, ya que incorpora recursos demasiado pesados y procesos innecesarios para las funcionalidades que ofrece. Esto provoca un mayor consumo de energía tanto en el servidor como en los dispositivos de los usuarios.

Entre los principales problemas detectados destacan:

- Uso de imágenes y archivos multimedia excesivamente pesados.
- Tiempos de carga muy elevados, especialmente en el elemento LCP (Largest Contentful Paint), que tarda aproximadamente 13 segundos en mostrarse.
- Recursos JavaScript y CSS poco optimizados o posiblemente obsoletos.
- Carga de elementos innecesarios que aumentan el consumo de datos y memoria.
- Baja puntuación en rendimiento y mejores prácticas según Lighthouse.

---

# Fase 2: Dimensión Social y Equidad (S)

## 2.1 Accesibility

Gracias a la herramienta web de  WAVE Web Accessibility Evaluation Tool podemos obtener una medición clara de la accesibilidad de esta web. Anteriormente obtuvimos un parámetro de 54 respecto a la accesibilidad pero vamos a profundizar más en ello y a darle la importancia que se merece.

<img width="344" height="250" alt="image" src="https://github.com/user-attachments/assets/cdaab64f-da3b-44f9-a121-05638f55d4e1" />

## 2.2 Accesibility errors

Muy importante y a tener en cuenta son los 11 errores que nos aparecen y los 29 errores de contraste que obtenemos.

<img width="322" height="460" alt="image" src="https://github.com/user-attachments/assets/cc533f48-f57b-4ef7-a285-8de1f70140af" />

Tenemos variedad de erorres pero sobre todo errores de contraste , algo que reduce mucho nuestra accesibilidad.
También observamos errores por falta de texto alternativo o de etiquetado que debemos tener en cuenta cuándo refactorizemos la web



# Fase 3: Dimensión de Gobernanza y Ética (G)

# Fase 4: Propuesta de Refactorización (Green Coding)
