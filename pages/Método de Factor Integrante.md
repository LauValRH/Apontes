- El factor integrante es un método para resolver ecuaciones diferenciales lineales de primer orden.
  Este método consiste en buscar un factor determinado, que al multiplicarlo en la ecuación
  $$y' + p(t)y = g(t)$$
  el lado izquierdo quede como la derivada de un producto de ese factor con $y$.
- # Determinación del factor
  id:: 65ef3dee-b5c4-4744-86a0-b69cf49a2c77
	- Sea $\mu(t)$ el factor integrante, buscamos que 
	  $$\mu(t)y'+\mu(t)p(t)y = \frac{d}{dt}[\mu(t)y]$$
	  Es decir, $\mu(t)$ tiene que ser de tal manera que 
	  $$[\mu(t)]' = \mu(t)p(t)$$
	- ## Explicación: ![Explicación factor integrante.pdf](../assets/Demos_1710179442518_0.pdf)
	- Así, por lo tanto, cuando multiplicamos el factor a ambos lados nos queda:
	- ## Desarrollo ![Desarrollo completo.pdf](../assets/Demos_1710370484903_0.pdf)
- # Ecuaciones de la forma $y'=ay+g(t)$
	- Para las ecuaciones de esta forma, de acuerdo con el método anterior, es fácil ver que $p(t) = a$, de esta manera el factor $\mu(t)$ es
	  $$\mu(t) = e^{at}$$
	  y resolviendo la ecuación para un caso general:
	- ## Desarrollo ![Caso y' = ay + g(t) .pdf](../assets/Demos_1710355134137_0.pdf)
- # Problema de valor inicial
	- Regresemos a la ecuación obtenida en ((65ef3dee-b5c4-4744-86a0-b69cf49a2c77)), tenemos un valor t_0 y a este mismo asociado un y_0.
	  Para la forma general de la ecuación, estos dos valores se toman convenientemente para que el cálculo de la forma general sea lo más simplificado posible. Por ejemplo $y(t_0)=0$ con $t_0=0$, sin embargo, en los problemas de valor inicial planteados de la forma
	  $$y' = p(t)y + g(t) \land y(a) = b$$
	  Se sabe que la solución es una función específica de la familia de funciones asociadas. Esto es más fácil verlo con ejemplos
- ## Ejemplos
	- ### Ejemplo 1 ![ejemplo 1.pdf](../assets/Demos_1710556356324_0.pdf)
		- En este caso, es necesario dejarla en términos de la integral porque $e^{\frac{t^2}{4}}$ no se puede expresar en términos de funciones elementales
	- ### Ejemplo 2 /asset
- Alguna cosa
- holi
-