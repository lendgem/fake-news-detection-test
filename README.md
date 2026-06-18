# fake-news-detection-test
Repositorio de código y fuentes para realización de TFM  
**"Comparativa de modelos explicables para la detección automática de noticias falsas en español"**

---

## Contenido del repositorio

En el siguiente repositorio se puede encontrar (en formato de cuadernos Jupyter Notebook):

- **Códigos de preparación de datos iniciales** para entrenar modelos.
- **Códigos de entrenamiento y evaluación de efectividad de modelos:**
  - Regresión logística
  - SVM
  - BiGRU (base)
  - BiGRU + CNN
  - BETO
  - BERTIN RoBERTa
- **Códigos de evaluación de explicabilidad de modelos (SHAP)**

---

## Corpus utilizados

### 1. The Spanish Fake News Corpus Version 2.0  
**[FakeDeS Task @ IberLEF 2021]**  
Colección de noticias ciertas y falsas recolectadas desde noviembre de 2020 hasta marzo de 2021.  
La información fue recopilada de dos fuentes principales: páginas web de compañías de medios de comunicación y sitios de verificación de hechos (*fact-checking*).

Para este análisis se revisa el corpus utilizado en la conferencia IberLEF 2021, considerada para evaluar tareas de detección de noticias falsas.  
El corpus está dividido en:
- **Entrenamiento:** versión antigua generada durante IberLEF 2020, compuesta de noticias recopiladas entre enero y julio de 2018.  
- **Test:** colección más nueva centrada en noticias sobre el COVID-19. Incluye un bajo porcentaje de publicaciones de redes sociales clasificadas como falsas.

Fuente: [FakeNewsCorpusSpanish](https://github.com/jpposadas/FakeNewsCorpusSpanish)

---

### 2. Spanish Fake News Dataset (Tretiakov et al., 2025)  
Colección de noticias exclusivamente falsas obtenidas desde diciembre de 2005 hasta octubre de 2021 y publicadas recientemente.  

Los datos poseen formatos variados que incluyen:
- Artículos y titulares de noticias  
- Tweets y publicaciones de Facebook/Instagram/Telegram  
- Transcripciones de videos en YouTube  
- Transcripciones de mensajes de voz y textos de WhatsApp  
- Documentos gubernamentales falsos  
- Extracción de texto de fotos y memes  

Las fuentes principales de estos datos son organizaciones de verificación de hechos: **Maldito Bulo, Newtral y AFP Factual**.  
Esta base de datos fue empleada en el artículo *“Detection of False Information in Spanish Using Machine Learning Techniques”* (Tretiakov et al., 2022).

Fuente: [Zenodo Dataset](https://zenodo.org/records/15592391)

---

## Referencias bibliográficas

- Gómez-Adorno, H., Posadas-Durán, J. P., Enguix, G. B., & Capetillo, C. P. (2021). *Overview of FakeDeS at IberLEF 2021: Fake News Detection in Spanish Shared Task*. Procesamiento del Lenguaje Natural, 67, 223-231.  
- Aragón, M. E., Jarquín, H., Gómez, M. M. Y., Escalante, H. J., Villaseñor-Pineda, L., Gómez-Adorno, H., ... & Posadas-Durán, J. P. (2020, September). *Overview of mex-a3t at iberlef 2020: Fake news and aggressiveness analysis in mexican spanish*. In Notebook Papers of 2nd SEPLN Workshop on Iberian Languages Evaluation Forum (IberLEF), Malaga, Spain.  
- Posadas-Durán, J. P., Gómez-Adorno, H., Sidorov, G., & Escobar, J. J. M. (2019). *Detection of fake news in a new corpus for the Spanish language*. Journal of Intelligent & Fuzzy Systems, 36(5), 4869-4876.  
- Tretiakov, A., Martín, A., & Camacho, D. (2022). *Detection of False Information in Spanish Using Machine Learning Techniques*. En H. Yin, D. Camacho, & P. Tino (Eds.), Intelligent Data Engineering and Automated Learning – IDEAL 2022 (pp. 42-53). Springer International Publishing. https://doi.org/10.1007/978-3-031-21753-1_5  
