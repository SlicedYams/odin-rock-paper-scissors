# odin-rock-paper-scissors

Pseudo-code:

    getComputerChoice():
        Declare and initialize a float between 0-1 with math.random()
        Declare string to hold rock, paper, or scissors
        If number is less than or equal to 1/3:
            Initlaize string to "Rock"
        Else if number is less than or equal to 2/3:
            Initialize string to "Paper"
        Else:
            Initialize string to "Scissors"
        Return the string

    getHumanChoice():
        Delare and initialize a variable using prompt()
        Return the variable

    humanScore: a variable to hold the score for human; initialize to 0
    computerScore: a variable to hold the score for computer; initialize to 0

    playRound(Human choice, Computer choice): 
        Change human choice to lowercase
        Change computer choice to lowercase
        If human choice and computer choice match:
            Console log that no one wins, there was a tie
        Else if some one has rock and the other has scissors:
            If the person has rock:
                Console log that they win
                Increase score for person
            Else: 
                Console log that they lose
                Increase score for computer
        Else if some one has scissors and the other has paper
            If the person has scissors:
                Console log that they win
                Increase score for person
            Else: 
                Console log that they lose
                Increase score for computer
        Else if some one has paper and the other has rock
            If the person has paper:
                Console log that they win
                Increase score for person
            Else: 
                Console log that they lose
                Increase score for computer

    playGame():
        For 5 interations:
            Call the play round method while passing the get human choice method and get computer choice method as its parameters

        If human score is greater than computer score:
            Console log that human won
        Else:
            Console log that computer won
        
