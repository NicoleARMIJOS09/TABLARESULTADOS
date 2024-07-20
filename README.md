# TABLARESULTADOS
## EXPLICACION DEL CODIGO
### Clase MaxPointTableView
La clase MaxPointTableView es una aplicación JavaFX que muestra dos ventanas con tablas de los puntos máximos de pilotos y constructores de Fórmula 1, obtenidos desde una base de datos MySQL. En el método start, se crea una instancia de QueryRepositorio para recuperar los datos de los pilotos y constructores. Para los pilotos, se obtiene una lista de DriverMaxPoint desde la base de datos y se convierte en una ObservableList que se usa para poblar un TableView. Se definen dos columnas, una para el nombre del piloto y otra para los puntos, y se configura y muestra una ventana con esta tabla. De manera similar, se obtienen los datos de los constructores y se muestra una segunda ventana con una tabla que contiene el nombre del constructor y los puntos.

### Clase QueryRepositorio
La clase QueryRepositorio se encarga de conectarse a la base de datos MySQL y recuperar los datos necesarios para la aplicación. El método getDriversMaxPoint obtiene los puntos máximos de los pilotos mediante una consulta SQL que selecciona los nombres concatenados de los pilotos y sus puntos totales, ordenados de mayor a menor, limitando los resultados a los 10 primeros. Establece una conexión con la base de datos, ejecuta la consulta, itera sobre los resultados y crea instancias de DriverMaxPoint con los datos recuperados. De manera similar, el método getConstructorsMaxPoints obtiene los puntos máximos de los constructores mediante una consulta SQL que selecciona los nombres de los constructores y sus puntos totales, ordenados de mayor a menor, limitando los resultados a los 10 primeros. Establece una conexión con la base de datos, ejecuta la consulta, itera sobre los resultados y crea instancias de ConstructorMaxPoint con los datos recuperados.

## CODIGO
![image](https://github.com/user-attachments/assets/0d79d7e4-1a67-4f59-869f-72e480404d91)
![image](https://github.com/user-attachments/assets/69d6737e-f6c6-44ff-964a-4ece663ee298)
![image](https://github.com/user-attachments/assets/bf51c9dc-7459-4fec-8d9f-2ea1d97e0832)
![image](https://github.com/user-attachments/assets/82df6d39-8eb4-44cc-a9f7-f2719d91c4c2)
![image](https://github.com/user-attachments/assets/9520db20-330a-4b46-a24a-1b205de91446)
![image](https://github.com/user-attachments/assets/43f0e2aa-939d-427d-b240-c17f49a9d067)

## EJECUCION
![image](https://github.com/user-attachments/assets/aa8649fc-eefa-447f-9f27-5bf9085d4ed5)
