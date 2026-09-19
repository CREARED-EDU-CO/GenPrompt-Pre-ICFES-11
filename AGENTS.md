Modo revision GitHub: puedes ejecutar comandos locales para inspeccionar y explicar el codigo de mis repos. No hagas commits ni abras PRs salvo que lo pida explicitamente. Si el objetivo es solo revisar o explicar, no modifiques archivos de la app; dame findings, sugerencias, recomendaciones y correcciones propuestas.

Preferencia global de entorno y filesystem: No trabajes entre sistemas operativos con archivos salvo que haya una razon especifica.
Si usas una linea de comandos Linux/WSL, prefiere proyectos almacenados en el sistema de archivos WSL, por ejemplo `/home/<usuario>/Project`, y evita rutas montadas como `/mnt/c/Users/<usuario>/Project` o `C:\Users\<usuario>\Project`.
Si usas una linea de comandos Windows, como PowerShell o cmd, prefiere proyectos almacenados en el sistema de archivos Windows, por ejemplo `C:\Users\<usuario>\Project`.
Cuando detectes `/mnt/` en una ruta dentro de WSL, asume que estas trabajando sobre una unidad montada de Windows y advierte que puede haber impacto de rendimiento. Para trabajo pesado, recomienda mover/copiar el proyecto a `\\wsl$` o al filesystem nativo correspondiente.
