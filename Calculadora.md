while True:
    print("Elije una opcion")
    print("1 - Sumar")
    print("2 - Restar")
    print("3 - Multplicar")
    print("4 - Dividir")
    print("5 - Salir\n\n")

    choice = input("Elige tu opcion(1/2/3/4/5): ")
    if choice in ('1','2','3','4','5'):
        if choice == '1':
            num1 = float(input("\n\tIngresa el primer numero: "))
            num2 = float(input("\n\tIngresa el segundo numero: "))
            print("\n\t\tResultado: ",num1, "+", num2, "=", num1 + num2,"\n")
        elif choice == '2':
            num1 = float(input("\n\tIngresa el primer numero: "))
            num2 = float(input("\n\tIngresa el segundo numero: "))
            print("\n\t\tResultado: ",num1, "-", num2, "=", num1 - num2,"\n")
        elif choice == '3':
            num1 = float(input("\n\tIngresa el primer numero: "))
            num2 = float(input("\n\tIngresa el segundo numero: "))
            print("\n\t\tResultado: ",num1, "*", num2, "=", num1 * num2,"\n")
        elif choice == '4':
            num1 = float(input("\n\tIngresa el primer numero: "))
            num2 = float(input("\n\tIngresa el segundo numero: "))
            print("\n\t\tResultado: ",num1, "/", num2, "=", num1/num2,"\n")
        elif choice == "5":
            print("cerro el programa")
            break
    else:
        print("No se reconoce este comando")
