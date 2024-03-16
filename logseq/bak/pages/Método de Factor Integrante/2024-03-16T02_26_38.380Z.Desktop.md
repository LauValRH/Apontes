- El factor integrante es un método para resolver ecuaciones diferenciales lineales de primer orden.
  Este método consiste en buscar un factor determinado, que al multiplicarlo en la ecuación
  $$y' + p(t)y = g(t)$$
  el lado izquierdo quede como la derivada de un producto de ese factor con $y$.
- # Determinación del factor
	- Sea $\mu(t)$ el factor integrante, buscamos que 
	  $$\mu(t)y'+\mu(t)p(t)y = \frac{d}{dt}[\mu(t)y]$$
	  Es decir, $\mu(t)$ tiene que ser de tal manera que 
	  $$[\mu(t)]' = \mu(t)p(t)$$
	- ## Explicación: ![Explicación factor integrante.pdf](../assets/Demos_1710179442518_0.pdf)
-
- # Ecuaciones de la forma $y'=ay+g(t)$
	- Para las ecuaciones de esta forma, de acuerdo con el método anterior, es fácil ver que $p(t) = a$, de esta manera el factor $\mu(t)$ es
	  $$\mu(t) = e^{at}$$
	  y resolviendo la ecuación para un caso general:
	- ## Desarrollo ![Explicacion caso p(t) = a.pdf](../assets/Demos_1710199055606_0.pdf)
- ## Ejemplos :D
	-