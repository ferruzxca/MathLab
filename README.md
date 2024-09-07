# MathLab
Crack de MathLab
Paso 1:  
Asigna el archivo `R2023a_Windows.iso` a la unidad virtual (Clic derecho > Seleccionar Montar).

Paso 2:  
Ejecuta `setup.exe` desde la unidad virtual, aparecerá el formulario de inicio de sesión/contraseña/usuario (ahora tu computadora ha concedido acceso a internet al instalador).  
Luego, en la esquina superior derecha, en "Opciones avanzadas", selecciona el modo "Tengo una Clave de Instalación de Archivo".  
En caso de que tu computadora desactive el acceso a internet, el modo de configuración requerido es "Tengo una Clave de Instalación de Archivo".

Paso 3:  
Cuando se te pida "Ingresar Clave de Instalación de Archivo", ingresa la siguiente clave:  
17704-65516-28949-05196-27677-58153-52675-25427-40932-65107-12325-01750-10518-09536-46547-49184-48288-09956-47596-00605-62383-55525-24311-34288-36021-37745

O para la versión MATLAB R2023a Parallel Server:  
20284-13217-46013-47231-63557-62975-19146-02884-14151-04022-48486-17967-18490-44073-14578-03364-64813-48591-11761-21869-44683-35880-36232-04348-07012-10488

Paso 4:  
La ventana mostrará "Seleccionar Archivo de Licencia", selecciona el archivo `license.lic` del archivo comprimido `MATLAB R2023a Licenses.rar`.

Paso 5:  
Selecciona la unidad y la carpeta donde deseas instalar MATLAB.

Paso 6:  
Cuando se te pregunte "Seleccionar productos", elige los componentes que necesitas:  
- Si seleccionas todos los componentes, MATLAB necesitará aproximadamente 32 GB de espacio en disco y tardará un poco más en arrancar.  
- Si seleccionas solo "MATLAB", necesitará aproximadamente 4 GB de espacio en disco.  
- Es recomendable instalar MATLAB en un disco SSD para mejorar el tiempo de arranque.

Paso 7:  
En "Seleccionar Opciones", selecciona "Agregar acceso directo en el escritorio".

Paso 8:  
Espera a que la instalación finalice.

Paso 9:  
Después de que la instalación haya terminado, copia el archivo `libmwlmgrimpl.dll` desde el archivo comprimido `MATLAB R2023a Licenses.rar` a la carpeta de instalación de MATLAB y sobrescribe el archivo existente:  
`<carpetamatlab>\bin\win64\matlab_startup_plugins\lmgrimpl` (La carpeta seleccionada en el Paso 5).

Nota:  
Si no se creó el acceso directo en el escritorio, puedes crear uno nuevo desde la ruta:  
`<carpetamatlab>\bin\win64\MATLAB.exe`.
