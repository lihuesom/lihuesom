<h2> Hi, I'm Lina Hueso</h2>
<p>
  <em>Software engineering student at <a href="https://www.poli.edu.co/">Politecnico Grancolombiano</a>
  </br>Junior Developer ✨  </em>
 </p>
<p>I am starting in backend development, with Python and Java languages. I have little experience in the programming field, but I have 3 years in data analysis. <br/>I hope you find my repos useful</p>

```javascript
import random

//Guess the number

def run():
    numero_aletorio = random.randint(1,100)
    numero_elegido = int(input("Elige un número del 1 al 100: "))
    while numero_elegido != numero_aletorio:
        if numero_elegido < numero_aletorio:
            print("Busca un número más grande")
        else:
            print("Busca un número más pequeño")
        numero_elegido = int(input("Elige otro número: "))
    print("¡Ganaste!")


if __name__ == "__main__":
    run()
```
