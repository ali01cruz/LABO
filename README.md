#%%
class Perro:
    def __init__(self,color,raza,nombre):
        self.color = color
        self.raza = raza
        self.nombre = nombre

    def ladra(self):
        print('wow wow soy gupo lose' ,self.nombre)    


firulais = Perro('amrillo', 'homero','firu')
marcio = Perro('negro', 'crack','marcio')


print('----------------------')
print('la  raza de firu es :')
print(firulais.raza)

firulais.ladra()

print('----------------------')
print('la  raza de marcio es :')
print(marcio.raza)
marcio.ladra()
