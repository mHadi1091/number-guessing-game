# number-guessing-game

```
#include <iostream>
#include <ctime>
using namespace std;
int guesschance=10;
int main()
{
    int number;
    int guess;
    int guesschance=0;

    cout<<"Player 1: Enter a number: "<<endl;
    cin>>number;

    while (number != guess){

        cout<<"Player 2: Guess player 1 number: "<<endl;
        cin>>guess;

        if (guess < number)
        {
            cout<<"Player 2: The number is too low."<<endl;
        }
        else if (guess > number)
        {
            cout<<"Player 2: The number is too high."<<endl;
        }
        else
        {
            cout<<"Player 2: You are correct! Congratulations!"<<endl;
        }

        guesschance++;
    }

    cout<<"Player 2 you made "<<guesschance<<" Attemps!"<<endl;

    return 0;

}
```

