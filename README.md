# Flet-MongoDB
Este repo contiene un ejemplo de conexion a MongoDB con Flet

Comandos Flet

python -m venv .venv

.\.venv\Scripts\Activate.ps1

pip install flet

pip install pymongo

flet create "nombre de la app"

# Ejecutar la aplicación
#ft.app(target=main)

# Ejecutar la aplicación en web
ft.app(target=main, view=ft.AppView.WEB_BROWSER)

# Ejecutar la aplicaion en mobile
#ft.app(target=main, view=ft.AppView.FLET_APP)
