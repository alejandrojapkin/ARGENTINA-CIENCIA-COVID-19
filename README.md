
<img src="https://i.postimg.cc/GmkphStN/argentinaunida.png" height="100" />

# Actividad Ciudadana en la epidemia Coronavirus
## Proyectos de bajo costo / tecnologías abiertas

Esta es una colección independiente de propuestas civiles para afrontar la **Crisis SARS-CoV2 (Coronavirus) en Argentina**.</br> **El enfoque está en alternativas de bajo costo o de tecnologías abiertas de última instancia**.</br>
No represento a ninguna agencia estatal. La información aquí publicada es traída en buena fe y es constantemente actualizada y corregida, toda fuente ha de ser revisada sin que de ello se desprenda responsabilidad alguna de mi persona. 
</br>
 **El objetivo es dar visibilidad a la ciudadanía y conectar profesionales con iniciativas de su ideoneidad**.</br>
Esta lista se seguirá desarrollando. Contactate para colaborar.

- [Respiradores](#respiradores)
  * [Proyecto RespirAR](#proyecto-respirar)
  * [Inventu - UNR](#inventu---unr)
  * [Leistung](#leistung)
  * [Tecme](#tecme)
  * [Amek](#amek)
- [Máscaras y elementos de ascepcia](#m-scaras-y-elementos-de-ascepcia)
  * [NanoHack](#nanohack)
  * [Purificador de aire (elimina virus)](#purificador-de-aire--elimina-virus-)
- [Instrumental de diagnóstico y estadística](#instrumental-de-diagn-stico-y-estad-stica)
  * [PocketPCR](#pocketpcr)
  * [Modelado Estadístico de COVID-19 en proporción a servicio hospitalario](#modelado-estad-stico-de-covid-19-en-proporci-n-a-servicio-hospitalario)
  * [Comparador de países](#comparador-de-pa-ses)
  * [Paneles estadísticos](#paneles-estad-sticos)
  * [AppJennifer](#appjennifer)
  * [Dataset científico del COVID-19](#dataset-cient-fico-del-covid-19)
  * [_Advertencia sobre falacias estadísticas_](#-advertencia-sobre-falacias-estad-sticas-)


# Respiradores
Según datos del mercado de la salud, en Argentina hay entre 5.000 y 7.000 respiradores mecánicos en actividad, algunos con una antigüedad de siete a 10 años. _**Dato reciente**: el gobierno argentino trabaja junto a diferentes entidades para adaptar pulmones mecánicos a las necesidades del COVID-19 y ponerlos a disposición de los afectados_.

## Proyecto RespirAR
Desarrollo de un respirador diseño libre y público. Plantea explorar alternativas para saltear regulaciones:
-   Fabricación intrahospitalaria. 
-   Consentimiento informado por el paciente.

| Requerimiento  | Especificación                          
|----------------|-------------------------------|
| Licencia        | `Libre fabricación, los esquemáticos serían públicos`
| Apto Uso Médico | `No (es un dispositivo de última instancia)`
| Modalidad      | `Intubación` `Asistivo`
| Capacidad      |`No testeada`         
| Parametros      | `Frecuencia respiratoria (FR)` `Presión inspiratoria pico (PIP)` `Proporción Inspirar  Expirar (I/E)` `PEEP`
| Interfaz          |`Pantalla lcd` `Botones`            |
| Costo          |`U$D 350`|

    
23-03-2020 Presentaron **CARMA**. Este es el estadio actual del prototipo que venimos trabajando desde hace unos días y que Lucas Vassarotto está desarrollando y validando con la colaboración interdisciplinaria de un grupo de profesionales.


- RespirAR hace llamado público a médicos, ingenieros y entes que puedan financiar su desarrollo.
- [Hacer Click para **sumarse** al proyecto acá](https://forms.gle/cnoBrY3RrapYCioLA)

## Inventu - UNR

Proyecto Privado de Respirador de bajo costo. Participan la empresa Inventu Ingeniería y sus colegas en la Universidad Nacional de Rosario con alianza con las empresas Update Ingeniería y Digilogic. Se trata de un aporte de 2 millones de pesos. Están terminando el prototipo de un respirador artificial de “bajo costo, específico para COVID-19 y que sea fabricable en escala. Buscan aprobación expedita de ANMAT.
| Requerimiento  | Especificación                          
|----------------|-------------------------------|
| Licencia       | `Privada` `Otra`
| Apto Uso Médico | `Sí (pendiente aprobación ANMAT)`
| Modalidad      | `Intubación` `No posee modo asistivo`
| Capacidad      |`Volumen Max: 20 l/m` `Presión Max: 120cm de columna de agua`             |
| Parametros      | `Frecuencia respiratoria (FR)` `Presión inspiratoria pico (PIP)` `Proporción Inspirar  Expirar (I/E)` `PEEP`
| Interfaz          |`Pantalla táctil`            |
|Costo          |`No publicado`|

- **Al 22 de Marzo dice estar en la prueba de concepto (PoC).** 
- Gerente: Germán Campero
- [Hacer Click para contactar vía Linkedin.](https://ar.linkedin.com/in/german-campero-45b063123)


## Leistung

Produce 300 equipos al año, pero le están solicitando 900 en 4 meses.
- [Hacer Click para tener acceso vía Sitio web.](http://leistungargentina.com.ar/en/)

## Tecme

Ya entregó 250 equipos en el país y prepara 500 pedidos. 
- [Hacer Click para tener acceso vía Sitio web.](https://tecmeglobal.com/home-tecme-ar/)

## Amek 

16-03-2020 **Están desarrollando una bolsa AMBU en automatizada**, para que no sea necesario un médico o enfermero accionándola manualmente durante horas.
[Link](https://drive.google.com/file/d/1wVxMTf5KkvtNR-Nz7afI-pkcwKu0oifZ/view?usp=sharing) de un video del prototipo funcionando la semana pasada hasta que se instaló la cuarentena. **Carecen de bolsa AMBU para continuar su desarrollo.**
El tiempo de inflado y desinflado lo establece un controlador Arduino u otro micro controlador similar (PIC por ejemplo).
- Contactos: Pablo o Maximiliano Ancharek
- Plantearon la necesidad de la bolsa AMBU para seguir adelante:
- [Resucitadores manuales AMBU](https://www.iberomed.es/blog/2018/02/28/que-son-y-para-que-sirven-los-resucitadores-manuales/)
- [Hacer Click para contactar vía Linkedin.](https://ar.linkedin.com/in/pablo-ancharek-4735947a)



# Máscaras y elementos de ascepcia

Instrumental de protección de primera y última instancia, con foco en costo-beneficio.

## NanoHack

La máscara NanoHack es un dispositivo de última instancia cuya carcaza puede ser impresa en 3D independientemente. No obstante, el filtro del cual depende la máscara, de óxido de cobre, es propietario y debe ser en principio comprado al desarrollador. Pruebas han demostrado que los materiales empleados  (textil no tejido de polipropileno,  el mismo material que las máscaras quirúrgicas) consigue una eficiencia de filtrado de 96.4% para microorganismos de 1 micron y 89.5% para microorganismos de 0.02 micrones. _Nótese que los materiales de impresión 3D no son los plásticos usualmente empleados por la impresión 3D hogareña_.

<p float="left">
  <img src="https://i.postimg.cc/Fz3W9K12/Screen-Shot-2020-04-03-at-18-19-03.png" width=30% />
  <img src="https://i.postimg.cc/kG9yNPnS/Screen-Shot-2020-04-03-at-18-19-10.png" width=65% /> 
  
</p>

- [Hacer Click para contactar vía Sitio web.](https://copper3d.com/hackthepandemic/)

## Purificador de aire (elimina virus)

Instrucciones y esquemático para el desarrollo de un sistema de sanitización de elementos vía rayos ultravioletas.<br>
Este proyecto propone la realización de un filtro germicida del aire basado en luz ultravioleta de clase C. La luz ultravioleta de clase C (UVC) tiene la capacidad de eliminar virus, bacterias y otros patógenos. si bien otros rangos de longitud de onda también tienen cierto efecto sobre los microorganismos y virus, la UVC es la que ha dado mejores resultados. Pueden ver algunos trabajos y noticias que mencionan los efectos del UVC en casos como el del COVID-19.
 <img src="https://github.com/cirujadigital/OpenUVClean/raw/master/OpenUVClean2_h.jpg" width=65% /> 
- [Hacer Click para tener acceso vía Sitio web.](https://github.com/cirujadigital/OpenUVClean/wiki/Home-Instrucciones)


# Instrumental de diagnóstico y estadística

## PocketPCR
El PocketPCR es un proyecto abierto de PCR por termociclado, utilizado para activar reacciones biológicas. La reacción en cadena de la polimerasa (PCR) es un método ampliamente utilizado en biología molecular para hacer copias de un segmento de ADN específico. Las aplicaciones de la técnica incluyen la clonación de ADN para secuenciación, análisis de huellas genéticas, amplificación de ADN antiguo y clonación de genes. Este termociclador ultra portátil y compacto fue diseñado con el objetivo de reducir el costo a un precio asequible para cualquiera que quiera hacer algo de biología Do-It-Your-Self con un kit de inicio de ADN en su cocina. El PocketPCR puede ejecutarse desde un simple adaptador de corriente USB. El dispositivo se puede operar de forma independiente y todos los parámetros se pueden configurar sin la necesidad de una computadora o teléfono inteligente.

- [Hacer Click para contactar vía website.](http://gaudi.ch/PocketPCR/)

## Modelado Estadístico de COVID-19 en proporción a servicio hospitalario
Este panel permite estimar la respuesta a COVID-19 en función de experiencias previas, parametrizando la disponibilidad de herramientas de salud. Las predicciones se basan en un modelo SIR (consulte la página para más detalles) que simula un brote de COVID19. La población as asume inicialmente mayormente susceptible (excepto para los casos iniciales). Las personas que se recuperan de COVID19 son posteriormente consideradas inmunes en la proyección (aunque esto no ha sido probado científicamente). Algunos parámetros del modelo no se ajustan a los datos, sino que simplemente son valores predeterminados;  podrían encajar mejor para algunas localidades que otras. En particular, los recuentos de casos iniciales a menudo son solo estimaciones aproximadas.
</br></br>
<img src="https://user-images.githubusercontent.com/9403403/77125848-710b2700-6a47-11ea-84c3-19016d16e9dd.gif" width=80% />

- [Hacer Click para contactar vía website.](https://github.com/neherlab/covid19_scenarios) 

## Comparador de países

Generador de estadística comparando parámetros de diferentes países.
<img src="https://i.postimg.cc/BvSBDGXj/Screen-Shot-2020-04-04-at-14-39-11.png" width=60% />
- [Hacer Click para tener acceso al Panel.](https://bibbase.org/other/covid-19)

## Paneles estadísticos

Componentes para gráficas visuales estadísticas.
- [Hacer Click para tener acceso vía Sitio web.](https://covid19dashboards.com)

## AppJennifer

Esta plataforma  identifica a las personas con fiebre en la oficina / espacio de trabajo compartido. Esta herramienta utiliza sensores térmicos que detectan a los compañeros de trabajo con temperatura corporal elevada. Estadísticamente, el 90% de los empleados en los Estados Unidos vienen a trabajar mientras están enfermos. La plataforma automatiza la identificación temprana de personas que padecen fiebre en el trabajo por diversos motivos, incluidos coronavirus, gripe, resfriado común, rinovirus, etc.

- [Hacer Click para contactar vía website.](http://appjennifer.com/)

## Dataset científico del COVID-19
Transforma los data de CSSEGISandData/COVID-19 en un archivo de base de datos no estructurada (JSON).

```
{
  "Thailand": [
    {
      "date": "2020-1-22",
      "confirmed": 2,
      "deaths": 0,
      "recovered": 0
    },
    {
      "date": "2020-1-23",
      "confirmed": 3,
      "deaths": 0,
      "recovered": 0
    },
    ...
  ],
  ...
}
```
- [Hacer Click para tener acceso vía Sitio web.](https://github.com/pomber/covid19)


## _Advertencia sobre falacias estadísticas_

_En los últimos días una publicación proveniente de New York ha causado revuelo y atracción de fondos públicos en Francia, vinculando la aplicación de la vacuna BCG con la baja proporción estadística de Coronavirus y proponiendo un causal epidemiológico. Esta publicación apresurada carece del método científico para sostener sus conclusiones. La BCG es una vacuna obligatoria en países donde la Tuberculosis no se encuentra erradicada; es decir, países en "vías de desarrollo". Estos son coincidentemente países donde la disponibilidad de reactivos de laboratorio para identificar el SARS-CoV2 es menor que en aquellos países donde la Tuberculosis ha sido erradicada y donde la aplicación de BCG usualmente no se encuentra en el calendario obligatorio de vacunación. Este caso nos invita a reflexionar sobre el tipo de información que divulgamos y cómo la obtenemos, para evitar encontrarnos en manos oportunistas._
