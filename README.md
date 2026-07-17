# Información del trabajo (partidos del mundial)

* **Nombre:** Nicolas Fuksman
* **Curso:** 5°E
* **Materia:** Frontend
* **LINK:** https://partidos-mundial-tp1.vercel.app/

## Explicación de la página
Una página que permite visualizar todos los partidos jugados y por jugarse del mundial.

## Herramientas utilizadas
* Astro
* API de Football-Data.org

## Cómo usarlo

1. **Clonar el repositorio:**
   ```bash
   git clone <URL_DEL_REPOSITORIO>
   cd <NOMBRE_DE_LA_CARPETA>
   ```

2. **Instalar las dependencias:**
   ```bash
   npm i
   ```

3. **Obtener la clave de la API:**
   * Registrate o logueate en [Football-Data.org](https://football-data.org).
   * Solicitá tu API key.

4. **Configurar las variables de entorno:**
   * Creá un archivo llamado `.env` en la raíz del proyecto.
   * Agregá la siguiente línea reemplazando con tu clave:
     ```env
     FOOTBALL_API_KEY=[api_de_Football-Data.org]
     ```

5. **Iniciar el servidor de desarrollo:**
   ```bash
   npm run dev
   ```
