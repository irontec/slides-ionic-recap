### Crear módulos
#### Añadir la lógica

- Añadimos la lógica de dicha funcionalidad y lo utilizamos en nuestra aplicación.

```javascript
angular
    .module('starter.settings')
    .controller('SettingsController', SettingsController);

    function SettingsController(...) {
        ...
    }

```
