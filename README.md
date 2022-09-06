# Proyecto final: "Professional Data Science DEVF"

# Análisis exploratorio del top 50 Gobal más escuchado de Spotify
## ¿Qué tienen de especial las canciones más escuchado en el mundo en Spotify?

----------------------------
<p align="center"> <img alt="Coding" width="400" src="https://developer.spotify.com/assets/FBImage.png"> </p>
<p align="center"> <img alt="Coding" width="200" src="https://i.scdn.co/image/ab67706c0000bebbee2440a8fd4602006216f55f"> </p>

----------------------------

### *Por: Julio César Avila Torreblanca* ([julio-avt](https://github.com/julio-avt))

### Resumen:
En este trabajo se realiza una conexión a la API de Spotify para obtener información sobre las canciones contenidas en una playlist (top 50 más escuchadas). Depués de ello se analiza la información extraida para realizar un estudio estadístico y obtener insights.

### Información sobre el proyecto:
Este proyecto analiza una playslist de spotify. Particularmente se analizo la playlist con el top 50 Global de spotify ([link](https://open.spotify.com/playlist/37i9dQZEVXbMDoHDwVN2tF?si=1367122882d04888)), pero puede replciarse con cualquier otra playlist pública.

### Conexión a la API de Spotify
Para poder acceder a la API de Spotify y extraer la información de las canciones en la playlist, se requieren de dos llaves. Los pasos para obtener estas llaves son:

1. Iniciar sesión (si ya se tiene cuenta de spotify y si no se debe crear una) en la página de **Spotify for developers** ([link](https://developer.spotify.com/dashboard/login)).

<p align="center"> <img alt="Coding" width="600" src="https://i.imgur.com/PzUkWHn.png"> </p>

2. Una vez inciada sesión, se te mostrará tu dashboard. Hay que crear una nueva app (o si ya se tiene utilizar ese). Esta app lleva un título y descripción.

<p align="center"> <img alt="Coding" width="900" src="https://i.imgur.com/TbGbqA2.png"> </p>
<p align="center"> <img alt="Coding" width="400" src="https://i.imgur.com/11pSnUm.png"> </p>

3. Ya creado el proyecto, ingresamos en el mismo y seleccionamos que se nos muestre las llave oculata.

<p align="center"> <img alt="Coding" width="600" src="https://i.imgur.com/zFK6uot.png"> </p>

4. Finalmente guardamos los valores de *Client ID* y *Client Secret* (en la imagen se han tapado ya que son llaves personales).

<p align="center"> <img alt="Coding" width="600" src="https://i.imgur.com/YJi6ZaZ.png"> </p>

### ¿Cómo correr el código?
1. Instalación previa de paquetes necesarios para python `requierements.txt`
2. Obtener las llaves para establecer la conexión con la API (revisar tutorial arriba).
3. Descargar los notebooks `Secrets.ipynb` y `Top50Global_Spotify.ipynb` en la misma carpeta.
3. Abrir el notebook `Secrets.ipynb` y colocar los valores de las vaibles: *ClientID* y *ClientSecretID* con sus llaves correspondientes. Y ejecutar este archivo.
4. Abrir el notebook `Top50Global_Spotify.ipynb` y ejecutarlo.
- **Extra:** si se quiere usar otra playslist (debe ser pública), hay que redefinir la variable ***playlist_link_Top50Global*** con el link de la nueva playlist. 
