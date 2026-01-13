# WordleESP

## Qué es
Juego de práctica en Python centrado en mecánicas de palabras/letras, organizado por módulos para separar lógica de juego, gestión de palabras/letras e indicadores.

## Stack
- Python 3.x
- Estructura modular: `Juego.py`, `Palabras.py`, `Letras.py`, `Indicador.py`
- Configuración: `config.py`
- Recursos: carpeta `assets/` (imágenes/sonidos y fuentes) [TODO: especificar]

## Features
- Punto de entrada claro desde `main.py`
- Separación por responsabilidades (juego / palabras / letras / indicador)
- Configuración centralizada en `config.py`
- Uso de assets para enriquecer la experiencia

## Capturas/GIF
<img width="627" height="915" alt="image" src="https://github.com/user-attachments/assets/435235e7-5e96-4219-8a3d-d37d51087b81" />
<img width="625" height="911" alt="image" src="https://github.com/user-attachments/assets/73481570-5241-4883-b1cd-3165b918d389" />
<img width="1803" height="992" alt="image" src="https://github.com/user-attachments/assets/fa848c6e-d87f-431a-8235-72215619718e" />

## Cómo ejecutar
1. Clona el repositorio
2. (Opcional) Crea y activa un entorno virtual
   - Windows:
     ```bash
     python -m venv .venv
     .\.venv\Scripts\activate
     ```
   - Linux/Mac:
     ```bash
     python -m venv .venv
     source .venv/bin/activate
     ```
3. Ejecuta el juego:
   ```bash
   python main.py
   pip install -r requirements.txt
   
## Qué aprendí
- A estructurar un proyecto en Python por módulos (separación de responsabilidades)
- Manejo de estado y flujo de juego desde un punto de entrada (main.py)
- Organización de recursos (assets/) y configuración centralizada (config.py)ç
