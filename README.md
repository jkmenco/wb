# Dado un arreglo de enteros que representan barreras con diferentes alturas (m) y con separación de 1m. Encuentre cual pareja de barreras puede contener la mayor cantidad de agua.

## **Input:**[1,5,8,9,4,5]<br>

![image](https://cdn.cacher.io/attachments/u/3iimr1rui030a/I0jeQJxLDbDauIPberC1U4u6JHI_ssj5/Screen_Shot_2022-12-12_at_5.49.10_PM.png)


## **ejemplo:**[3,5] *contiene 10 lts*

![image(3,5)](https://cdn.cacher.io/attachments/u/3iimr1rui030a/1oI7KtBMgaYV5K1hVseYkxlj1k2QegMG/Screen_Shot_2022-12-13_at_10.49.02_AM.png)<br>
<br>

# Encontrar cual pareja de barreras contiene mayor cantidad de agua.

[1,5,8,9,4,5]

<br>
<br>
<br>
<br>
# conclusiones

* Se debe calcular entre 1 pareja (y rango entre estos) cual puede contener la mayor cantidad de agua

* se puede calcular el area de un rectángulo entre estos grupos

* la separación entre cada barrera es de 1 metro, la base sera siempre 1m y la altura limite dependerá del mas bajo del grupo

* Si se logra concatenar en escalera se encontrara el máximo posible, es posible encontrar 2 eventos:
	1. Entre medio de la pareja exista un menor, su altura se debe ignorar y tener en cuenta solo su alrededor [9-4-5)] el elemento 4 no se cuenta para calcular el limite de 5
	2. La pareja se conforme por una escalera descendente la cual calcular la cantidad de agua sera mas eficiente
<br>

# Todo esto dentro del rango de numero de la lista. <br>Al final, mostrar resultados, los 2 números formados con la mayor cantidad de agua y la cantidad de agua total.

<br>
<br>
<br>
<br>
