# exercicio_16

#measuring the sides of a triagule

opo = float (input ('comprimento do cateto oposto '))
adj = float (input ('comprimento do cateto adjacente '))
hip = ((opo ** 2) + (adj ** 2))
realh = (hip ** (1/2))
print ('a hipotenusa deste triangulo ira medir {:.2f}'.format (realh))
