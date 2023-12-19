# k-NN de números escrito a mano
Este es un clasificador KNN para una base de datos de reconocimiento óptico de un conjunto de datos de dígitos escritos a mano.

## Instrucciones de uso.

- Clona este repositorio en tu máquina local.
- Asegure que el respositorio se haya descargado correctamente.
- Abre el programa que deseas ejecutar en tu entorno de desarrollo que soporte Python 3.11.2 64-bit.
- Asegure de que cuando se ejecute el programa, los archivos para el entrenamiento (optdigits.tra) y de prueba (optdigits.tes) esten en el lugar donde se encuentre el programa (KNN_numeros_mano.py)

El conjunto de datos contiene imágenes de dígitos escritos a mano: 10 clases donde cada clase hace referencia a un dígito.
<br><br>
Son mapas de bits normalizados de dígitos escritos a mano de un formulario preimpreso, estos mapas de bits de 32x32 se dividen en bloques de 4x4 que no se superponen y se cuenta el número de píxeles en cada bloque, esto genera una matriz de entrada de 8x8 donde cada elemento es un número entero en el rango de 0 a 16, esto reduce la dimensionalidad y da invariancia a pequeñas distorsiones.
<br><br>
Para obtener información sobre las rutinas de preprocesamiento del NIST, consulte M. D. Garris, J. L. Blue, G. T. Candela, D. L. Dimmick, J. Geist, P. J. Grother, S. A. Janet y C. L. Wilson, NIST Form-Based Handprint Recognition System, NISTIR 5469, 1994.

> [!IMPORTANT]
> La base de datos pertenece a sus resprectivos creadores, E. Alpaydin y C. Kaynak.
> <br>Link de la base de datos: https://archive.ics.uci.edu/dataset/80/optical+recognition+of+handwritten+digits
> <br>Link de las utilidades de carga de conjuntos de datos: https://scikit-learn.org/stable/datasets/toy_dataset.html#optical-recognition-of-handwritten-digits-dataset

Si deseas contribuir a este proyecto, puedes enviar solicitudes de extracción (pull requests) con mejoras o características adicionales y si tienes alguna pregunta o problema, puedes contactarme a través de mi perfil de GitHub MrMike92. 🐢
