# 13222 - Análisis de Datos

Asignatura teórico-práctica que tiene como finalidad introducir a los estudiantes en las técnicas para transformar datos en conocimiento, a través de su caracterización, separación y modelación, para analizar o predecir un fenómeno.

- **Carrera:** Ingeniería Civil Informática
- **Requisitos:** Inferencia y Modelos Estadísticos
- **Horas presenciales a la semana:** 6

## Objetivo General: 
- Analizar y relacionar conjuntos de datos multivariados y/o series temporales para generar información y conocimiento, usando los modelos basados en datos que mejor expliquen el fenómeno modelado. 

## Objetivos Específicos: 
- Representar datos multidimensionales para presentarlos de forma comprensible para su posterior análisis. 
- Aplicar técnicas para identificar características en los datos que permiten su agrupamiento. 
- Diseñar y evaluar clasificadores usando diferentes paradigmas de representación del conocimiento.
- Modelar linealmente relaciones entre señales y series temporales de datos, con la finalidad de realizar predicciones.

## Unidades y contenidos
1. Introducción 
2. Análisis de Componentes Principales (ACP)
3. Análisis de agrupamientos
4. Reglas de asociación
5. Análisis discriminante
6. Clasificación Bayesiana 
7. Árboles de decisión 
8. Análisis de series temporales 

## Evaluación

### Cátedra (60% de nota final)
```R
PEPS = c(PEP1, PEP2, PEP3)

if ((PEP1 >= 4 && PEP2 >= 4 && PEP3 >= 4) || mean(PEPS) >= 5){
	CATEDRA = mean(PEPS)
}
else{
	PEPS = c(PEPS, PA, PA)
	CATEDRA = mean(tail(sort(PEPS), 4))
}
```

### Laboratorio (40% de nota final)
```R
LABS = c(L1, L2, L3, L4, L5, L6)
LAB = mean(LABS)
```

### Nota final
```R
if (CATEDRA >= 4 && LAB >= 4){
	FINAL = 0.6*CATEDRA + 0.4*LAB
	cat("APRUEBA CON", FINAL)
}
else{
	FINAL = min(CATEDRA, LAB)
	cat("REPRUEBA CON", FINAL)
}
```

## Fuentes de información

### Directa
 - Introducción a la Minería de datos, Hernandez, Ramirez y Ferri, Prentoce Hall, 2004. 
 - Multivariate Statistical Methods: A primer. B.F.J. Manly, Chapman &may/CRC, London, 2ª Ed. 2000. 
 -  Data Analisys, S. Brandt, Spinger-Verlag. N Y, 3ª Ed. 1999. 
 - Intelligent Data Analisys, M. Berthold and D.J. Hand. Spinger-Verlag. Heidelberg, 2ª Ed. 2003

### Recomendada
- [The Elements of Statistical Learning: Data Mining, Inference, and Prediction. Second Edition. Trevor Hastie, Robert Tibshinari and Jerome Friedman.](https://link.springer.com/content/pdf/10.1007/978-0-387-84858-7.pdf)

## Enunciados laboratorio
1. [Análisis Estadístico](https://www.overleaf.com/read/khyrqwqtbbcq)
2. [Agrupamiento K-Medias](https://www.overleaf.com/read/dzmpmmppkbwt)
3. [Reglas de Asociación](https://www.overleaf.com/read/jzqrgftsnncd)
4. [Clasificador Bayesiano](https://www.overleaf.com/read/xtcykqkqcfrk)
5. [Árboles de Decisión](https://www.overleaf.com/read/rtkvjhvttwgj)
6. [Señales y Sistemas](https://www.overleaf.com/read/zvwnvggpxsdq)

[Formato informe](https://www.overleaf.com/read/ftmpkkkhzcms)

