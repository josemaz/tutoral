---
title: Cambios en los patrones genéticos y epigenéticos en las etapas de progresión del cáncer
subtitle: José María Zamora Fuentes
comite: "Comité Tutoral: Dr. Jesús Espinal Enríquez <br>
Dra. Patricia García López <br>
Dr. Luis Mendoza Sierra"
date: Junio, 2022
institute: Universidad Nacional Autónoma de México
css: file.css
theme: white
slideNumber: h.v
---

### Tópicos
- Introducción
- Hipótesis
- Objetivo
- Métodos y materiales
- Resultados
- Resumen

### Cáncer
<img src="./img/Cancer.png">


### Progresión del Cáncer
<img src="./img/Etapas.png" width="70%">
<p style="font-size: 12px; text-align: left;">
<a target="_blank" href="">[1]</a> Stephen B. Edge, et al. "The American Joint Committee on Cancer: the 7th Edition of the AJCC Cancer Staging Manual and the Future of TNM". Annals of Surgical Oncology 17. 6(2010): 1471–1474.</p>


### Regulación genética y epigenética 
<img src="img/Regulacion.png" width="90%">

### Metilación
<img src="img/Methylation.png" width="90%">
<p style="font-size: 12px; text-align: left;">
<a target="_blank" href="">[1]</a>Modificado de Michalak EM, Burr ML, Bannister AJ, Dawson MA. The roles of DNA, RNA and histone methylation in ageing and cancer. Nat Rev Mol Cell Biol. 2019;20(10):573-589.</p>

### Metilación
<img src="img/beta.png" width="90%">
<p style="font-size: 12px; text-align: left;">
<a target="_blank" href="">[1]</a>Modificado de Michalak EM, Burr ML, Bannister AJ, Dawson MA. The roles of DNA, RNA and histone methylation in ageing and cancer. Nat Rev Mol Cell Biol. 2019;20(10):573-589.</p>

### Fuentes de datos
- TCGA (The Cancer Genome Atlas)
	- 11,300 pacientes 
	- más de 30 tejidos de cáncer.
	- Secuenciación RNA
		- mRNA 
	- Secuenciación de 450K sitios CpG
<p style="font-size: 12px; text-align: left;">
<a target="_blank" href="">[1]</a>The Cancer Genome Atlas Research Network. "Before and After: Comparison of Legacy and Harmonized TCGA Genomic Data Commons Data". Cell Systems. 2019;9(1):24-34.e10.</p>

<aside class="notes">
Que es un experimento RNAseq?
Que es un experimento de miRNAs?
Como se hace la secuención de sitios CpG?
</aside>


### Hipótesis
Existen **posibles mecanismos** de control regulatorio llevados a cabo por miRNAs y por metilación sobre genes involucrados en la progresión del cáncer.


### Objetivo
Encontrar **genes clave** que son afectados por **miRNAs** o por **metilación**, los cuales cambian su programa regulatorio y de **co-expresión** durante <br> la progresión del cáncer.


### Métodos y materiales

### Flujo de trabajo
<img src="img/workflow-phd.png" width="90%">

### Carcinoma Renal
- Cáncer "silencioso" (ausencia de síntomas).
- 80% de los casos se diagnostican de manera incidental en imágenes solicitadas por otros motivos,
- de estos, el 20 % son diagnosticados en etapas avanzadas,
- la tasa de mortalidad es del 95% a los 5 años.
<p style="font-size: 14px; text-align: left;">
<a target="_blank" href="">[2]</a>James J. Hsieh, et al. "Renal cell carcinoma". Nature Reviews Disease Primers 3. 1(2017).</p>

### CRcc - Características Moleculares
- 85% se encuentran en células claras.
- Línea principal:  Mutaciones en VHL.
- Pérdida en VHL no induce ccRC.
- Biomarcadores de metilación no especificados.
- Histopatalogía con alta degradación de MEC (regado de estroma)
<p style="font-size: 14px; text-align: left;">
<a target="_blank" href="">[2]</a>James J. Hsieh, et al. "Renal cell carcinoma". Nature Reviews Disease Primers 3. 1(2017).</p>

### Muestras de ccRC
| Control | Etapa I  | Etapa II | Etapa III | Etapa IV |
|:-------:|:--------:|:--------:|:---------:|:--------:|
|  72     |  272     |   59     | 123       | 82       |



### Metiloma
<img src="img/meandesc.png" width="80%">

### Agrupamiento del metiloma
<img src="img/heatmap-1e5.png" width="80%">

### Sitios CpGs diferencialmente metilados
<img src="img/NTvsStage1.png" width="80%">

### Algoritmo de metilación diferencial
<img src="img/pipeline-meth.png" width="80%">

### Ejemplo: Gen Hipermetilado (ERMP1) 
<img src="img/under-ERMP1.png" width="60%">

### Ejemplo: Gen Hipometilado (IL32)
<img src="img/over-IL32.png" width="60%">

### Genes afectados por la metilación
<img src="img/meth-venns.png" width="100%">

### Criterio funcional (Hipometilados)
<img src="img/meth-overHipo.png" width="70%">

### Criterio funcional (Hipermetilados)
<img src="img/meth-underHyper.png" width="90%">

### Enriquecimiento funcional de las 4 etapas
| Metilación    | Gene núcleo   | Función Biológica  |
|:------------- |:-------------:| -----:|
|  hypo         | ITK           | Activación de células T |
|  hyper        | RAB25         |   Supresor tumoral      |

### RAB25: Funciones en cáncer
<img src="img/RAB25-func.png" width="70%">
<p style="font-size: 12px; text-align: left;">
<a target="_blank" href="">[1]</a>Wang S, et al. Rab25 GTPase: Functional roles in cancer. Oncotarget. 2017;8(38):64591-64599</p>


### Infiltración
<img src="img/inmune.png" width="90%">


### Implicaciones
- La metilacion puede apagar un supresor tumoral (RAB25) en las etapas del cancer
- En las 4 etapas puede haber inflitracion de celulas del sistema inmune que cambiaron su patron de metilacion en ciertos genes importantes (ITK) en sus desarrollo.
- Esta metodologia puede reproducir los 

### Trabajo futuro
- Usar esta metodología para evaluar los siguientes tejidos de cáncer.
- Escribir la tesis doctoral.

### Agradecimientos
- Comité tutoral.
- Comité del exámen de candidatura.
- CONACYT (cvu 267236).
- UNAM, IE e INMEGEN.

### Resultados académicos
<p style="font-size: 24px; text-align: left;">
**1--**  Curso de Biología Molecular (Dr. Felix Recillas)
**2--**  Exámen de Candidatura
**4--**  *Zamora-Fuentes JM*, Hernández-Lemus E, Espinal-Enríquez J. **methylation-driven gene networks in Clear Cell Renal Carcinoma** (*Enviado*). <br>
**4--**  *Zamora-Fuentes JM*, Hernández-Lemus E, Espinal-Enríquez J. **miR-217 regulates different oncogenes during clear cell renal carcinoma progression** (*En revisión, Frontiers in Oncology*). <br>
**5--** *Zamora-Fuentes JM*, Hernández-Lemus E, Espinal-Enríquez J. **Gene Expression and Co-expression Networks Are Strongly Altered Through Stages in Clear Cell Renal Carcinoma.** Front Genet. 2020;11:578679. Published 2020 Nov 3. <br>
**6--**  González-Espinoza A, *Zamora-Fuentes JM*, Hernández-Lemus E, Espinal-Enríquez J. **Gene Co-Expression in Breast Cancer: A Matter of Distance.** Front Oncol. 2021;11:726493. Published 2021 Nov 17. <br>
**7--**  Andonegui-Elguera SD, *Zamora-Fuentes JM*, Espinal-Enríquez J, Hernández-Lemus E. **Loss of Long Distance Co-Expression in Lung Cancer.** Front Genet. 2021;12:625741. Published 2021 Mar 10. <br>
</p>


### Apendice

### Microambiente
<img src="img/microambiente.png" width="80%">
<p style="font-size: 14px; text-align: left;">
<a target="_blank" href="">[1]</a>Yoshihara K, Inferring tumour purity and stromal and immune cell admixture from expression data. Nat Commun. 2013;4(1):2612.
</p>

### ccRC - CNVS (Amplificaciones)
<img src="img/CNVS-expr-amps-kirc.png" width="80%">

### Mutaciones en ccRC
<img src="img/mutaciones.png" width="60%">

### Cáncer en México
<img src="img/globocan-cancer-kidney-mex.png" width="80%">
<p style="font-size: 14px; text-align: left;">
<a target="_blank" href="">Globocan  </a>https://gco.iarc.fr/today</p>

### Aumento de Cáncer de riñon en hombres
<img src="img/globocan-time-kidney-mex.png" width="50%">



