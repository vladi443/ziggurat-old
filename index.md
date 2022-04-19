## Ziggurat Systems

Welcome to the Ziggurat Systems Project main page. Ziggurat Systems is a github repository made to organize and list the open-source projects I am currently working on. Feel free to use, modify, or share any of the code that is uploaded here. All the projects will be registered under the GNU GPLv3 software license. For more information, [go to the ziggurat github repository](https://github.com/vladi443/ziggurat)'s README file. 

## Projects

### Wordle Dictionary

---

Wordle Dictionary is a C++ algorithm that scores words based on their match probability for the popular web game _Wordle_. Wordle Dictionary recieves a 5-letter input word followed by a 5-digit input number that indicates if the specific charachter is present in the mystery word. After scoring each word Wordle Dictionary displayes the top 20 words that match the given pattern. The user can choose one of these words and input it again, followed by a new 5-digit number to represent the pattern of the newly entered word.

Wordle Dictionary uses a 5-digit number to represent the pattern of the inputed word. 0 indicates that the charachter at the corresponding location in the word is not present, 1 indicates the charachter is present but in different location, and 2 indicates the charachter is present in that exact location. Wordle Dictionary stores the charachters not present in the mystery word to better score and sort words based on their matching probability.

Wordle Dictionary outputs matching words together with their definition when available, which allows the user to select the most optimal word from the list provided.

Wordle Dictionary also has a BETA option to compute the best starting word. This function calculates the times each letter is present in the list of words, and constructs words with the most common letters. This method allows for the starting word to have the highest probability of containing a matching letter.

Wordle Dictionary provides a debug-mode that allows the user to track a certain word's score throughout the algorithm, allowing for any scoring bugs/misputs to be traced. Debug-mode can be enabled at the beginning of the program.

Wordle Dictionary is registered under the GNU GPLv3 software license and its source-code is avaiable on github.

Go to [Wordle Dictionary Github Repository](https://github.com/vladi443/dictionary/blob/main/README.md)

Go to [Official Wordle Website](https://www.nytimes.com/games/wordle/index.html)

### Sierpinski triangle

---

Sierpinski triangle is a geometric fractal based on equilateral triangles. The sequence begins with one equilateral triangle with custom size, and by dividing the sides of the triangle in half a pattern emerges which represents the Sierpinski triangle. If the pattern is continued forever, the triangle will contain an infinite amount of smaller equilateral triangles within it.

The Triangles fractal C++ algorithm simulates what the Sierpinski triangle will appear like in n iretations. The algorithm uses the Chaos principle to simulate the appearance of the triangle rather than the normal removing triangles technique. The Chaos game states that if a point is placed halfway between two other points, one being a point chosen at random from withing the triangle, and the other chosen at random being from the original triangle, after n iretations the cluster of points will resemble the Sierpinski triangle.

The Triangles fractal C++ algorithm follows the Chaos game principles by randomly selecting two points and creating a new point located in the middle of them. The algorithm repeats this process n-times, which is the amount of iretations indicated by the user at the beginning of the program. After cicling through all the iretations, the algorithm creates a simple grid and displays each point on it.

Triangles fractal is registered under the GNU GPLv3 software license and its source-code is avaiable on github.

Go to [Triangle fractal Github Repository]()

Learn more about the [Sierpinski Triangle]()

### Primes

---

Primes is a C++ algorithm that finds all prime numbers between 10,000 - 99, 999 and scores their match probability for the web game _Primel_. Primes recieves a 5-digit input prime number followed by a 5-digit input number that indicates wheter the specific digit is present in the mystery prime number. Primes would use that information to score the remaining prime numbers accordingly and present the newly updates scores. Primes would continue this proccess until the user indicates the prime number has been found.

Similarly to Wordle Dictionary, Primes uses a 5-digit number to represent the pattern of the inputed prime number. Unlike Wordle Dictionary however, both input and output for Primes can be a single digit, without space separation between the individual charachters. Primes uses the same output scheme as Wordle Dictionary to represent the pattern of the inputted prime number, which is a 0 for the digit is not present in the mystery prime number, 1 for the digit is present in the mystery prime number but in a different location, and 2 to represent the digit is present at the corresponding location of the mystery prime number.

Primes has a BETA option that computes the best starting prime number, which is rated based on the most used digits in the list of prime numbers. Primes also scores prime numbers based on the uniqueness of their digits, meaning 19237 would be rated slightly higher than 10007.

Primes is registered under the GNU GPLv3 software license and its source-code is available on github.

Go to [Primes Github Repository](https://github.com/vladi443/primes)

Go to [Official Primel Website](https://converged.yt/primel)

## About

I am a high school computer science student interested in computer algorithms, computer security, and algorithm efficiency. I am taking computer science and cyber security clases together with high level math classes. All the projects available here are made using skills learned in high school, and are either school projects or individual projects. All the projects posted here will be licensed under the GPL2 software license.

All the projects are open-source and can be used or modified at no cost. If you want to support my work you can [buy me a tea (coming soon)](https://www.google.com) to warm me up, or share this site and its project with others.
