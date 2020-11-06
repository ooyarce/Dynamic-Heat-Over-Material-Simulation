# MCOC-Entrega-5


* Para todos los casos cuando se da una temperatura en específico lo que se hace es simplemente reemplazar esta en las condiciones iniciales como se puede apreciar en el código, un caso distinto es cuando se entrega un gradiente, aquí lo que se hace es sumarle el gradiente por dx (o dy, pero como son iguales siempre se deja como dx) a la temperatura inicial en el borde dado. Por último para el caso 7 se agrega una línea de código (línea 105) en la que se define el cambio sinusoidal de la temperatura en un día partiendo con una temperatura ambiente de 20°.     (No se explica cada caso en particular porque sería mucho repetir lo mismo, pero en todos se siguieron los pasos descritos)

# Caso 1:
* Condiciones de Borde:
  * Condición Inicial: 20°
  * Borde Superior: 0°
  * Borde Izquierdo: 20°
  * Borde Inferior: 20°
  * Borde Derecho: 0°
  * a: 1.0
  * b: 1.0
  * Nx: 30
  * Ny: 30

![caso_1](https://user-images.githubusercontent.com/69210578/98310764-9637b000-1fac-11eb-8a4c-739b7f29d2f2.png)
![caso_1](https://user-images.githubusercontent.com/69210578/98310779-a059ae80-1fac-11eb-85c5-2d71c9177df8.gif)


# Caso 2:
* Condiciones de Borde:
  * Condición Inicial: 20°
  * Borde Superior: 0°
  * Borde Izquierdo: 20°
  * Borde Inferior: 20°
  * Borde Derecho: Gradiente 0°
  * a: 1.0
  * b: 1.0
  * Nx: 30
  * Ny: 30
  
![caso_2](https://user-images.githubusercontent.com/69210578/98310797-aa7bad00-1fac-11eb-8e58-100ee4978f30.gif)
![caso_2](https://user-images.githubusercontent.com/69210578/98310810-b0718e00-1fac-11eb-9acb-c56822b3671a.png)

# Caso 3:
* Condiciones de Borde:
  * Condición Inicial: 10°
  * Borde Superior: 0°
  * Borde Izquierdo: 20°
  * Borde Inferior: 20°
  * Borde Derecho: 20°
  * a: 1.0
  * b: 1.0
  * Nx: 30
  * Ny: 30
 
![caso_3](https://user-images.githubusercontent.com/69210578/98310827-b6676f00-1fac-11eb-8de5-a6ce6801a8b2.gif)
![caso_3](https://user-images.githubusercontent.com/69210578/98310830-b7989c00-1fac-11eb-8664-54e6b38c7378.png)

# Caso 4:
* Condiciones de Borde:
  * Condición Inicial: 10°
  * Borde Superior: 0°
  * Borde Izquierdo: 20°
  * Borde Inferior: 20°
  * Borde Derecho: Gradiente 0°
  * a: 1.0
  * b: 0.5
  * Nx: 15
  * Ny: 30
  
![caso_4](https://user-images.githubusercontent.com/69210578/98310837-bb2c2300-1fac-11eb-9397-e03d91d09f72.gif)
![caso_4](https://user-images.githubusercontent.com/69210578/98310842-be271380-1fac-11eb-9b4c-694dda222337.png)

# Caso 5:
* Condiciones de Borde:
  * Condición Inicial: 5°
  * Borde Superior: Gradiente 0°
  * Borde Izquierdo: 25°
  * Borde Inferior: Gradiente 0°
  * Borde Derecho: 25°
  * a: 1.0
  * b: 1.0
  * Nx: 30
  * Ny: 30

![caso_5](https://user-images.githubusercontent.com/69210578/98310847-c1220400-1fac-11eb-8880-9c01786ecce0.gif)
![caso_5](https://user-images.githubusercontent.com/69210578/98310851-c2533100-1fac-11eb-95f6-d730b3a659e2.png)

# Caso 6:
* Condiciones de Borde:
  * Condición Inicial: 30°
  * Borde Superior: Gradiente 0°
  * Borde Izquierdo: 10°
  * Borde Inferior: Gradiente 0°
  * Borde Derecho: Gradiente 0°
  * a: 1.0
  * b: 1.0
  * Nx: 30
  * Ny: 30

![caso_6](https://user-images.githubusercontent.com/69210578/98310857-c8491200-1fac-11eb-91a7-8ce775ebdfc4.gif)
![caso_6](https://user-images.githubusercontent.com/69210578/98310860-ca12d580-1fac-11eb-8178-fc629f353344.png)

# Caso 7:
* Condiciones de Borde:
  * Condición Inicial: 20°
  * Borde Superior: Temperatura ambiental (sinusoide con variación de 10°, período de 1 día)
  * Borde Izquierdo: Gradiente 0°
  * Borde Inferior: Gradiente 0°
  * Borde Derecho: Gradiente 0°
  * a: 1.0
  * b: 1.0
  * Nx: 30
  * Ny: 30
  
