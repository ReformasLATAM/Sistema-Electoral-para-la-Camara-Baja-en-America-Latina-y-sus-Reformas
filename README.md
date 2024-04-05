# Sistema Electoral para la Cámara Baja en América Latina y sus Reformas

Bienvenidos/as al repositorio GitHub de la base de datos "Sistema Electoral para la Cámara Baja en América Latina y sus Reformas", mantenida por integrantes del Observatorio de Reformas Políticas en América Latina.

## Contenidos

-   [Resumen](#resumen)
-   [Descripción](#descripción)
-   [Citado](#citado)

## Resumen

La base de datos contiene información sobre las reformas electorales a la normativa que regula el sistema electoral de las cámaras bajas nacionales de 19 países de América Latina. En la base de datos hay información sobre las modificaciones en el principio de representación, fórmula electoral, presencia de circunscripción especial, magnitud de la cámara, número de distritos electorales, estructura del voto, mandato, barrera legal, así como reelección y revocación legislativas.

La revisión de la normatividad se realizó a partir del año de la transición a la democracia de cada país, con base en lo planteado por Alcántara; Paramo; Freidenberg y Déniz (2006). En el caso de los países con procesos de cambio político graduales, se utiliza como base el año de inicio de la tercera ola de la democracia en América Latina (Huntington, 1991).

Integrantes del Observatorio de Reformas Políticas en América Latina recopilaron y codificaron la información. Las personas responsables de la recopilación de los datos son Flavia Freidenberg (Instituto de Investigaciones Jurídicas); Karolina Monika Gilas (Facultad de Ciencias Políticas y Sociales, UNAM) y Luciana Modica (Universidad Nacional de Río Cuarto, Argentina), mientras que la persona responsable de la codificación de los datos es Carlos Guadarrama Cruz (FLACSO, México). 

## Descripción

El directorio `./Data/` contiene el archivo `./Data/DD_SECB` en el cual se encuentra toda la información relevante respecto a la base de datos del sistema electoral de la Cámara Baja y sus reformas. En específico, la base de datos se compone de las siguientes variables:

-   `país`: nombre del país en el cual se llevó a cabo la reforma al régimen electoral ejecutivo en América Latina.

-   `cowcode`: código del país de acuerdo con la codificación de “Correlates of War”
https://correlatesofwar.org/data-sets/cow-country-codes.

-   `siglas_pais`: siglas del país de acuerdo con el código de tres letras ISO (por ejemplo: ARG, MEX, SAL) disponible en: http://utils.mucattu.com/iso_3166-1.html 

-   `consec_reforma_pais`: registra el número consecutivo de las reformas al régimen electoral ejecutivo en cada país de América Latina. Ejemplo: Peru_1 Peru_2, Peru_3, Peru_4.

-   `año`: año calendario al que corresponde la reforma al régimen electoral del ejecutivo en cada país de América Latina entre 1949-2023.

-   `principio_repre`: indica el principio de representación política que rige la elección de los miembros de la cámara baja nacional del poder legislativo nacional en cada país. Sus valores [1]: Mayoritario [2]: Proporcional; [3]: Mixto

-   `form_elec_n`: indica la fórmula de conversión de votos en escaños establecida en la reforma electoral para la cámara baja del poder legislativo nacional. Sus valores [1]: Cifra repartidora;  [2]: D ́Hondt; [3]: Cociente o residuo electoral; [4]: Hare y restos mayores; [5] Hare modificada; [6]: Imperiali corregido; [7]: Factor ponderado; [8]: Webster; [9]: Hagenbanch-Bischoff; [10]: Sistema proporcional integral; [11]: Mayoría absoluta; [12]: Mayoría relativa; [99]: No aplica.

-   `circunsc_esp`: indica la presencia de circunscripciones electorales especiales asignadas para la elección de algunos miembros de la cámara baja del poder legislativo nacional; por ejemplo, comunidades indígenas, población en el extranjero, etc. Sus valores [0]: No específica; [1]: Si específica

-   `m_camara`: indica el número de escaños que la reforma electoral establece para la cámara baja del poder legislativo nacional.

-   `distr_elec_n`: indica el número de distritos electorales que la reforma electoral establece para la cámara baja del poder legislativo nacional por principio de representación política.

-   `estructura_vot_n`: indica el tipo de voto que establece la reforma electoral para la cámara baja del poder legislativo nacional por principio de representación política. Sus valores [1]: Candidatura uninominal; [2]: Lista cerrada y bloqueada; [3]: Lista cerrada y no bloqueada; [4]: Lista cerrada, no bloqueada y voto preferencial doble; [5]: Lista cerrada, no bloqueada y voto preferencial y opcional; [6]: Lista abierta;  [7]: Lista abierta y voto preferente; [8]: Lista única vinculada a candidatura presidencial; [9]: Voto preferente; [10]: Doble voto simultáneo; [11]: Doble voto preferencial opcional; [12]: Voto por un candidato en listas de partido; [13]: Mixto.

-   `mandato`: duración del mandato de los miembros de la cámara baja en años fijado por la reforma electoral.

-   `barrera_legal`: indica si la reforma electoral plantea la existencia o inexistencia de barreras legales para el acceso de los partidos políticos al reparto de escaños de la cámara baja del poder legislativo nacional. Sus valores: [0]: No específica; [1]: Si específica.

-   `reelección_legis`: indica la manera en que la reforma electoral regula la reelección de los miembros de la cámara baja del poder legislativo nacional. Sus valores:  [1]: No reelección; [2]: No reelección inmediata; [3]: Reelección inmediata; [4]: Reelección inmediata e indefinida; [5]: Reelección inmediata por dos períodos;

-   `revoca_legis`: indica si la reforma electoral considera la existencia o inexistencia de la revocación legislativa para los miembros de la cámara baja del poder ejecutivo nacional. Sus valores: No [0]: la normativa no considera la existe de revocación legislativa; Sí [1]: la normativa considera la existe de revocación legislativa.

## Citado

``` r
Freidenberg, Flavia. Dir., 2023, “Sistema electoral para la Cámara Baja en América Latina y sus reformas”, Observatorio de Reformas Políticas en América Latina (1978-2023). Ciudad de México: Instituto de Investigaciones Jurídicas (IIJ-UNAM) y Washington, D.C.: Secretaría para el Fortalecimiento de la Democracia de la Organización de los Estados Americanos (SFD/OEA), V2. DOI: https://doi.org/10.5281/zenodo.8368074 
```