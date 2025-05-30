# dotfileseos

Configuración personalizada de dotfiles para i3wm y herramientas asociadas en Linux.

## Descripción

Este repositorio contiene mis archivos de configuración (dotfiles) para el gestor de ventanas i3, así como scripts y configuraciones para mejorar la experiencia en entornos Linux tipo Arch/EndeavourOS. Incluye ajustes para i3, i3blocks, rofi, atajos de teclado, scripts de sistema, y más.

## Características

- Configuración avanzada y personalizada de i3wm.
- Scripts para gestión de energía, brillo, volumen, batería, red, clima, etc. (ver carpeta [`i3/scripts`](i3/scripts))
- Temas y menús personalizados para rofi.
- Integración con i3blocks para una barra de estado informativa.
- Atajos de teclado optimizados y documentación de keybindings.
- Scripts para detección automática de monitores y disposición de pantallas.
- Configuración de aplicaciones favoritas y utilidades del sistema.

## Instalación

1. Clona este repositorio en tu directorio de usuario:
   ```sh
   git clone https://gitlab.com/luislmoron/dotfileseos.git ~/dotfileseos
   ```
2. Copia o enlaza los archivos de configuración a tu `$HOME`:
   ```sh
   cp -r ~/dotfileseos/i3 ~/.config/
   cp -r ~/dotfileseos/rofi ~/.config/
   cp ~/dotfileseos/zshrc ~/.zshrc
   cp ~/dotfileseos/zprofile ~/.zprofile
   ```
3. Asegúrate de tener instaladas las dependencias necesarias: i3, rofi, dunst, i3blocks, acpi, upower, brightnessctl, etc.
4. Reinicia tu sesión o recarga la configuración de i3.

## Uso

- Personaliza los scripts y configuraciones según tus necesidades.
- Consulta los atajos de teclado en [`i3/keybindings`](i3/keybindings) o usando el menú de ayuda integrado (`F1`).
- Modifica los scripts en [`i3/scripts`](i3/scripts) para adaptarlos a tu hardware o preferencias.

## Capturas de pantalla

_Agrega aquí imágenes de tu escritorio y barra de estado si lo deseas._

## Créditos

Basado en configuraciones de la comunidad EndeavourOS y scripts de múltiples autores (ver comentarios en cada archivo).

## Licencia

Consulta la licencia individual en cada script. La mayoría de los scripts están bajo GPL o licencias libres.

---

¿Tienes dudas o sugerencias? ¡Abre un issue o contáctame!
