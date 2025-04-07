# OFME-Scraper
## Made by Systemm32
OFME Scraper based on NodeJS, made by Systemm32.
### 🖼 Imágenes
![OFME Scraper Mockup](https://github.com/user-attachments/assets/c47c8fa6-45ba-4f5e-aae8-a275d17c7326)

![OFME Scraper Menu](https://github.com/user-attachments/assets/724f1955-ea4f-4c5a-9d29-c72afe9ec8b1)


### ⚙ Configuración
Este scraper **necesita** una configuración para su correcto funcionamiento.
Es posible que no funcione si no la utiliza.
- Deberas colocar la configuración (_config.json_) en el mismo directorio que el ejecutable del scraper.
- Si la configuración no sigue el formato de la documentación (explicada mas abajo) el programa no funcionará.
### 📃 Documentación
- La configuración es un archivo **_JSON_**, es necesario que esté formateado con este lenguaje de marca.
    Parámetros del JSON:
  - Credentials: Las credenciales del módulo de scrapeo
      - Cookie (La cookie en cuestión, se puede insertar desde la opción 2 del menú)
      - User (Datos vinculantes al usuario)
          - Username (Nombre de usuario del módulo
      - Modules (Los módulos de scrapeo)
        > Recomendado para su uso el modulo OFME con enlace al sitio
  ### config.json
  ```json
  {
  "credentials": {
    "cookie": "encryptedCookie"
  },
  "user": {
    "username": "yourUsername"
  },
  "modules": [
    {
      "name": "OFME",
      "source": "https://OFME-site/"
    }
  ]
  }
## ❗ **Es necesario cambiar la fuente de enlace del módulo OFME para que funcione** (por motivos legales no puedo proporcionar directamente el enlace.)
