# Nombre del Proyecto

Breve descripción de qué hace el proyecto y para qué sirve.

---

## Requisitos

* Python 3.10+ (u otra dependencia relevante)
* Paquetes: `google-api-python-client`, `google-auth`, `google-auth-oauthlib`, `openai`

---

## Instalación

1. Clona el repositorio:

```bash
git clone https://github.com/tu-usuario/tu-repo.git
cd tu-repo
```

2. Crea y activa un entorno virtual (opcional pero recomendado):

```bash
python -m venv venv
# Windows
venv\Scripts\activate
# macOS / Linux
source venv/bin/activate
```

3. Instala dependencias:

```bash
pip install -r requirements.txt
```

---

## Configuración

1. Coloca tus credenciales de Google (`credentials.json`) y el archivo `token.json` en la carpeta `config/` o en la ruta que prefieras.
2. Crea un archivo `openai_key.txt` con tu API key de OpenAI.
3. Ajusta las rutas en el archivo de configuración o directamente en el script si es necesario.

Ejemplo de estructura
