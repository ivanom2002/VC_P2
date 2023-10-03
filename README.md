# VC_P2

En esta práctica hemos elaborado varias tareas usando funciones como Sobel y Canny. Además, se han aplicado técnicas de substracción de fotorgramas.

Tarea 1: Para esta tarea, hemos realizado la cuanta de píxeles blancos tanto por filas como por columnas. Una vez realizada la cuenta, determinamos cuál es el número máximo de píxeles blancos por filas y por columnas y contamos el número de filas y columnas que tenían un número de píxeles blancos superior a 0.95*máximo. Para ello hemos usado funciones como max, cv2.reduce y np.count_nonzero.

Tarea 2: Para esta tarea, hemos escogido la imagen leon.jpg y lo que hemos hecho ha sido mostrar las imágenes resultantes de aplicar Sobel de manera vertical, horizontal y combinada antes y después de ajustar su escala.

Tarea 3: Para esta tarea, hemos convertido la imagen resultante de Sobel a 8 bits y posteriormente le hemos aplicado un umbralizado. Por otro lado, hemos realizado un conteo del número máximo de píxeles blancos tanto por filas como por columnas, de forma similar a la tarea 1. En este caso, se han resaltado además las filas y columnas cuyo número de píxeles blancos superan 0.95*máximo. Para diferenciar los resultados entre Sobel y Canny diríamos que Sobel ofrece mucho más detalle de la imagen. Sin embargo, como hemos utilizado una imagen diferente a la de la tarea 1 es difícil comparar los resultados entre ambas tareas.

Tarea 4: Para esta tarea, hemos aplicado a la entrada de la webcam un filtro resultante de haber usado Sobel con la escala ajustada. Por otro lado, hemos usado un filtro resultante de haber usado canny, dejando así dos salidas en las que se puede apreciar lo dado en esta práctica.

Tarea 5: Para esta tarea, hemos intentado poder cambiar el volumen del ordenador a través de una interfaz creada a partir de la webcam, en donde subimos y bajamos con nustros propios dedos una barra, cambiando así el volumen del mismo. Hemos dividido la entrada en dos frames, uno en donde vemos la barra de manera visual y todo a color, y en el otro frame, solo vemos un cacho del frame original, para poder usar un filtro donde en escala de grises solo vemos movimiento y con dos loops for, vemos el píxel blanco más alto en la Y para poder así ajustar la barra del frame original.
