# Algoritmo Genético F(x,y) = x^2 -2xy + y^2 <br/>
<br/>
en la carpeta fotos se puede ver la primera prueba con una población de 5 individuos y 1000 generaciones<br/>
como se aprecia no converge en una solución óptima.
se aplica una segunda prueba con 1500 generaciones y como se aprecia en el grafico se llega a una solución optima<br/>
se estabiliza 
Se modificó la función de aleatorios. <br/>
	antes el rango inicial x = 0-127, y = 0-255 <br/>
	ahora el rango inicial x = 0-30, y = 0-55 <br/>
	con esto los valores empiezan muy bajos y de puede observar mejor la convergencia. <br/>
<br/>
se modificó en el operador Selección un error de suma.  <br/>
	en leguaje c++ en el ciclo for del operador selección había un "=" cuando debía ser "+=". <br/>
	por eso había un error con los elementos del promedio en el operador Selección. <br/>
<br/>
finalmente, se mejor el operador de Mutación <br/>
	antes los bits del cromosoma era casi-fijos. <br/>
	ahora son completamente aleatorios. <br/>


