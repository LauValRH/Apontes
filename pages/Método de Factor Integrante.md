- El factor integrante es un método para resolver ecuaciones diferenciales lineales de primer orden.
  Este método consiste en buscar un factor determinado, que al multiplicarlo en la ecuación
  $$y' + p(t)y = g(t)$$
  el lado izquierdo quede como la derivada de un producto de ese factor con $y$.
- # Determinación del factor
	- Sea $\mu(t)$ el factor integrante, buscamos que 
	  $$\mu(t)y'+\mu(t)p(t)y = \frac{d}{dt}[\mu(t)y]$$
	  Es decir, $\mu(t)$ tiene que ser de tal manera que 
	  $$[\mu(t)]' = \mu(t)p(t)$$
	  Lo que es equivalente a 
	  $$\frac{[\mu(t)]'}{\mu(t)} = p(t)$$
	  $$\int_{t_{0}}^{t}\frac{[\mu(s)]'}{\mu(s)} ds = \int_{t_0}^{t} p(s)ds$$
	-
-
- # Ecuaciones de la forma $y'=ay+b$
	- Para las ecuaciones de esta forma