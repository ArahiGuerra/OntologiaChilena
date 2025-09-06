# Ontología Semántica de la Música Chilena 

## Descripción
Este proyecto presenta una **ontología semántica preliminar** para la representación estructurada del conocimiento musical chileno. La ontología abarca dos períodos significativos: **1970–2000** y **2019–2020**, capturando la relación entre música, artistas, géneros, temáticas y contextos históricos, sociales y políticos de Chile.

El proyecto se desarrolla en **Protégé**, se exporta a **RDF/OWL** y se consulta en **GraphDB** mediante **SPARQL**, contribuyendo a la preservación cultural, análisis académico y construcción de grafos de conocimiento en humanidades digitales.

---

## Objetivos
- Sistematizar y preservar información sobre la música chilena en una ontología formal.
- Representar de manera estructurada las entidades principales: **Canciones, Artistas, Géneros, Épocas, Productores y Temáticas**.
- Permitir consultas semánticas para el análisis de tendencias musicales.
- Explorar las conexiones entre música y contextos sociales y políticos de Chile.

---

## Tecnologías empleadas
| Tecnología | Uso |
|------------|-----|
| **Protégé** | Modelado de la ontología |
| **GraphDB** | Repositorio RDF y motor de consultas SPARQL |
| **OWL / RDF / Turtle** | Estándares de representación del conocimiento |

---

## Metodología
1. **Definición del dominio y alcance**: delimitación temporal y temática (1970–2000 y 2019–2020).  
2. **Identificación de entidades principales**: clases como `Cancion`, `Artista`, `Genero`, `Epoca`, `Productor`, `Tematica`.  
3. **Modelado ontológico en Protégé**: definición de propiedades de objeto y datos, axiomas y restricciones.  
4. **Normalización y carga de datos**: conversión de dataset a instancias RDF.  
5. **Verificación**: uso de razonadores (**HermiT**) para validar consistencia.  
6. **Almacenamiento en GraphDB**: carga de la ontología en un repositorio RDF.  
7. **Consultas SPARQL**: obtención de información estructurada y visualización en forma de grafo.


