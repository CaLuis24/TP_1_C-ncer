# Introducción.
La zona del Pacífico Norte, que comprende principalmente la provincia de Guanacaste, es muy importante en aspectos económicos, sociales, culturales; para nuestro país, ya que, es una de las zonas con más auge turístico, debido a su enorme belleza. Pero también, es muy relevante en temas agrícolas, donde la producción de arroz y frijol, por ejemplo, está muy extendida y es característica de la zona, siendo dos productos esenciales en la dieta del costarricense.  
En términos de esta investigación, la zona de interés comprende los alrededores de la cuenca del río Tempisque, identificando zonas implementadas para la agricultura, se realizará un análisis de vegetación de estas áreas, para así identificar los períodos del año, que abarcan desde el 2018 al 2020, donde el clima es más determinante hacia los cultivos, por ejemplo, el período seco de Guanacaste, que es tan extenso e intenso. A raíz de esto, se implementó el Distrito de Riego Arenal-Tempisque (DRAT), que consiste en la distribución del riego de agua sobre fincas utilizadas para la agricultura, con el fin de no perder las cosechas en los períodos de época seca (Wong, 2021).  
Todo esto se realizará con la ayuda de imágenes satelitales (Landsat 8) y con el Google Earth Engine (GEE). Mediante índices, donde se podrá identificar el estado de la vegetación. Por ejemplo, el índice de vegetación (NDVI), donde esta, según Pedro Muñoz (2013), ayudará a identificar zonas con ausencia de vegetación, donde los valores negativos indican superficies con poca vegetación. Otro índice a utilizar, es el índice de vegetación mejorado (EVI), según un estudio, este es útil sobre vegetaciones densas y en reducción de influencias atmosféricas, además es sensible a variaciones del dosel y del área foliar de la vegetación. (Posada et al., 2019). Por último, el índice de clorofila verde (GCI), que acorde a una investigación, este sirve para trabajar sobre masas vegetales, para calcular su nivel de clorofila, mediante las bandas del verde visible y el infrarrojo (Gisandbeers, 2019).  

### Metodología.
 Por medio de la plataforma de Google Earth Engine, el uso de imágenes satelitales y un lenguaje de JavaScript se realizaron procesos geoespaciales para lograr realizar un análisis de las imágenes en el distrito de riego Arenal-Tempisque. Durante esta fase del procesamiento: creación del polígono de la región de riego, en el cual se iba utilizar (importar) la colección de imágenes de Servicio Geológico de Estados Unidos (USGS) Landsat 8 Collection 1 Tier 1 calibrated top-of-atmosphere (TOA) reflectance, entre los años 2018 y 2021 en periodos de 2 meses y en algunos casos de 1 mes, en la estación seca y lluviosa. Esta colección de imágenes cuenta con alrededor de 11 bandas que van desde una resolución de 30 y unas de 15 metros y con longitud de ondas desde 0.43 - 12.51 µm, y con una frecuencia de aproximadamente 16 días (Tabla 1).  



