### Módulos de Bower
#### Configurar el paquete

- Si el paquete viene con un *provider* para su configuración, lo configuramos en el *core/config.js*.

- Para ello, añadiremos una función declarada en el **.config()** del módulo general.

```javascript
angular.module('starter')
    .config(configLocalStorage)

function configLocalStorage(localStorageServiceProvider) {
  localStorageServiceProvider.setPrefix('starter');
}
```
