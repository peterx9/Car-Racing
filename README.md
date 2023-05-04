# Car-Racing
## студенты
- `Хабиб Петер`
- `Гомаа Халид`
## Основное
- language: `C#`
- Genre: `2D` `Racing` `Surviving` 
## Сюжет
The main idea is to survive as long as u can, the player controling the main car and he has to avoid the other cars

## Игровой мир
The game world in on the street where cars race each other

## Геймплей
the game starts, your score is 0.

you can control the car using the `keyboard arrows`

the game target is collecting as much high score as you can.

you have to avoid the other cars and if you touch them your car will destroy

when you die you will receive a medal
- if your score `40-500` you receive `Bronze` medal
- if your score `500-2000` you receive `Silver` medal
- if your score is higher than `2000` you recive `Gold` medal

## Game difficulty
you might think the game is easy but it isn't, the game difficulty is increasing after scoring points (race the other cars)

while your score gets higher and higher your speed also increases so the game becomes harder

## Game elements
- `Racing`
- `Score`
- `Challenges`

## Классы игры
- `Form1.cs` here you can find these methods `keyisdown,keyisup` these two methods are written to control the movment of the player , `gameTimerEvent` this method is written to count the time, calculate the score and give prizes, `changeAIcars` this method is to change the enimes randomly , `gameOver,ResetGame and restartGame` these 3 method is to reset and restart the game , `Play sound` this method is to play crash sound when the car crashes

- `Form1.Designer.cs` here where is the background and the designs are created using `windows form`

- `Properties/Resources.Designer` The main idea of this class is to provide a centralized location for managing and accessing the game's resources. This makes it easier to manage and update resources, as well as to ensure that they are used consistently throughout the game


