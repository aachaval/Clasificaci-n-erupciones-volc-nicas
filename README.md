Clasificación de erupciones volcánicas

Reto a desarrollar
Jorge es un geólogo del IGME (Instituto Geológico y Minero de España) que está desarrollando un nuevo sistema de prevención de erupciones para poder predecir qué tipo de erupción tendrá un volcán según las las vibraciones detectadas por sus sensores durante los días previos a la erupción. Esto permitirá reducir el riesgo de víctimas y destrozos materiales por este tipo de catástrofe natural.

El sistema de Jorge trabaja con 5 tipos de erupciones:

Pliniana: Se caracteriza por su alto grado de explosividad, con manifestaciones muy violentas en las cuales se expulsan grandes volúmenes de gas volcánico, fragmentos y cenizas.

Peleana: La característica más importante de una erupción peleana es la presencia de una avalancha brillante de ceniza volcánica caliente, llamada flujo piroclástico.

Vulcaniana: Son erupciones volcánicas de tipo explosivo. El material magmático liberado es más viscoso que en el caso de las erupciones hawaianas o estrombolianas; consecuentemente, se acumula más presión desde la cámara magmática conforme el magma asciende hacia la superficie.

Hawaiana: Consiste en la emisión de material volcánico, mayoritariamente basáltico, de manera efusiva o no explosiva. Ocurre de este modo debido a que la difusión de los gases a través de magmas más básicos (basálticos) puede hacerse de manera lenta pero más o menos continua. Consecuentemente, las erupciones volcánicas de este tipo no suelen ser muy destructivas.

Estromboliana: La erupción Estromboliana está caracterizada por erupciones explosivas separadas por periodos de calma de duración variable. El proceso de cada explosión corresponde a la evolución de una burbuja de gases liberados por el propio magma.

El objetivo de este reto será ayudar a Jorge realizando el modelado predictivo a partir de un dataset que contiene las mediciones hechas por sus sensores y tipos.

Datasets
Variables del dataset:

Features: El dataset contiene 6 features en 6 columnas, que son los parámetros medidos por los diferentes sensores. Estos corresponden a las vibraciones detectadas en ciertos puntos de la ladera del volcán.

Target: El target corresponde al 'label' que clasifica los tipos de erupciones volcánicas en función de los features medidos por los sensores.

Target 0 corresponde a una erupción de tipo Pliniana
Target 1 corresponde a una erupción de tipo Peleana
Target 2 corresponde a una erupción de tipo Vulcaniana
Target 3 corresponde a una erupción de tipo Hawaiana
Target 4 corresponde a una erupción de tipo Estromboliana
Archivos:
jm_train.csv: Este dataset contiene tanto las variables predictoras como el tipo de erupción.

jm_test_X.csv: Este dataset contiene las variables predictoras con las que se tendrá que predecir el tipo de erupción.

Objetivo
El objetivo del reto será realizar un modelo predictivo basado en Random Forests que permita conocer el tipo de erupción que tendrá un volcán en función de las vibraciones medidas por los sensores.
