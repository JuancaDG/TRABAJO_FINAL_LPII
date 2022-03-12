# TRABAJO_FINAL_LPII
Web Scraping (Trabajo colaborativo en git hub)

Lo primero que hicimos fue guiarnos de los 20 ejemplos de la pagina de la profesora que nos brindo  
https://www.projectpro.io/article/web-scraping-projects-ideas/475#mcetoc_1fet0v40ha  
y quisimos escoger el proyecto numero1 el cual consistia en scrapear la pagina de amazon para luego    
analaizar las reseñas de sus clientes.  
quisimos guiarnos de un video de youtube pero al momento de correr los codigos no se podia tratamos   
de ver los errores viendo linea por linea pero el resultado era el mismo y no ponia muchas trabas la pagina de    
amazon , asi que ya teniendo base decidimos cambiar de mercado, ahora con "MERCADO LIBRE" y nos fue mucho mas    
accesible hacer el requests (el requerimiento) para poder scrapear.  


# ALCANCES:

### NUESTRO PROYECTO CONSISTE  
- Este proyecto consiste en web scrapear una pagina de nuestro interes el cual escogimos "mercado libre"  
- Tenemos que ingresar a nuestro nuestro codigo la direccion de algun producto deseado.  
- El cual nos brindara la primera pagina del producto deseado con diferentes precios y caracteristicas de este tipo 
  de producto, el cual nuestro codigo recorrera y scrapeara todos los titulos de los productos y url de cada uno de estos.
- Luego de obtener titulos y url de cada producto , escoregemos uno de estos en especifico y copiaremos su url en nuestro codigo para    
  poder saber los comentarios(preguntas de los consumidores y respuesta del vendedor) de uno de los productos de la primera pagina.
 - Una ves obtenido los comentarios los ordenaremos en un data frame para luego tenerlos en archivo csv.

# LIMITACIONES:
 Bueno tratar de explicar en que consiste el codigo de principio a fin es algo difil de concluir en un trabajo colaborativo ya que mientras  
 pasan los dias se busca mejorar el codigo en partes que no nos damos cuenta al inicio y vamos percatandonos conforme cada uno da su aporte  
 en el trabajo y se les ocurre nuevas ideas y por ensayo y error descubrimos modificaciones.  
 Por ejemplo al inico poniamos la url fija, pero luego nos dimos cuenta que si poniamos una funcion input de entrada era mas dinamico y vistoso.
 
 Bueno las limitaciones en nuestro codigo serian:  
 - Por ejemplo cuando scrapeamos la primera pagina de todos los  "zapatos mocasines" nos da todo los titulos y url del productod de esa pagina  
  que eran 52 tipos de zapatos en la primera pagina,pero nos dimos con la sorpresa que cuando agregaron una promocion de zapato no lo scrapeaba  
  nuestro codigo, asi que supisimos que podia ser por que estaba en otra class de la estructura del html y estabamos viendo la forma de como incluirlo.  
 - El otro problema fue cuando bucamos el producto jamon, nos salieron como 50 productos relacionado a jamones y cuando scrapeamos salio los titulos  
   de todos estos productos, " PERO no nos salia las url " nos salia una lista vacia, nos dimos cuenta que era por la class que teniamos que  
   que cambiar para otro producto.
   
 Estas serian las limitaciones de nuestros codigo, en la parte de obtener las url para otro productos no se puede o si sale nuevos productos de promocion  
 no los quiere leer.
 En la parte de scrapear los comentariso de las personas y vendedores de cada producto si nos salia para cualquier url escogida no habia problema,  
 podiamos escoger cualquier variedad de producto, obtendreos igual comentarios.  
 
 Nuestro objetivo es ir modificando y mejorando algunas cosas del codigo para que sea mas util al scrapear nuestro producto, para luego ponerlo en  
 un archivo csv  con los datos mas relevantes e interesantes.  
 
 
 
  













