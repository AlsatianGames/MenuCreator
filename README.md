# Generador de Menús Semanales

**Generador de Menús Semanales** es una aplicación de escritorio para organizar y asignar comidas diarias. Desarrollada en Python con **Tkinter** para la interfaz gráfica y **Telegram Bot API** para enviar menús semanales a un grupo de Telegram.

## Características

- **Asignación de Menús**: Asigna comidas para desayuno, comida y cena para cada día de la semana.
- **Validación Nutricional**: Incluye validaciones para controlar el consumo de carbohidratos, proteínas y grasas por día.
- **Integración con Telegram**: Envía el menú semanal a un grupo de Telegram a través de un bot, con notificaciones en caso de exceso de nutrientes.
- **Búsqueda de Platos**: Permite buscar platos en el `ComboBox` mientras se escriben caracteres.
- **Añadir Nuevos Alimentos**: Agrega alimentos manualmente al archivo `comidas.csv` especificando sus propiedades nutricionales y tipo de comida.
  
## Tecnologías Utilizadas

- **Python 3.x**
- **Tkinter** - Interfaz gráfica de usuario
- **Python-Telegram-Bot** - API de Telegram para el bot de envío de menús
- **Pandas** - Gestión de datos en el archivo `comidas.csv`

## Requisitos Previos

1. **Python 3.x** instalado.
2. Librerías de Python: 
   ```bash
   pip install tkinter pandas python-telegram-bot pyinstaller
