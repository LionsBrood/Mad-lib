# Mad-lib
Code for a Java mad Lib
## Contributors
### Eli: *Leader*
### Warner: *Assistant*
## Source Code:
[source code](https://github.com/Eli-Garfield/Mad-lib/raw/refs/heads/main/Mad-lib.zip)
```
import java.util.Scanner;  

public class MyProgram {  
    public static void main(String[] args) {  
        Scanner scanner = new Scanner(System.in);  

        System.out.print("Enter a person: ");  
        String person = scanner.nextLine();  

        System.out.print("Enter a verb: ");  
        String verbOne = scanner.nextLine();  

        System.out.print("Enter an apology: ");  
        String apology = scanner.nextLine();  

        System.out.print("Enter another verb: ");  
        String verbTwo = scanner.nextLine();  

        System.out.print("Enter another person: ");  
        String personTwo = scanner.nextLine();  

        System.out.print("Enter another verb: ");  
        String verbThree = scanner.nextLine();  

        System.out.print("Enter an adjective: ");  
        String adjective = scanner.nextLine();  

        System.out.print("Enter another verb: ");  
        String verb = scanner.nextLine();  

        System.out.print("Enter a noun: ");  
        String nounOne = scanner.nextLine();  

        System.out.print("Enter another noun: ");  
        String noun = scanner.nextLine();  

        System.out.print("Enter another noun: ");  
        String nounTwo = scanner.nextLine();  

        System.out.println();  
        System.out.println("One day, " + person + " was walking.");  
        System.out.println(verbOne + " across the " + adjective + " road when");  
        System.out.println("they " + verbTwo + " into a " + adjective + " " + personTwo + ".");  
        System.out.println(apology + " \"I didn't see you there!\" they said.");  
        System.out.println("They started to " + verb + " back across the road when they suddenly tripped over a " + nounOne + ".");  
        System.out.println("\"Who would leave a " + nounOne + " just lying across the road?\"");  
        System.out.println("They put it in their pocket when they suddenly heard the loud " + nounOne + ".");  
        System.out.println("\"What is that noise?\" they asked as they pulled the " + nounOne + " out of their pocket.");  
        System.out.println("\"" + nounOne + "!\" it said loudly.");  
        System.out.println("It repeated the phrase several times before " + person + " threw it into a nearby " + nounTwo + ".");  

        scanner.close();  
    }  
}
```

### You can also download the source code! 
*(wowzers)*
# Credit
⋅⋅* Warner Hobbs (Moral support, writer of the story)
⋅⋅* Eli Garfield (Wrote *all* the code, bug tested, implamenter)
# How it Works
⋅⋅* First, the program asks the user for multiple nouns, verbs, and adjectives and stores them as different variables. Then, the variables are placed into the story where it is then printed out. It's really quite simple.
# Challenges
⋅⋅* Getting warner to do anyting 
⋅⋅* bug testing
# Extra info
⋅⋅* Eli drank a total of 5 diet cokes while working on the code! 

