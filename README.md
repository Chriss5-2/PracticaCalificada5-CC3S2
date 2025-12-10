# Repo Individual - PracticaCalificada5-CC3S2

Integrantes:
- Yorklin Lazaro
- Christian Luna


# Ejecución
```bash
# Clonar el repositorio grupal
git clone https://github.com/Grupo2-CC3S2/Practica_Calificada_5-CC3S2.git
```

Tener DockerDesktop en ejecución y en la carpeta raiz ejecutar
```bash
make build
make run
```

Para levantar la aplicación web, luego para probar el acceso
```bash
make requests
```

Para ejecutar las pruebas unitarias
```bash
make venv
make test
```

Eliminar los contenedores, imagenes y red interna creada
```bash
make delete
```

Limpiar en entorno
```bash
make clean
```
