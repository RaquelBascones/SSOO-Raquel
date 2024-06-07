# SSOO-Raquel

```markdown
# ESCRITORIO PERSONALIZADO EN Java

Este proyecto implementa un escritorio personalizado en Java utilizando Swing. La aplicación ofrece una interfaz gráfica con varios iconos que lanzan diferentes aplicaciones junto con un reloj digital.

## FUNCIONALIDADES

- **Reloj Digital:** Muestra la hora y la fecha actual en la parte superior central del escritorio.
- **Iconos de Aplicaciones:** Diferentes iconos para acceder a varias aplicaciones como navegador web, gestor de archivos, calendario, configuraciones, aplicaciones de Microsoft Office, correo, recomendador de IA, terminal, y una carpeta de juegos.

## ESTRUCTURA DEL PROYECTO

- **Paquete `Escritorio`:**
  - `DesktopScreen.java`: Clase principal que configura y muestra el escritorio.
  - `CustomTerminal.java`: Implementación de una terminal personalizada.
  - `LoginScreen.java`: Implementación de la pantalla de inicio de sesión. (Esta es la que se debe de ejecutar)
  
- **Paquete `Escritoriojuegos`:**
  - `SudokuGame.java`: Implementación del juego Sudoku.
  - `WordleGame.java`: Implementación del juego Wordle.
  - **Subpaquete `ajedrez`:**
    - `ChessGame.java`: Implementación del juego de Ajedrez.
    - `Bishop.java`: Implementación del juego de Ajedrez.
    - `Board.java`: Implementación del juego de Ajedrez.
    - `King.java`: Implementación del juego de Ajedrez.
    - `Knight.java`: Implementación del juego de Ajedrez.
    - `Pawn.java`: Implementación del juego de Ajedrez.
    - `Piece.java`: Implementación del juego de Ajedrez.
    - `Queen.java`: Implementación del juego de Ajedrez.
    - `Rook.java`: Implementación del juego de Ajedrez.

## REQUISITOS QUE TIENES QUE TENER PARA PODER EJECUTARLO
- Java JDK 11 o superior.
- Sistema operativo Windows (algunas funcionalidades específicas como abrir aplicaciones están configuradas para Windows).

## COMO USAR MI SISTEMA OPERATIVO

1. **Inicio de Sesión:**
   - Al iniciar la aplicación, se presenta una pantalla de inicio de sesión.
   - Ingrese sus credenciales para acceder al escritorio.

2. **Navegar por el Escritorio:**
   - Haga clic en los iconos para abrir las diferentes aplicaciones.
   - La hora y la fecha se actualizan automáticamente.
```
