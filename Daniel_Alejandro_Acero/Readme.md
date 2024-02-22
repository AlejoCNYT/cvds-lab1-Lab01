# Hello there!! 
I´m *Alejo* ☄️


![IMG_20230705_112216](https://github.com/AlejoCNYT/cvds-lab1-Lab01/assets/89206637/bd8d5e44-370f-443f-8adc-dba9131bad93)

## About me

-   I ❤️‍🔥 **programming and** **Maths**!
-   I enjoy **reading, board g♣️mes and [karate-do](https://es.wikipedia.org/wiki/Karate) 🦖**. 

## Experience

1. 🧮 Teaching applied mathematics. 🏰
2. 👨‍💻 Computer lab monitor. 
3. Administrative Assistant. 💱

## Github

![id | 1000046581](https://github.com/AlejoCNYT/cvds-lab1-Lab01/assets/89206637/9faab0fc-ec3d-424e-a626-181bdb49be38)
![Captura de pantalla 2024-02-05 055201](https://github.com/AlejoCNYT/cvds-lab1-Lab01/assets/89206637/5fe82a16-e65a-4bb0-a2ae-255586461058)

### Carné

```

Escuela Colombiana de Ingeniería Julio Garavito 
Daniel Alejandro acero Varela
codigo: 2046581
Ing. Sistemas
Estudiante

```

## Code 

```



program MaximoArray;

const
    TAMANYO = 5;
    
var
    datos : array[1..TAMANYO] of integer;
    i : integer;
    maximo : integer;
    
begin
    datos[1] := 40;
    datos[2] := 30;
    datos[3] := 50;
    datos[4] := 20;
    datos[5] := 10;
    
    maximo := datos[1];
    for i := 2 to TAMANYO do
        begin
            if datos[i] > maximo then
                maximo := datos[i];
        end;
        
    writeln('El maximo es ', maximo);
            
    readln;
    
end.


```
