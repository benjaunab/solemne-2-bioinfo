# solemne 2

Alumno: Benjamin Flores Oviedo

__1.__ Usted trabaja como asistente de investigación en el centro de bioinformática y biología integrativa de la Universidad Andres Bello. Su jefe le asigna un proyecto de alta prioridad: se le indica que, en el refrigerador (a -20 °C), usted encontrara un tubo eppendorf que contiene ADN aislado desde una muestra fecal proveniente de un paciente, cuya identidad desconoce . el paciente presenta claros sintomas de una infeccion bacterian intestinal, pero no se ha podido identificar la identidad del patógeno responsable mediante el metodo tradicional de cultivo en placa de petri. Disponiendo usted de una muestra de ADN total aislado de una muestra de heces del paciente, describa de forma breve y precisa su plan de trabajo, paso a paso, para responder a la siguiente pregunta: ¿Que bacterias estan presentes en la muestra?

_R_: Para responder esta pregunta el plan de trabajo que realizaría seria: Primero, asumiendo que la muestra esta pura y con la cantidad suficiente de DNA, realizar una meta taxonómica utilizando como herramienta una amplicon sequencing, debido a que lo que necesito es solo identificar las bacterias presentes en la muestras y estas técnica me permite obtener los perfiles taxonómicos, para esto nos tendríamos que enfocar en un gen marcador que podría ser el gen que codifica la síntesis del ARN ribosomal 16S, ya que, es un gen bastante característico de cada especie al poseer regiones conservadas y variables. Luego de obtener los OTUs realizar un BLAST para poder identificar que son cada OTUs al alinear las secuencias obtenidas con lo que se encuentra en las bases de datos. De esta forma poder identificar que bacterias están presentes en la muestra y en qué cantidad.


__2.__ Siguiendo con la situacion planteada en el enunciado anterior. Usted ya tiene los resultados de su trabajo, es decir, usted sabe qué bacterias estan presentes en la muestra. De acuerdo a sus hallazgos, ¿bajo que criterio usted indicaria a una de las bacterias como el patogeno y por qué?

_R_: Para esto cada organismo se le realizara un análisis en específico dándole prioridad a las bacterias que tienen un mayor porcentaje de abundancia relativa en la muestra, debido a que si se encuentra en mayor cantidad en la muestra, existe una gran posibilidad de ser la causante de la enfermedad en el paciente. Cuyo análisis consistirá en realizar un shotgun sequencing, ya que se conocen las bacterias, para identificar su secuencia. Luego aplicar un ensamblaje De Novo, para obtener mayor información taxonómica de la especie, luego se compararía con una base de datos, como por ejemplo NCBI, para realizar una filogenia, de esta manera se podrá inferir que: si la bacteria que se sospecha que es la patógena, va a esta cercana evolutivamente a un patógeno conocido, entonces existirá una gran posibilidad de que este organismos sea el causante de la enfermedad. 

__1.__ Según lo visto en el laboratorio, en este caso requerirá caracterizar evolutivamente proteínas de la familia de isoprenyl synthetase (5 proteínas) determinando si ¿existe una relación convergente o divergente entre ellas? ¿porque?, para lo cual deberá utilizar las distintas herramientas como las bases de datos uniprot, prosite, pfam, entre otras.

_R_: Al buscar la familia de isoprenil sintetiza se encontró que, bases datos tales como pfam y scop, entregaba resultados relacionados con poliprenil sintetasa (EZ 2.5 Transferring Alkyl or Aryl Groups, Other than Methyl Groups), por lo cual se utilizó este para la búsqueda de las proteínas.

Para empezar, se eligieron las proteínas cuyo código uniprot es: P22939, P05369, O04046, O95749 Y O66129. Utilizando la base de datos de uniprot se encontró que entre ellas poseen la misma función que es transferir grupos alquilos, pero entre ellas se diferencian la cantidad de reacciones que pueden realizar, en el caso de la Farnesyl diphosphate synthase (P22939) puede realizar una reacción en cambio la Heterodimeric geranylgeranyl pyrophosphate synthase large subunit 2 es capaz de catalizar 3 reacciones distintas. Cabe destacar que las 5 proteínas poseen dominios que interactúan con el magnesio y que están compuestas principalmente por alfa hélices. Al realizar el alineamiento de estas 5 proteínas dio como resultado un porcentaje de identidad del 4.494% en donde la región de unión al cofactor y el sitio de unión al sustrato esta conservada entre ellas. Al buscar información en prosite, pfam e interpro se obtuvo que todas poseen 2 dominios característicos de la familia de poliprenil sintetasa y que 4 de ellas los poseen en regiones muy cercanas a diferencia de la Heterodimeric geranylgeranyl pyrophosphate synthase que posee estos dominios un poco más desplazados. Como resultado se puede inferir que estas 5 proteínas poseen una relación divergente, ya que poseen una función similar entre ellas, pero que algunas lograron especializarse y/o adquirir funciones nuevas, además los organismo han utilizar energía para conservar estructuras claves entre ellas que les permiten ser un aporte para la supervivencia y lo que ha cambiado significativamente son los aminoácidos que le otorgan la conformación a la proteína, ósea, que aminoácidos han sido cambiado por la naturaleza para poder modificar la estructura de la proteína y de esta manera interactuar con nuevos sustratos.   
 



