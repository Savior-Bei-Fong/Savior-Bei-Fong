- 👋 Hi, I’m @Savior-Bei-Fong
- 👀 I’m interested in ... Cyber Security ( RET BTEAM ) and Python coding //  Games Coding with Unity, Unreal and with CryEngine
- 🌱 I’m currently learning Python Coding
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

you can contakt me on saviorsniper4574@gmail.com

i am 27 Jears old and i lifing in Germany Bonn, my Language is German...

now he a simple python code


# == (gleich) und != (ungleich) &/& function &/& while Bedingung: &/& for Bedingung:
# "break" stop der Schleife  &/& "continue" rest von Schleife ignoriert
# Bedingung wird sofort vor der Wiederdurchführung &/& des Befehlsblocks erneut kontrolliert.
# ------------------------------------------------------------------------
from random import randint
eingabe = int(input("Gib eine positive ganze Zahl an: "))
liste = []
for i in range(eingabe):
    liste.append(randint(0, 100))
result = 0
for i in range(eingabe):
    result = result + liste[i]
result = result / len(liste)
print("Das Ergebnis lautet " + str(result) + ".")
# ------------------------------------------------------------------------
def bspfunktionfuerrueckgabe(eingabewert):
    rueckgabewert = eingabewert * 3
    return rueckgabewert
ergebnisausfunktion = bspfunktionfuerrueckgabe (5)
print(ergebnisausfunktion)
# ------------------------------------------------------------------------
