# Multilingo
MultiLingo: herramienta de traducción de software automatizada.
# Multilingo

Multilingo es una herramienta de traducción automática básica diseñada para traducir archivos de texto de manera sencilla. Actualmente, su funcionalidad se centra en procesar archivos dentro de una carpeta específica y traducirlos automáticamente.

## Características principales
- **Traducción automática**: Traduce archivos de texto ubicados en la carpeta `traducir`.
- **Uso sencillo**: No requiere configuraciones avanzadas.
- **Soporte para múltiples archivos**: Procesa todos los archivos dentro de la carpeta `traducir`.
- Manejo de caracteres de escape unicode para evitar errores de traucción.
- Traducciones consistentes y contextualizadas.

## Instalación
Para instalar Multilingo, sigue estos pasos:
1. Clona el repositorio:
   ```sh
   git clone https://github.com/usuario/multilingo.git
   ```
2. Accede al directorio del proyecto:
   ```sh
   cd multilingo
   ```
3. Instala las dependencias necesarias:
   ```sh
   pip install -r requisitos.txt
   ```

## Uso
1. **Colocar archivos en la carpeta `traducir`**:
   - Asegúrate de que los archivos de texto que deseas traducir estén dentro de la carpeta `traducir`.
2. **Ejecutar la traducción**:
   ```sh
   python multilingo.py
   ```
3. **Recuperar los archivos traducidos**:
   - Los archivos traducidos se guardarán en la carpeta `procesados`.

## Próximas mejoras
Se planea añadir las siguientes funcionalidades en futuras versiones:
- **Gestor de proyectos**: Permitir la gestión de múltiples proyectos con configuraciones personalizadas.
- **Parser universal**: Ampliar la compatibilidad con distintos formatos de archivos de texto.
- **Base de datos de traducciones**: Almacenar traducciones validadas para evitar duplicados y mejorar la eficiencia.
- **Identificación de claves no traducidas**: Detectar automáticamente frases que aún no han sido traducidas.

## Contribuir
Si deseas contribuir al desarrollo de Multilingo, puedes:
- Reportar problemas o sugerir mejoras en la sección de *Issues*
- Realizar *pull requests* con nuevas funcionalidades

## Licencia
Multilingo está licenciado bajo la licencia MIT. Consulta el archivo `LICENSE` para más información.

