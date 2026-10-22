touch README.md
# Migraciones con Flask

Proyecto académico de TEM-742 Tecnologías Emergentes II.

## Tecnologías
- Python 3.13
- Flask
- Flask-SQLAlchemy
- Flask-Migrate
- SQLite

## Base de datos
El sistema administra usuarios, clientes, productos, ventas y detalles de ventas.

## Instalación

```bash
pip install -r requirements.txt
flask db upgrade
python seed.py
```

## Migraciones
1. Usuarios, clientes y productos.
2. Ventas y detalle de ventas.
3. Columna categoria en productos.

## Autor
Danner De Jesus Ticona Yujra
