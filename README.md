Start
    Set correctNumber = random number between 1 and 100
    Declare userGuess

    Do
        Display "Enter your guess (1-100):"
        Input userGuess

        If userGuess < correctNumber Then
            Display "Too low. Try again."
        Else If userGuess > correctNumber Then
            Display "Too high. Try again."
        Else
            Display "Correct! You guessed the number."
        End If
    While userGuess != correctNumber
End
