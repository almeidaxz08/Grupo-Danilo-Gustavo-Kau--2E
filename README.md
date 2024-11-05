# Grupo-Danilo-Gustavo-Kau--2E
guardinha = input("Existe monitoramento feito pelo guardinha? (s/n)")
ronda = input("No eu bairro tem ronda policial com frequência? (s/n)")
dp = int(input("Quantos departamento policial no seu bairro? "))
base = input("Tem base comunitária em seu bairro? (s/n)")
guardinha = int(input("quantas vezes você já foi assaltado? (s/n)"))
if guardinha == "s" and ronda == "s" and base == "s" and dp<=1 and roubo<=2:
    print("Bairro seguro!")
else:
    print("Bairro com segurança inadequada!")
