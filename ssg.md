# ¿Que es un ssg? 

> es una compilación de HTML estáticas donde el público puede descargar tus  HTMLs sin problema. El SSG habitualmente sirve para facilitar la creación de blogs, páginas web donde no quieras programar o no tienes ni idea y por último, a diferencia con respecto del cms y a un SSG son páginas estática, es decir sus páginas están creadas por un simple HTML + CSS + JS. 

--- 

| Aspecto a que mirar | Jekyll | Hugo | Astro |
| :--- | :--- | :--- | :--- |
| **Tecnología o lenguaje principal** | Ruby | Go (Golang) | Javascript (Framework) |
| **Formato utilizado para el contenido** | Markdown, HTML, Liquid | Markdown, AsciiDoc, HTML | Markdown, MDX, HTML |
| **Necesidad de instalación** | Requiere Ruby y gemas asociadas | Binario único ejecutable sin dependencias complejas | Requiere Node.js y un gestor de paquetes (npm, pnpm, yarn) |
| **Funcionamiento básico** | Compila archivos Markdown y plantillas Liquid en HTML estático | Compila contenido y plantillas Go a gran velocidad | Arquitectura basada en islas: compila componentes y Markdown a HTML estático con JavaScript mínimo |
| **Usos habituales** | Blogs personales y documentación (nativo de GitHub Pages) | Sitios web grandes, blogs y portales de documentación ultrarrápidos | Sitios web orientados a contenido, blogs, portfolios y aplicaciones web |
| **Ventajas** | Integración nativa absoluta con GitHub Pages; gran comunidad de blogs | Velocidad de compilación extrema; un solo archivo ejecutable | Rendimiento excepcional |
| **Inconvenientes** | Tiempos de compilación lentos en proyectos muy grandes; dependencia del ecosistema Ruby | Curva de aprendizaje inicial con las plantillas de Go | Menos enfocado a blogs tradicionales |
| **Posibilidad de publicarlo en GitHub Pages** | Sí (soporte nativo directo de forma automática) | Sí (mediante acciones de compilación como GitHub Actions) | Sí (mediante GitHub Actions) |


--- 

[![¿Que es un sitio generador estetico?](https://youtube.com)](https://youtu.be/osWfEtbP_sk?si=sHFWF5mwxiJhv5wL)

[Ir a CMS](cms.md) 
