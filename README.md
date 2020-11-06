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
  
![0](https://user-images.githubusercontent.com/69210578/98312108-c0d73800-1faf-11eb-809e-aafa21a02342.png)
![2](https://user-images.githubusercontent.com/69210578/98312112-c16fce80-1faf-11eb-8835-67109d159171.png)
![6](https://user-images.githubusercontent.com/69210578/98312114-c2086500-1faf-11eb-8015-18c78ba10dd2.png) 
![12](https://user-images.githubusercontent.com/69210578/98312116-c2a0fb80-1faf-11eb-8a54-738e739ee7c5.png)
![16](https://user-images.githubusercontent.com/69210578/98312117-c2a0fb80-1faf-11eb-91d8-df940a5d2099.png)
![24](https://user-images.githubusercontent.com/69210578/98312119-c3399200-1faf-11eb-88a4-a73a5594ef4a.png)

![caso_1](https://user-images.githubusercontent.com/69210578/98313618-02b5ad80-1fb3-11eb-9782-b38adb55df89.png)
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
  
  
![0](https://user-images.githubusercontent.com/69210578/98312200-fb40d500-1faf-11eb-87da-f0cffcd5c474.png)
![2](https://user-images.githubusercontent.com/69210578/98312202-fb40d500-1faf-11eb-889b-23a0b6b27982.png)
![6](https://user-images.githubusercontent.com/69210578/98312204-fbd96b80-1faf-11eb-9e3f-45cb61972d81.png)
![12](https://user-images.githubusercontent.com/69210578/98312194-fa0fa800-1faf-11eb-9359-bd3eb57d57c4.png)
![16](https://user-images.githubusercontent.com/69210578/98312197-faa83e80-1faf-11eb-8526-290d21b0c61a.png)
![24](https://user-images.githubusercontent.com/69210578/98312198-faa83e80-1faf-11eb-9ecb-2a42430f07d3.png)
  
![caso_2](https://user-images.githubusercontent.com/69210578/98313628-06493480-1fb3-11eb-931a-8073953778d4.png)
![caso_2](https://user-images.githubusercontent.com/69210578/98310797-aa7bad00-1fac-11eb-8e58-100ee4978f30.gif)


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
 
![0](https://user-images.githubusercontent.com/69210578/98312281-1dd2ee00-1fb0-11eb-8192-47b8fe6590c1.png)
![2](https://user-images.githubusercontent.com/69210578/98312283-1e6b8480-1fb0-11eb-91b9-3b1c266c2a39.png)
![6](https://user-images.githubusercontent.com/69210578/98312284-1e6b8480-1fb0-11eb-8b1e-a84f1538f471.png)
![12](https://user-images.githubusercontent.com/69210578/98312277-1ca1c100-1fb0-11eb-889d-f9ce7811c347.png)
![16](https://user-images.githubusercontent.com/69210578/98312278-1d3a5780-1fb0-11eb-9453-107368e67975.png)
![24](https://user-images.githubusercontent.com/69210578/98312279-1dd2ee00-1fb0-11eb-9723-d51c4b9e946a.png)


![caso_3](https://user-images.githubusercontent.com/69210578/98313635-0a755200-1fb3-11eb-9f9f-dddc31c4e313.png)
![caso_3](https://user-images.githubusercontent.com/69210578/98310827-b6676f00-1fac-11eb-8de5-a6ce6801a8b2.gif)


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
  
 
![0](https://user-images.githubusercontent.com/69210578/98312319-38a56280-1fb0-11eb-83d7-6721a6351b10.png)
![2](https://user-images.githubusercontent.com/69210578/98312320-393df900-1fb0-11eb-98ef-f534ebf82266.png)
![6](https://user-images.githubusercontent.com/69210578/98312321-39d68f80-1fb0-11eb-9e2a-ffb99f870c77.png)
![12](https://user-images.githubusercontent.com/69210578/98312313-37743580-1fb0-11eb-93d7-4ba1aca94a23.png)
![16](https://user-images.githubusercontent.com/69210578/98312316-380ccc00-1fb0-11eb-857c-08fff942d571.png)
![24](https://user-images.githubusercontent.com/69210578/98312317-38a56280-1fb0-11eb-8531-8ce2fe060c36.png)

![caso_4](https://user-images.githubusercontent.com/69210578/98313638-0ba67f00-1fb3-11eb-9272-a621d86947bb.png)
![caso_4](https://user-images.githubusercontent.com/69210578/98310837-bb2c2300-1fac-11eb-9397-e03d91d09f72.gif)


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


![0](https://user-images.githubusercontent.com/69210578/98312350-4d81f600-1fb0-11eb-86de-5a24a4506ca2.png)
![2](https://user-images.githubusercontent.com/69210578/98312351-4d81f600-1fb0-11eb-9f4f-5eac9cabbfbe.png)
![6](https://user-images.githubusercontent.com/69210578/98312353-4e1a8c80-1fb0-11eb-9224-b6a9672223f7.png)
![12](https://user-images.githubusercontent.com/69210578/98312345-4c50c900-1fb0-11eb-830c-a5a8314c72f6.png)
![16](https://user-images.githubusercontent.com/69210578/98312347-4ce95f80-1fb0-11eb-95b6-2149f48f34bf.png)
![24 (2)](https://user-images.githubusercontent.com/69210578/98312348-4ce95f80-1fb0-11eb-994b-f9f0c94130cd.png)


![caso_5](https://user-images.githubusercontent.com/69210578/98313643-0d704280-1fb3-11eb-9129-a02cee3a09b9.png)
![caso_5](https://user-images.githubusercontent.com/69210578/98310847-c1220400-1fac-11eb-8880-9c01786ecce0.gif)


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
  
  
![0](https://user-images.githubusercontent.com/69210578/98312395-638fb680-1fb0-11eb-9e58-7e8848f20629.png)
![2](https://user-images.githubusercontent.com/69210578/98312396-638fb680-1fb0-11eb-9b8f-04a0702b0cb5.png)
![6](https://user-images.githubusercontent.com/69210578/98312397-64284d00-1fb0-11eb-8f49-d141824d5430.png)
![12](https://user-images.githubusercontent.com/69210578/98312390-625e8980-1fb0-11eb-92f2-f1a0ef42fb46.png)
![16](https://user-images.githubusercontent.com/69210578/98312392-62f72000-1fb0-11eb-9c1f-7e366f4c3fcb.png)
![24](https://user-images.githubusercontent.com/69210578/98312394-62f72000-1fb0-11eb-9bac-dbf5f1aa5a9a.png)

![caso_6](https://user-images.githubusercontent.com/69210578/98313645-0f3a0600-1fb3-11eb-8528-756ed42fead3.png)
![caso_6](https://user-images.githubusercontent.com/69210578/98310857-c8491200-1fac-11eb-91a7-8ce775ebdfc4.gif)

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
  
  
![0](https://github.com/ooyarce/MCOC---Entrega-5/blob/main/Caso%207/Resultados/frame_0000.png)
![2](https://github.com/ooyarce/MCOC---Entrega-5/blob/main/Caso%207/Resultados/frame_0004.png)
![6](https://github.com/ooyarce/MCOC---Entrega-5/blob/main/Caso%207/Resultados/frame_0012.png)
![12](https://github.com/ooyarce/MCOC---Entrega-5/blob/main/Caso%207/Resultados/frame_0024.png)
![16](https://github.com/ooyarce/MCOC---Entrega-5/blob/main/Caso%207/Resultados/frame_0032.png)
![24](https://github.com/ooyarce/MCOC---Entrega-5/blob/main/Caso%207/Resultados/frame_0048.png)

![caso_7](https://user-images.githubusercontent.com/69210578/98313645-0f3a0600-1fb3-11eb-8528-756ed42fead3.png)
![caso_7](https://user-images.githubusercontent.com/69210578/98310857-c8491200-1fac-11eb-91a7-8ce775ebdfc4.gif)

