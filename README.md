![](https://pypi-camo.freetls.fastly.net/c6d123c80807cb0c81e95ecd063048a1c82f6ede/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f70726163746963616c5f666f722d756e7072656469637461626c655f6e756d6265725f67656e65726174696f6e5f666f725f6175746874656e7469636174696f6e2d626c7565) ![](https://img.shields.io/badge/Latest_release-secretrandom_v2.2.2-orange) ![](https://img.shields.io/badge/on-PyPI-blue)

# secretrandom (Python package)

## The combination of the **random** module's features with the security of the **secrets** module for unpredictable random number generation and random character generation.

#### Includes:

*   Password & passcode generation for authentication.
*   Random number generation features from the random module.
*   Powered with **⚡true optimization and unpredictability.⚡**

- - -
#### PyPI project: https://pypi.org/project/secretrandom/
#### Changelog: https://github.com/dUhEnC-39/secretrandom/blob/main/CHANGELOG.txt

## Installation
Open your system's terminal (ex: CMD, Powershell, etc.)
```
pip install secretrandom
```
Or in the Python terminal
```
>>> import pip
>>> pip.main(['install', 'secretrandom'])
```
- - -
## Documentation guide

All functions:

*   `randchar()` — Password/Character generation
*   `randcode()` — Passcode and PIN generation
*   `randint()` — Random whole integer generation
*   `randflt()` — Random float generation
*   `choice()` — For random choices
*   `shuffle()` — For random shuffles

### `randchar()`

Generates a random character based on int: length (1st argument)

```
import secretrandom

password = secretrandom.randchar(1)
print(password) # Prints out a random character
```
Print multiple characters to makeup a password.

```
password = secretrandom.randchar(17)
print(password) # Prints out multiple characters like a password
```

### `randcode()`

Generates passcodes or PINs based on the length as the only argument.

```
passcode = secretrandom.randcode(6)
print(passcode) # Prints out passcode with 6 integers   
```

### `randint()`

Random whole integer generator starting from 1st arg to 2nd arg with steps (3rd arg)

```
random_num = secretrandom.randint(1, 4)
print(random_num) # Prints out a number between 1-4    
```

## OR

```
random_num = secretrandom.randint(1, 6, 2)
print(random_num) # Prints out a number either 2, 4, or 6   
```

### `randflt()`

Random float generator from 1st arg to 2nd arg

```
random_flt = secretrandom.randflt(1, 2)
print(random_flt) # Prints out random float from 1 to 2 (like 1.673)  
```

### `choice()`

Chooses part of a list of values.

```
choice = secretrandom.choice('abcd')
print(choice) # Prints out what it chose (either a, b, c, or d)  
```

### `And finally shuffle()`

Shuffles a list of values.

```
data = ['a', 'b', 'c', 'd']
secretrandom.shuffle(data)
print(data) # Shuffles the list of values.
```

Any questions? Email [here](mailto:albeback01@gmail.com?subject=Python%20library%20secretrandom%20question.)
