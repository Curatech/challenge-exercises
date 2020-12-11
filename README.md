# Problem #1 :milk_glass:
Sandy works at a groceries store :convenience_store:. There is a large pile of milk boxes that must be paired by flavor for sale. Given an array of integers representing the color of each milk box, determine how many pairs of milk boxes with matching colors there are.

For example, there are **_n = 7_** milk boxes with colors **_ar = [1, 2, 1, 2, 1, 3, 2]_**. There is one pair of color and one of color . There are three odd socks left, one of each color. The number of pairs is **2**


# Function Description

Create the **_MilkMerchant_** function. It must return an integer representing the number of matching pairs of socks that are available.

**_MilkMerchant_** has the following parameter(s):

    n: the number of socks in the pile
    ar: the colors of each sock

# Input Format

The first line contains an integer **_n_**, the number of socks represented in **_ar_**.
The second line contains **_n_** space-separated integers describing the colors **_ar[i]_** of the milk box in the row.

# Constraints
```python
1 ≤ n     ≤ 100
1 ≤ ar[i] ≤ 100 where 0 ≤ i < n 
```
# Output Format

Return the total number of matching pairs of milk boxes that Sandy can sell.

# Sample Inputs
##  Input 
```bash
9
10 20 20 10 10 30 50 10 20
```
## Output
```bash
3
```
##  Input 
```
20
4 5 5 5 6 6 4 1 4 4 3 6 6 3 6 1 4 5 5 5
```
## Output
```bash
9
```
# Explanation
![1474122392-c7b9097430-sock](https://user-images.githubusercontent.com/243380/101201476-6f14e280-362d-11eb-9a32-c66b99361cf8.png)

# Problem #2 :hiking_boot:
An avid hiker keeps meticulous records of their hikes. During the last hike that took exactly **_steps_**, for every step it was noted if it was an uphill, **_Ʊ_** , or a downhill, **_Ɗ_** step. Hikes always start and end at sea level, and each step up or down represents a **_1_** unit change in altitude. We define the following terms:

* A mountain is a sequence of consecutive steps above sea level, starting with a step up from sea level and ending with a step down to sea level.
* A valley is a sequence of consecutive steps below sea level, starting with a step down from sea level and ending with a step up to sea level.

Given the sequence of up and down steps during a hike, find and print the number of valleys walked through. 
# Example
**_steps = 8 path [ƊƊƱƱƱƱƊƊ]_**

The hiker first enters a valley **_2_** units deep. Then they climb out and up onto a mountain **_2_** units high. Finally, the hiker returns to sea level and ends the hike. 
# Function Description

Complete the **_countingValleys_** function in the editor below.

**_countingValleys_** has the following parameter(s):

- int steps: the number of steps on the hike
- string path: a string describing the path

# Returns

- int: the number of valleys traversed

# Input Format

The first line contains an integer **_steps_**, the number of steps in the hike.
The second line contains a single string **_path_** , of  **_steps_** characters that describe the path.

# Constraints
```bash
2 ≤ steps ≤ 10⁶
path[i] ϵ {Ʊ Ɗ}
```
# Samples
## Inputs
```bash
8
UDDDUDUU
```
### Outputs
```bash
1
```
## Inputs
```bash
12
DDUUDDUDUUUD
```
### Outputs
```bash
2
```
# Explanation
If we represent _ as sea level, a step up as /, and a step down as \, the hike can be drawn as:
```bash
_/\      _
   \    /
    \/\/
```

# Problem #3 :1234:
Write a short program that prints each number from 1 to 100 on a new line. 
For each multiple of **_3_**, print **_"Fizz"_** instead of the number. 
For each multiple of **_5_**, print **_"Buzz"_** instead of the number. 
For numbers which are multiples of both **_3_** and **_5_**, print **_"FizzBuzz"_** instead of the number.


# Sample Output:
```bash
...
8
Fizz
Buzz
11
Fizz
13
14
FizzBuzz
16...
```

# Happy hacking!


# Enviando la prueba

Antes de todo muchas gracias por tomarte el tiempo, envía tu resultado a careers@curatech.mx. En el asunto agrega la posicion de la cual estás aplicando, adem&aacute;s segúrate de incluir; en el cuerpo del correo; del cómo te enteraste de la oferta.

---
Nota:
Entrega tu solución contenida en algún repositorio público de GitHub, GitLab, o cualquiera del cual te sientas cómodo. Utiliza toda el workflow de commits, ya que esto es importante para validar tu historial. Evita que sea solo uno.
