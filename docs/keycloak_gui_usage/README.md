# Keycloak Graphical Interface

Keycloak application is launched by running the keycloak container and the keycloak web application is available at the keycloak_url

[http://KC_HOST:KC_PORT](http://KC_HOST:KC_PORT)

example: http://localhost:8080


## Screens

### Login and Landing Zone of Keycloak

![Keycloak Landing 1](/docs/assets/images/kc_1_keycloak_login_landing.png)

The default login credentials for keycloak are as below it's not good practice

```env
KC_BOOTSTRAP_ADMIN_USERNAME=admin
KC_BOOTSTRAP_ADMIN_PASSWORD=admin
```

### Admin Console after login

![Keycloak Landing 1](/docs/assets/images/kc_2_keycloak_main_page.png)

### Create a new Realm in Keycloak

By default keycloak is launched with `master` realm.
Creaate a new realm almost always so the realm is more aligned to the application or group of applications.

![Keycloak New Realm](/docs/assets/images/kc_3_keycloak_create_new_realm_button.png)

by clicking on the create realm opens the below form to fill to create a new keycloak realm.

![Keycloak New Realm Form Filled](/docs/assets/images/kc_4_create_new_realm_form.png)

![Keycloak Create New Realm Form](/docs/assets/images/kc_5_create_new_realm_added_realm_name.png)

![Keycloak New Realm Home Landing Page](/docs/assets/images/kc_6_new_realm_home_landing_page.png)

### Create Keycloak Admin account

