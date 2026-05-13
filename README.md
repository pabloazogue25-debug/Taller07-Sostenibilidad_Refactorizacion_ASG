# AEE UD06.Auditoría ASG y Refactorización Sostenible

## ÍNDICE
1. [Fase 1: Inventario y Dimensión Ambiental (A)](#fase-1-inventario-y-dimensión-ambiental-a)
2. [Fase 2: Dimensión Social y Equidad (S)](#fase-2-dimensión-social-y-equidad-s)
3. [Fase 3: Dimensión de Gobernanza y Ética (G)](#fase-3-dimensión-de-gobernanza-y-ética-g)
4. [Fase 4: Propuesta de Refactorización (Green Coding)](#fase-4-propuesta-de-refactorización-green-coding)

## Fase 1: Inventario y Dimensión Ambiental (A)
### 1.1 Medición inicial mediante websitecarbon.
    
        [www.mkpersons.com](https://www.websitecarbon.com/website/mkpersons-com/)
        Tras la investigación observamos que esta página web obtiene una calificación de carbono de Dy que es más limpio que 
        52% de todas las páginas web a nivel mundial.
        También vemos que solo 0,25 gramos de CO2 Se produce cada vez que alguien visita esta página web y que parece que esta página web utiliza energía estándar.Si este sitio web utilizara alojamiento web ecológico,               emitiría un 9% menos de CO2.
        
### 1.2 Identificación de Bloatware.
    
        Tras realizar mediciones con la herramienta de lighthouse que nos proporciona chrome obtenemos una media de 64 en rendimiento que nos indica que necesita una refactorización para su carga.
        Observamos también una accesibilidad de 67 lo que indica que hay malos constrastes de colores o estructuras de encabezados. Obtenemos una media de 54 en mejores prácticas lo que nos indica que la web usa código              obsoleto. En SEO obtenemos un 85 lo que nos indica que está bien optimizada para motores de búsqueda.

        A tener en cuenta que el elemento mas grande de la pantalla tarda 13 segundos  en aparecer.
        
        ![Lighthouse rendimiento](https://github.com/user-attachments/assets/2dbc3faa-e93d-4991-a02e-4774ec8d04a6)

        También observamos en la imágen inferior que tenemos 3 archivos muy pesados (entre 2.500 KB y 3.500 KB ) lo que realentiza mucho la carga

        ![Archivos pesados](https://github.com/user-attachments/assets/9d712589-d069-4f34-ba49-cbee57a6b213)
        
   ### 1.3 Conclusión y Análisis.

        Llegamos a la conclusión que la página web elegida necesita una refactorización de código para aumentar su rendimiento y bajar su impacto ambiental.
        Sufre una inflación de software ya que incorpora recursos demasiado pesados y procesos innecesarios para las funcionalidades que ofrece. Esto provoca un mayor consumo de energía tanto en el servidor como en los            dispositivos de los usuarios.
        Entre los principales problemas detectados destacan:
            - Uso de imágenes y archivos multimedia excesivamente pesados.
            - Tiempos de carga muy elevados, especialmente en el elemento LCP (Largest Contentful Paint), que tarda aproximadamente 13 segundos en mostrarse.
            - Recursos JavaScript y CSS poco optimizados o posiblemente obsoletos.
            - Carga de elementos innecesarios que aumentan el consumo de datos y memoria.
            - Baja puntuación en rendimiento y mejores prácticas según Lighthouse.
        
## Fase 2: Dimensión Social y Equidad (S)

## Fase 3: Dimensión de Gobernanza y Ética (G)

## Fase 4: Propuesta de Refactorización (Green Coding)
