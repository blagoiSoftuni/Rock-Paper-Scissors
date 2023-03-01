
string playerMove = string.Empty;
const string rock = "Rock";
const string paper = " Paper";
const string scissors = "scissors";

Console.Write("[r]ock, [p]paper, [s]scissors");
string input = Console.ReadLine();

if (input == "r" || input == "rock")
{
    playerMove = "Rock";
}
else if (input == "p" || input == "paper")
{
    playerMove = "paper";

}
else if (input == "s" || input == "scissors")
{
    playerMove = "scissors";
}
else
{
    Console.WriteLine("Wrong input. Try again...");
    return;

}
Random random = new Random();
int computerRandomMove = random.Next(1, 4);
string ComputerMove = string.Empty;
switch (computerRandomMove)
{
    case 1:
        ComputerMove = "Rock";
        break;

    case 2:
        ComputerMove = "paper";
        break;

    case 3:
        ComputerMove = "scissors";
        break;
        Console.Write($"The computer choose {ComputerMove}");
       
       }if ((playerMove == rock && ComputerMove == scissors) || ;
       (playerMove = paper && ComputerMove == Rock)||
       (playerMove == scissors && ComputerMove == paper));
        Console.WriteLine("You win. ");
