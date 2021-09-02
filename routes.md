#
# Liste des routes

> Attention: Certaines routes ne fonctionnent pas, elles seront mentionnées d'un : *

| Route        | Permission           | Methode  |
| ------------- |:-------------:| :-----:|
| /     | . | . |
| /login     | . | . |
| /register     | . | . |

# Créer une route

```yaml
# config/routes.yaml

Login:
  path: /login
  controller: App\Controller\LoginController::index
```
