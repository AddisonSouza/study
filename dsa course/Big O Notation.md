- Mede a **escalabilidade** de um algoritmo, e não necessariamente sua performance absoluta.
    
- Um algoritmo possui complexidade de **tempo** e de **espaço**. A complexidade de tempo representa o crescimento do trabalho realizado pelo algoritmo conforme o tamanho da entrada aumenta.
    

## O(1) — Complexidade constante

- Busca direta em uma estrutura de dados.
    
- Exemplo: acessar um índice específico de um array.
    

## O(log n) — Complexidade logarítmica

- Exemplo: **Binary Search** (busca binária).
    
- A quantidade de operações cresce de forma logarítmica em relação ao tamanho da entrada.
    
- Se o input dobrar, o tempo não dobra necessariamente.
    

## O(n) — Complexidade linear

- No cenário pessimista, percorre todos os elementos de um array.
    
- A complexidade escala linearmente à medida que o input aumenta.
    

## O(n log n) — Complexidade linearítmica

- Exemplos: `Quicksort` (caso médio), `Merge Sort`.
    
- Exceção: `Bubble Sort`, cuja complexidade média e de pior caso é O(n²).
    
- Geralmente associada à estratégia **Divide and Conquer** (dividir para conquistar).
    
- Um exemplo é dividir um array recursivamente pela metade até restar um único elemento e, depois, reconstruir as partes até obter os elementos ordenados.
    

## O(n²) — Complexidade quadrática

- Exemplo: loops aninhados (`for` dentro de `for`) sobre um array.
    
- Para cada elemento do array, o algoritmo verifica todos os outros elementos.
    
- Exemplo clássico: `Bubble Sort`.
    

## Outras complexidades

- **O(2ⁿ) — Exponencial:** o número de operações cresce exponencialmente com o tamanho da entrada.
    
- **O(√n) — Raiz quadrada:** a quantidade de operações cresce proporcionalmente à raiz quadrada de n.
    
- **O(n!) — Fatorial:** crescimento extremamente rápido; pode aparecer em algoritmos que exploram todas as permutações possíveis, como uma solução ingênua para alguns problemas combinatórios. Uma implementação ingênua de Fibonacci costuma ser O(2ⁿ), não O(n!).