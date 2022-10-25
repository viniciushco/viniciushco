nota=int(input("Informe uma nota entre 0 e 10:\n"))
while (nota<0) or (nota>10):
        print("Valor invalido.Digite novamente\n")
        nota=int(input("Informe uma nota entre 0 e 10:\n"))
        
if (nota>0) or (nota<10):
    print("Valor valido")
