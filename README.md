# Repo-42
Convert character uppercase to lowercase
//Covert character lower to upper & vice-version
import java.util.Scanner;
class Covert{
    public static void main(String[] args) {
    char ch,ch2;
    System.out.println("Enter any character");
    Scanner r = new Scanner(System.in);
    ch = r.next().charAt(0);
    
    if (ch >='A' && ch <='z')
    {
       ch2=Character.toLowerCase(ch);
       System.out.println("LowerCase: "+ ch2);
    }
    else 
    {
       ch2=Character.toUpperCase(ch);
       System.out.println("UpperCase: "+ ch2);
    }
     }
       }
