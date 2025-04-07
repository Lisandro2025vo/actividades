# actividades

##1
---
import numpy as np  
import pandas as pd  
b = np.array([[1,2],[3,4],[5,6]])  
a = np.array([0,1,2,3,4,5,6,7,8,9,10])  
df = pd.DataFrame(b, index=['FILA1','FILA2','FILA3'], columns=['COLUMNA1','COLUMNA2'])  
Provincia = ['cordoba', 'san luis', 'buenos aires', 'rioja', 'tucuman']  
poblacion = [6000000, 5000000, 4000000, 8000000, 1000000]  
diccionario = {'Provincia': Provincia, 'poblacion': poblacion}  
df2 = pd.DataFrame(diccionario)  
print(df2)
