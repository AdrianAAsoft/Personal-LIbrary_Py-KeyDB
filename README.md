# Personal-LIbrary_Py-KeyDB
Utilizar sistemas de almacenamiento en memoria para desarrollar aplicaciones con alto rendimiento en lectura y escritura. Para ello, deben adaptar su aplicación de línea de comandos para que funcione con KeyDB, utilizando estructuras de datos serializadas como JSON.

# 📝 Contexto
Modificar la aplicación de biblioteca personal para reemplazar el uso de MongoDB por KeyDB, un sistema de almacenamiento en memoria compatible con Redis. Los datos deberán ser almacenados y gestionados usando operaciones rápidas y eficientes mediante redis-py.

## 📌 Instalacion de KeyDB(Windows):
1. Instalar docker hub [https://www.docker.com/get-started/]
2. Abrir docker hub
3. windows + R
4. cmd + enter
5. En el cmd escribir lo siguiente:
   - 1step es una variable que especifica el nombre del contenedor
   - 6505 es el puerto que le colocas al contenedor (es modficable)
   - 6379 es el puerto en el que escucha keydb (no modificable)
```bash
docker run -p 6505:6379 --name 1step -d eqalpha/keydb 
```

## 📌 Instalacion de dependencias:
```bash
pip install redis python-dotenv
```

## 📁 Archivos

```bash
├── main.py            # Modulo principal
├── sql.py             # Modulo de funciones para KeyDB 
```

## ▶️ Ejecución
Ejecuta el programa con:
```bash
python main.py
```

## 🧪 Ejemplo de Uso

```python
======= BIBLIOTECA =======
1. Agregar nuevo libro
2. Actualizar información de un libro
3. Eliminar libro existente
4. Ver listado de libros
5. Buscar libros
6. Salir
```
