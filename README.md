# VC_P2

En esta práctica hemos elaborado varias tareas usando funciones como Sobel y Canny. Además, se han aplicado técnicas de substracción de fotorgramas.

Tarea 1: Para esta tarea, hemos realizado la cuanta de píxeles blancos tanto por filas como por columnas. Una vez realizada la cuenta, determinamos cuál es el número máximo de píxeles blancos por filas y por columnas y contamos el número de filas y columnas que tenían un número de píxeles blancos superior a 0.95*máximo. Para ello hemos usado funciones como max, cv2.reduce y np.count_nonzero.

Tarea 2: Para esta tarea, hemos escogido la imagen leon.jpg y lo que hemos hecho ha sido mostrar las imágenes resultantes de aplicar Sobel de manera vertical, horizontal y combinada antes y después de ajustar su escala.

Tarea 3: Para esta tarea, hemos convertido la imagen resultante de Sobel a 8 bits y posteriormente le hemos aplicado un umbralizado. Por otro lado, hemos realizado un conteo del número máximo de píxeles blancos tanto por filas como por columnas, de forma similar a la tarea 1. En este caso, se han resaltado además las filas y columnas cuyo número de píxeles blancos superan 0.95*máximo.
