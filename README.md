# 🎮 **Steam Review Scraper**

Extrae datos textuales de los comentarios de [Steam](https://store.steampowered.com/) y realiza un análisis de sentimientos y emociones, generando estadísticas cuantitativas y visualizaciones gráficas para su interpretación.

## **Obtención de los datos**

Para llevar a cabo el proyecto, hicimos una búsqueda de los datos de las dos formas posibles que ofrece **Steam**, mediante **web scraping** y usando su **API**.

Aunque para trabajar con los datos solo utilizaremos la **API**, ya que el **web scraping** es mucho más costoso y tarda cantidades de tiempo muy elevadas y en cambio, con la **API** podemos obtener más datos en mucho menos tiempo.

Utilizaremos como ejemplo el juego: [**Call of Duty®: Black Ops 7**](https://store.steampowered.com/app/3606480/Call_of_Duty_Black_Ops_7/)

El cual salió el 14 de noviembre de 2025.

![cod: black ops 7](/img/header.jpg)

**Documentación: [API OFICIAL](https://partner.steamgames.com/doc/store/getreviews?l=spanish&language=english)**

## **Exploración y visualización de los datos**

Hemos limitado el conjunto de datos a **3000 reseñas** para evitar tiempos de carga largos al descargar los comentarios.

![Distribución de la longitud de las reseñas](/img/distribution_of_review_length.png)

![Porcentaje de reseñas recomendadas](/img/percentage_of_recommended_reviews.png)

## **Matriz de confusión**

![Matriz](/img/matriz.png)

## **Créditos**

Hecho por [**Alejandro Barrionuevo Rosado**](https://github.com/Alejandro-BR) y [**Alvaro López Guerrero**](https://github.com/Alvalogue72).

**Máster de FP en Inteligencia Artificial y Big Data**

<img src="./img/alan_turing.png" width="150"/>
