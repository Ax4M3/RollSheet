# [RollSheet](https://ax4m3.github.io/RollSheet/)

![License MIT](https://img.shields.io/github/license/Ax4M3/RollSheet?style=flat-square&color=green)
![GitHub Issues](https://img.shields.io/github/issues/Ax4M3/RollSheet?style=flat-square)

Una herramienta web estática, ligera y (casi) completa para generar, previsualizar y exportar fichas de personaje para diferentes sistemas de juegos de rol (Dungeons & Dragons, Warhammer, etc.).

El proyecto está programado íntegramente en HTML, CSS y JavaScript puro, y se ejecuta directamente en el navegador sin necesidad de instalación alguna.

### Para encontrarme a mí mismo y apoyarme
[![Mastodon](https://img.shields.io/badge/Mastodon-Profil-563acc?style=flat-square&logo=mastodon)](https://piaille.fr/@Axm)
[![Liberapay](https://img.shields.io/badge/Liberapay-Faire_un_don-f6c915?style=flat-square&logo=liberapay&logoColor=black)](https://liberapay.com/AxM3/donate)

**[Para probar la herramienta en línea (GitHub Pages)](https://ax4m3.github.io/RollSheet/)**

-> *Herramienta procedente de un proyecto anterior : [Ver el repositorio archivado](https://github.com/Ax4M3/fiches-jdr)*

### Idiomas
- English version : [README in English](README.en.md)
- Deutscher Sprache : [README auf Deutsch](README.de.md)
- Version Française : [README en Français](README.md)

---

## Funcionalidades

- **Formulario web**: Introduce manualmente la identidad, el avatar, las estadísticas, las habilidades y la historia de tu personaje.
- **Generación aleatoria**: Crea personajes al instante con el botón *Aleatorio*.
- **Sistema multilingüe**: Interfaz disponible en Deutsch (DE), English (EN),  Español (ES) et Français (FR).
- **Tema adaptativo**: gestión integrada de un modo oscuro para proteger tus ojos durante las sesiones nocturnas.
- **Exportación a varios formatos**:
  - **📥 PDF**: Generar una ficha lista para imprimir en formato PDF.
  - **📄 DOCX (Word)**: Exporta un archivo editable para perfeccionar tu ficha en tu procesador de textos.
  - **💾 JSON**: Guarda la estructura de datos de tu personaje para volver a cargarla más tarde.
  - **Compartir**: Comparte tu ficha con el enlace generado que se te proporciona.

## Uso e Instalación

### Opción 1: Uso en línea (recomendado)
Accede directamente a la página del proyecto alojada en GitHub:
-> **[https://ax4m3.github.io/RollSheet/](https://ax4m3.github.io/RollSheet/)**

### Opción 2: Uso local (sin Internet)
No se necesita ningún servidor ni instalación (como Python).
1. Descarga o clona el repositorio :
   ```bash
   git clone [https://github.com/Ax4M3/RollSheet.git](https://github.com/Ax4M3/RollSheet.git)
   cd RollSheet
   ```
2. Haz doble clic en el archivo `index.html` para abrir el generador al instante en tu navegador.

## Sistemas de juego compatibles
**- *Nota*: Los sistemas instalados aún necesitan mejoras; faltan muchos elementos que se irán añadiendo más adelante.**

| Sistema | Estado | Atributos gestionados |
| --- | --- | --- |
| **Dungeons & Dragons** | ✓ Implementado | Fuerza, Destreza, Constitución, Inteligencia, Sabiduría, Carisma |
| **Warhammer** | ✓ Implementado | WS, BS, S, T, Ag, Int, WP, Fel |
| **Call of Cthulhu** | ☓ Próximamente | *Próximamente* |
| **Pathfinder** | ☓ Próximamente | *Próximamente* |

## Colaborar
Se agradecen las colaboraciones para hacer crecer la herramienta. No dudes en abrir una *Pull Request* o una *Issue* para: 
- Proponer nuevos sistemas de juegos de rol (Shadowrun, Cyberpunk, etc.).
- Mejorar o modernizar el diseño de las fichas generadas (CSS).
- Añadir o corregir traducciones.

## Licencia
Este proyecto se distribuye bajo la licencia MIT. Consulta el archivo [LICENSE](https://github.com/Ax4M3/RollSheet/blob/main/license.html) o la [página dedicada](https://ax4m3.github.io/RollSheet/license.html) para obtener más detalles.