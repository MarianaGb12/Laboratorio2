# Laboratorio2
Integrantes: Mariana Guerrero, Jonathan Castellanos.

Optimización 2184.

Si ejecuta el codigo en Visual Studio, o parecido, instala toda las libreria que se encuentra en "requirements.txt"
puedes hacerlo en Visual Studio escribiendo en el comando "pip install -r requirements"

Si desea ejecutarlo por Google Colab o parecido sube el Dataset llamado "Car_Purchasing_Data.csv" y coloca el siguiente codigo:

    from google.colab import drive # Esta libreria conecta una cuenta de google drive
    drive.mount('/content/drive') # Carga y muestra mi carpeta desde esta direccion (En la carpetita que esta en la barrra que esta a la izquierda)
    df = pd.read_csv('/content/drive/MyDrive/Car_Purchasing_Data.csv')# Este la direción de donde se encuentra el Dataset (Esta en la direción estandar, si guardaste el Dataset en una carpeta especifica y no en el inicio de tu Drive, debe colocar la ruta completa)
