### Crear módulos
#### Utilizar el módulo

- Inyectamos la dependencia en los controladores/factorías que harán uso de dicho paquete.

- Hacemos uso de las variables o funciones que nos aporta el módulo.

```javascript
    function SettingsController(localStorageService) {
        var language = localStorageService.get('language');
    }

```
