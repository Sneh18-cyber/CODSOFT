#include <iostream>
#include <cstdlib> //Also write like this #include<stdlib.h>
#include <ctime> // Also write like this #include<time.h>
using namespace std;

int main() {
    srand(time(0));  // Seed for random number
    int secretNumber = rand() % 100 + 1;  // Generate random number between 1 and 100
    int guess;
    int attempts = 0;

    cout << "Welcome to the Number Guessing Game!" << endl;
    cout << "Guess the number between 1 and 100.\n" << endl;

    do {
        cout << "Enter your guess: ";
        cin >> guess;
        attempts++;

        if (guess > secretNumber)
            cout << "Too high! Try again.\n";
        else if (guess < secretNumber)
            cout << "Too low! Try again.\n";
        else
            cout << "Congratulations! You guessed the number in " << attempts << " attempts.\n";

    } while (guess != secretNumber);

    return 0;
}
