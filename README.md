# Course Number 1

# Variable (string)

 

We will first start by creating a string variable like this 

```csharp 
string chain = Console.ReadLine();
``` 

And will write it

```csharp 
string chain = Console.ReadLine();

Console.WriteLine(chain);
``` 

The string variable will ask you what you want to write and will therefore write it

# Variable (int)

The int variable is used for numbers, written as a string except that you are going to put a number. that gives us that

```chsarp
int number = 3;
```

and

```chsarp
int number = 3;
Console.WriteLine(number);
```

# Variable (bool)

The Boolean variable is a variable of truths. it's close to the conditions, Like this :
```csharp
bool the_meal_is_good = true;

if (the_meal_is_good)
{
    Console.WriteLine("The meal must have been delicious");
}


```

# Condition (if)

Conditions are written like this

```csharp
string stan = Console.ReadLine();

if (stan == "Stanley")
{
   Console.WriteLine("Stanley is the best programmer, better than zellidev");
}
```

# Condition (else)

Else is used to give a possible exit from the if. We will resume our example from before, It is written like this

```csharp
string stan = Console.ReadLine();

if (stan == "Stanley")
{
   Console.WriteLine("Stanley is the best programmer, better than zellidev");
}
else 

{
   Console.WriteLine("hum, write Stanley please : )");
]

```
# Loop (for)

The for loop is used to repeat something until it stops. It is written like that. We will create a for loop and repeat it 400 times
```csharp

int count;
for (count = 1; count < 400; count++)
{
    Console.WriteLine("#" + count);
}
```

other example

```csharp
string[] gf-user = new string[] { "Smooth", "Stanley", "Stanford", "Bill", "Mabel", "Deeper", "Wendy" };
int indice;
for (indice = 0; indice < 7; indice++)
{
    Console.WriteLine(gf-user[indice]);
}
```

# Loop (foreach)

The foreach loop is used for specific objects, to traverse all the elements of an array. Using : 

```csharp
string[] planets = new string[] { "Earth", "Mars", "Jupyter", "Saturn", "Uranus", "PLuto", "Neptune" };
foreach (string planet in planets)
{
    Console.WriteLine(planet);
}
```

# Other (WriteLine, ReadLine, ReadKey, Write ...)

```csharp
Console.WriteLine(); : Write a text then wrap

Console.Write(); : Write a text

Console.ReadLine(); : Allows you to write a text

Console.ReadKey(); : Get information about a key (ideal for key conditions)

Console.Title = "title"; : Put a name on the console

using exemple : Allows you to import a library (installed via nuget)

Console.ForegroundColor = ConsoleColor.Cyan; Set a color for console text

if {}, else{} : condition

System.Threading.Thread.Sleep(1000) : wait for 1 seconde 

Console.Clear(); : clear the console

Program.Main(args); : return to the Main

try : try
catch : if exception for the try, continue


```
