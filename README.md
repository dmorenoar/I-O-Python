# Mostrar dades amb print()

## 🔸 Exemple bàsic
```python
print("Hola, món!")

Sortida: 
Hola, món!
```

## 🔸 Mostrar text i variables
```python
name = "Anna"
age = 16
print("El teu nom és", name, "i tens", age, "anys.")
print(name,age)

Sortida:
El teu nom és Anna i tens 16 anys.
Anna 16
````
## 🔸Mostrar variables concatenant amb +
```python
name = "Pau"
city = "Barcelona"
print("Em dic " + name + " i visc a " + city + ".")

Sortida:  
Em dic Pau i visc a Barcelona.
```
**⚠️ Atenció:**
Només pots concatenar textos (strings).
Si la variable és un número, cal convertir-la amb str():
```python
age = 18
print("Tinc " + str(age) + " anys.")
```

## 🔸 Mostrar text amb format (f-strings)
🧩 És la forma moderna i recomanada.
```python
name = "Pol"
age = 17
print(f"Hola {name}, tens {age} anys.")
```

Llegir dades amb input()
## 🔸 Llegir un text
```python
name = input("Com et dius? ")
print(f"Encantat de conèixer-te, {name}!")
```
## 🔸 Llegir un número enter
```python
age = int(input("Quants anys tens? "))
print(f"L'any vinent tindràs {age + 1} anys.")
```
## 🔸 Llegir un número decimal
```python
height = float(input("Escriu la teva alçada en metres: "))
print(f"La teva alçada és {height} m.")
```
## 🔸Exemple complet
```python
name = input("Nom: ")
age = int(input("Edat: "))
height = float(input("Alçada (m): "))

print(f"Et dius {name}, tens {age} anys i fas {height} metres d'alçada.")

Sortida:  
Nom: Marc
Edat: 18
Alçada (m): 1.75
Et dius Marc, tens 18 anys i fas 1.75 metres d'alçada.
```

