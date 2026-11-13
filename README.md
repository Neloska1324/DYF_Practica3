
Versión de Unreal Engine: 5.8.0

Versión de Meta XR Plugin: 1.207.0

Minijuego Bolos: La bola, que tiene un Blueprint con su mismo nombre, se desliza por una rampa hasta chocar con los bolos apilados en triangulo que tiene en frente.

Minijuego Wreck-It Ralph: En este juego el usuario coge el martillo que se encuentra en la sala (manteniendo "u") y rompe la piñata. No es necesario Blueprint.

Minijuego Mr.Potato: Trata de coger cada pieza situada en la mesa, al aproximarse al cuerpo de Mr.Potato y soltar la tecla, estas se adhieren a la superficie del cuerpo. Cada una de las extremidades tienen su propio Blueprint.

Minijuego Dardos: El dardo se deja caer desde la altura predeterminada hacia la diana, el usuario puede agarrarlo y soltarlo desde la altura que desee para que vuelva a clavarse. Tanto el dardo como la diana son Blueprints. 


Valores físicos finales

| Elemento | Propiedad | Valor |
| :--- | :--- | :--- |
| **Bola** | Masa | 20 kg |
| | Linear Damping | 0.1 |
| | Angular Damping | 0.0 |


| Elemento | Propiedad | Valor |
| :--- | :--- | :--- |
| **Bolos** | Masa | 1 kg |
| | Linear Damping | 0.1 |
| | Angular Damping | 0.0 |


| Elemento | Propiedad | Valor |
| :--- | :--- | :--- |
| **Piñata** | Masa | 849,7 kg |
| | Damage Threshold | índice [0] = 100, [1] = 50, [3] = 20|
| | Geometry Collection | Nivel 1 = 455 |


