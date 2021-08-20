## TLR vs VPH y Ebola 

Puede utilizar el [editor en GitHub](https://github.com/CdeCMx-org/templates_paginaweb/edit/main/README.md) para mantener y obtener una vista previa del contenido de su sitio web en archivos Markdown. Siempre que guardes los cambios en este repositorio, GitHub Pages ejecutará [Jekyll](https://jekyllrb.com/) para reconstruir las páginas de su sitio, a partir del contenido de sus archivos Markdown. Puedes escoger otro template en la siguiente página [repository settings](https://github.com/CdeCMx-org/templates_paginaweb/settings/pages). El tema de este template fue guardado en `_config.yml`.

El URL generado de tu página lo puedes encontrar en Settings -> Pages. 

*Puedes ver los cambios reflejados en la página, solo toma en cuenta que puede tomar unos minutos en cambiar.*

### Introducción

Desde tiempos antiguos nuestro cuerpo ha luchado por evolucionar y adaptarse a distintas situaciones de riesgo, y esto se intensifica más cuando se debe enfrentar contra algún tipo de patógeno tales como los virus. Puede ser algo complejo entender cómo el cuerpo humano puede darle batalla a estos antígenos que pueden perdurar por años, sin embargo, gracias al avance tecnológico y científico es posible darle una ayuda al sistema inmunitario humano para acelerar el proceso de protección contra estos virus. 

El tercer Objetivo de Desarrollo Sostenible (ODS) está focalizado a la salud y bienestar, el cual busca garantizar una vida sana y promover el bienestar para todos en todas las edades. Es en este objetivo que se inspiró para realizar este Club de ciencia llamado “Virus o anticuerpos, quién se adapta más rápido y cómo”, ya que lo que se busca por medio de investigación y desarrollo en el ámbito médico, disminuir la mortalidad por los virus tan agresivos como el que hoy en día estamos luchando por erradicar (SARS-CoV-2).

Con la ayuda del análisis computacional y la biología, se tomaron como ejemplos al VPH (Virus del Papiloma Humano) y al virus del Ébola para entender cómo los anticuerpos nos protegen contra los virus.


### Métodología

A.	Como primer paso, se eligieron estas dos proteínas de la base de datos “Protein Data Bank (PDB)”:
  1.	Estructura del pentámero de la proteína principal de la cápside L1 del virus del papiloma humano tipo 18. ID PDB: 2R5I.
  
 Las siglas VPH significan virus del papiloma humano (HPV, por sus siglas en inglés). El VPH se conforma por un grupo numeroso de virus relacionados. 
A cada variedad de virus en el grupo se le asigna un número, lo que es llamado tipo de VPH. 
Los tipos comunes de VPH de alto riesgo incluyen los tipos 16 y 18 del virus.

   2.	Virus del Ébola VP24 (EBOV) en complejo con carioferina alfa 5 C-terminal. ID PDB: 4U2X.
 La proteína viral del Ébola se considera una proteína de matriz secundaria multifuncional presente en partículas virales. 
En el centro de la desregulación inducida por el Ébola se encuentra una temprana y coordinada actuación de las proteínas VP24, VP30 y VP35, que conduce a niveles elevados de replicación viral, a una inapropiada temporización de la cascada de liberación de linfocinas y a la muerte, tanto de células presentadoras de antígenos, como de células efectoras.

B.	Al reconocer el ID en el que los virus se identifican en la página “RCSB PDB”, se dispone a utilizar el programa “Chimera”, el cual nos ayudará a limpiar la estructura de cada uno para dejar solamente la proteína del virus. 

C.	Se procede a elegir qué receptores tipo toll (TLRs, por sus siglas en inglés) se utilizarán para acoplarlos en la proteína de los virus. Éstos son sensores de reconocimiento de membrana evolutivamente conservados, constituyen una familia de proteínas que forman parte del sistema inmunitario innato. Podría decirse que son activadores clave de la respuesta inmunológica. Sin embargo, se debe elegir cuidadosamente ya que cada TLR tiene ciertas características que los hace más afines a ciertas proteínas de virus. 

### VPH tipo 18 + TLR 4

![](Proteina_1_0.JPG)
![](Proteina_1_1.JPG)

Un estudio realizado por Hasimu A. y otros (2) evidenció que la expresión de TLR4, 7 y 9 varía significativamente en el tejido de cáncer cervical, donde los niveles de expresión de TLR4 y TLR9 correlacionaron positivamente con la infección del VPH16 y VPH18.
Como el TLR 4 es un TLR de membrana celular, es adecuado para que se acople con la proteína principal de la cápside L1 del virus del papiloma humano tipo 18.
TLR4 reconoce el lipopolisacárido (LPS) de la pared de bacterias Gram negativas, las proteínas de choque térmico (HSP) de 60 y 70 kDa, entre otros.

#### Virus del Ébola + TLR3

![](proteina20.JPG)
![](proteina21.JPG)

Los TLR de membrana endosomal van a reconocer moléculas intracelulares, como el TLR-3 que reconoce ARN BC (ARN bicatenario).
Aunque el virus del ébola contiene ARN monocatenario se quiere averiguar si existe alguna posibilidad de compatibilidad.




### Resultados

Este es el momento en que nos compartas los resultados obtenidos en tu proyecto. Asegurate de incluir material visual (gráficas, fotos, diagramas, tablas). 

Puedes inster imagenes utilizando Markdown `![](Logo_CdeCMx.png)`.

![](Logo_CdeCMx.png)

O utilizando codigo html `<img src="Logo_CdeCMx.png" width=200>`, la ventaja de utilizar html es que le puedes modificar el tamaño utilizando **width**.
<img src="Logo_CdeCMx.png" width=200>


### Conclusiones

Comparte tus observaciones, lo aprendedido, limitaciones y siguientes pasos. 

### Video
 1. Para insertar un video de YouTube, en la página de YouTube del video selecciona compartir y selecciona el código de html.
 <iframe width="560" height="315" src="https://www.youtube.com/embed/PLj1-CMNERM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
 
 2. Insertar el link de tu video en YouTube, [nuestro video](https://youtu.be/rmXvlBPq24Q).
 4. Puedes subir el archivo de tu video directamente a Github [instrucciones aquí](https://stackoverflow.com/questions/4279611/how-to-embed-a-video-into-github-readme-md)
 
### Equipo:

* Leonardo Darwin Ortiz Perez
* Ileany Noemi Avila Chay
* Jennifer Evelyn Estrada Medina


