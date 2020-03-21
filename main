print("Premi 1 per il calcolo combinatorio.")
print("Premi 2 per il calcolo di eventi possibili.")
print("Premi 3 per il principio di inclusione/esclusione.")
print("Premi 4 per il Teorema di Bayes.")
a = int(input())

# calcolo combinatorio
if a == 1:
    n = int(input("Inserisci il numero di oggetti: "))
    r = int(input("Inserisci il numero raggruppamenti: "))

    def fattorial(number):
        for i in range((number-1), 0, -1):        
           number = number * i 
        return number

    result = fattorial(n) / (fattorial(n - r) * fattorial(r))
    print("Il binomio di Newton è: ", result)

# calcolo di eventi possibili
elif a == 2:
    E = int(input("Inserisci il numero di eventi possibili E: "))
    F = int(input("Inserisci il numero di eventi possibili F: "))
    EF = E*F
    print(EF)
    
# principio di inclusione/esclusione
elif a == 3:
    n = int(input("Inserisci numero di eventi equiprobabili: "))
    P = float(input("Inserisci la probabilità di ogni evento: "))

    somma_P = n*P
    probabilita_finale = somma_P
    print("La probabilità finale è: ", probabilita_finale)

# Teorema di Bayes
elif a == 4:
    E_F = float(input("Inserisci il numero di eventi in comune tra E ed F: "))
    F = float(input("Inserisci il numero di eventi possibili F: "))
    S = float(input("Inserisci il numero di eventi totali S: "))
    P_F = float(F/S)
    P_E_F = float(E_F/S)
    
    P_Bayes = P_E_F / P_F
    print("La probabilità di Bayes è: ", P_Bayes)
