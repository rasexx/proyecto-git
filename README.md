Sistema de Control de Versiones (SCV):
Un Sistema de Control de Versiones (SCV) es una herramienta que gestiona y controla los cambios en el código fuente u otros conjuntos de archivos a lo largo del tiempo. Su función principal es rastrear las modificaciones realizadas en los archivos, así como gestionar la colaboración entre varios desarrolladores en un proyecto. Permite registrar quién hizo qué cambio, cuándo se realizó y facilita la recuperación de versiones anteriores.

Términos en un SCV:
    Repositorio: Es el lugar donde se almacenan los archivos y las versiones del proyecto. Puede ser centralizado o distribuido.
    Working Copy/Working Set: Es la copia local de los archivos del repositorio que tiene un desarrollador en su máquina. Es la versión con la que trabaja activamente.
    Trunk/Main/Master: Estos términos suelen referirse a la rama principal del desarrollo en un repositorio. Es la línea principal de desarrollo donde se encuentran las versiones estables del código.

Operaciones en un SCV:
    Add: Prepara los archivos modificados para ser incluidos en la próxima confirmación (commit) al repositorio.
    Head: Hace referencia a la versión más reciente del código en una rama específica. Es la punta de la rama.
    Commits: Guarda los cambios realizados en los archivos en el repositorio. Cada commit tiene un mensaje que describe los cambios realizados.
    Branching: Crear una rama separada del desarrollo principal para trabajar en nuevas características o correcciones sin afectar directamente la rama principal.
    Merge: Combina los cambios realizados en una rama con otra, integrando las modificaciones de manera que no se pierda información.

Tipos de SCV:
    Centralizados: En este modelo, hay un único repositorio central que almacena todas las versiones del código. Los desarrolladores trabajan con copias locales, pero las actualizaciones y confirmaciones se realizan en el repositorio central.
    Distribuidos: Cada desarrollador tiene una copia completa del repositorio, incluyendo el historial completo. Los cambios pueden realizarse localmente y luego compartirse con otros repositorios, lo que proporciona mayor flexibilidad y capacidad de trabajo offline. Ejemplos incluyen Git y Mercurial.

