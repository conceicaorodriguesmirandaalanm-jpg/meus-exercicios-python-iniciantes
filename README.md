def dobro(numero):
    return numero * 2

def quadrado(numero):
    return numero ** 2
    
def cubo(numero):
    return numero ** 3
    
n = int(input("Número: "))

print(f'''Resultados: multiplo de 2 = {dobro(n)}, a potência de 2 = {quadrado(n)} e a potência de 3 = {cubo(n)}.''')
