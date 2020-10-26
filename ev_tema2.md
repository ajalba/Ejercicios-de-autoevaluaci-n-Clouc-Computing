# Ejercicio 1
## Instalar alguno de los entornos virtuales de node.js (o de cualquier otro lenguaje con el que se esté familiarizado) y, con ellos, instalar la última versión existente, la versión minor más actual de la 4.x y lo mismo para la 0.11 o alguna impar (de desarrollo).

## Instalación
Para instalarlo basta con descargar el script  dado por (https://github.com/nvm-sh/nvm) y ejecutarlo o en su defecto emplear el comando *curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.36.0/install.sh | bash* que hará la instalación automática.

Por otro lado, para instalar la versión más reciente de node es recomendable emplear *nvm install node* ya que "node" es un alias para la última versión dispoble.

En el caso de a día 21 de Octubre de 2020, la versión 15.0.0

Para el resto de versiones bastará cambiar en el comando anterior la palabra **node** por el número de versión deseado.

# Ejercicio 2
## Crear una descripción del módulo usando package.json. En caso de que se trate de otro lenguaje, usar el método correspondiente.

Basta con crear una carpeta y ejecutar el comando *npm init* y así obtener toda la estructura de directorios básica necesaria para comenzar un proyecto, entre ellos un fichero **package.json**.