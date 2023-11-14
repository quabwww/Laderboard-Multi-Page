# Laderboard-Multi-Page

Hola bienvenido me presento soy xquab y hoy les compartire mi trabajo. hecho junto con el owner de The BDS Word (izana.py)
por favor para apoyar mas proyectos asi nos gustaria que se unan al servidor official de The BDS Word.

Link: https://discord.gg/dru9uRYKqq

## Variables Necesarias

|    Nombre   |         Valor       |
|-------------|---------------------|
|   currency  |  un stiker o emoji  |

Este codigo lo unico que requiere es una variable de uso de su economia (solo numeros)

### Leaderboard 
Por favor para que este codigo funcione siga las indicaciones ala continuacion.

Remplaze el var llamado "variable" por el nombre de su variable de la cual desea usar el leaderboard.

![image](https://github.com/quabwww/Laderboard-Multi-Page/assets/148601206/66b5de27-a5c1-4722-9fb7-458ba974ec22)

Remplaze el var llamado "tipo" segun el tipo de su variable.
- `user` = local
- `globalUser` = Global
- `server` = Servidor

![image](https://github.com/quabwww/Laderboard-Multi-Page/assets/148601206/4bf1f4ee-ea7f-415d-9e3a-06acdcfeecd7)

### $onInteraction
Para que la interacciones de los botones juncionen bien por favor use la guia de arriba que la explicacion seria la misma.

![image](https://github.com/quabwww/Laderboard-Multi-Page/assets/148601206/f8a167fd-2022-43f1-80cd-aaeb39dab5e4)

## Importante este Leadeboard solo muestra hasta 5 paginas
Esto significa que solo muestra 50 usuarios del leaderboard pero esto se puede cambiar pero el resultado seria el lag (Los botones en ciertas ocasiones no funcionarian)

**Nota:** un $repeatMessage sobre otro hace que se multique el valor repetido
Ejemplo:
```python
$repeatMessage[2;$repeatMessage[5;a]]
2 x 5= 10
Resultado: aaaaaaaaaa
