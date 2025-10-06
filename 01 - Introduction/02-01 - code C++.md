# 1er code C++

Dans le code ci-dessous, à quoi servent les différentes parties numérotées
~~~cpp
#include <iostream>                         // 1
#include <cstdlib>
using namespace std;                        // 2

int main()                                  // 3
{                                           // 4
    cout << "Hello world"       << endl;    // 5
    cout << "fin de programme"  << endl;
    return EXIT_SUCCESS;                    // 6
}                                           // 4
~~~
~~~cpp
#include <iostream>                         // Input output
#include <cstdlib>
using namespace std;                        // Standard library of C++ functions, plus using them without having to call their library each time

int main()                                  // Main function, called upon program's start
{                                           // Oppening of function
    cout << "Hello world"       << endl;    // Outputs Hello World to the terminal
    cout << "fin de programme"  << endl;    // Outputs fin de programme to the terminal
    return EXIT_SUCCESS;                    // Outputs an int since main() is supposed to return one. Will return 0 to signify having finished without error
}                                           // 4
~~~

<details>
<summary>Solution</summary>

1. Ajouter des librairies utiles au programme
    - *iostream*  : pour *cout*, *cin*, ...
    - *cstdlib*   : pour *EXIT_SUCCESS*
2. Utilise l'espace de nommage *std*. Sans quoi, il faudrait écrire
    - *std::cout*
    - *std::endl*
3. *main* est le nom de la fonction principale (obligatoire)
    - n'a pas de paramêtre () /!\ *main(void)* serait faux (du C)
    - retourne un code d'erreur en entier
4. *{ ... }* bloc de la fonction contenant les instructions
5. Les instructions, toutes se terminent par un ";"
6. Code d'erreur en fin de fonction.

   **NB**: pas obligatoire pour la fonction "main"

</details>
