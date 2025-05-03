this is the answer for the next labs.
	•	
import java.util.*;
public class MyProgram
{
    public static void main(String[] args)
    {
        ArrayList<String> color = new ArrayList<String>();
        color.add("Red");
        color.add("Green");
        color.add("Orange");
        color.add("White");
        color.add("Black");
        
        System.out.println(color);
    }
}

	•	
import java.util.ArrayList;
public class MyProgram
{
    public static void main(String[] args)
    {
        ArrayList<String> color = new ArrayList<String>();
        color.add("Red");
        color.add("Green");
        color.add("Orange");
        color.add("White");
        color.add("Black");
        
        for (int i = 0; i < color.size(); i++){
            System.out.println(color.get(i));
        }
    }
}


3)
import java.util.ArrayList;
public class MyProgram
{
    public static void main(String[] args)
    {
        ArrayList<String> string = new ArrayList<String>();
        ArrayList<Integer> number = new ArrayList<Integer>();
        ArrayList<String> str = new ArrayList<String>();
        string.add("A");
        string.add("B");
        string.add("C");
        string.add("D");
        number.add(1);
        number.add(2);
        number.add(3);
        number.add(4);
        System.out.print("List1: ");
        System.out.println(string);
        System.out.print("List2: ");
        System.out.println(number);
        System.out.println("Copy List1 to List2,");
        System.out.println("After copy:");
        
        number.clear();
        String x = "A";
        for (int i = 0; i < string.size(); i++){
            x = string.get(i);
            str.add(x);
        }
        System.out.print("List1: ");
        System.out.println(string);
        System.out.print("List2: ");
        System.out.println(str);
    }
}




4)
import java.util.*;
public class MyProgram
{
    public static void main(String[] args)
    {
        ArrayList<String> string = new ArrayList<String>();
        string.add("Red");
        string.add("Green");
        string.add("Orange");
        string.add("White");
        string.add("Black");
        System.out.println(string);
        System.out.println("After removing third element from the list: ");
        string.remove(2);
        System.out.println(string);
    }
} 

5) 
import java.util.ArrayList;
 
public class MyProgram {
    public static void main(String[] args) {
        ArrayList<String> str1 = new ArrayList<String>();
        ArrayList<String> str2 = new ArrayList<String>();
        
        str1.add("Red");
        str1.add("Green");
        str1.add("Black");
        str1.add("White");
        str1.add("Pink");
        
        str2.add("Red");
        str2.add("Green");
        str2.add("Black");
        str2.add("Pink");
        
        for (String s : str1) {
            if (str2.contains(s)) {
                System.out.println(s + " - Yes");
            } else {
                System.out.println(s + " - No");
            }
        }
    }
}

6)
import java.util.*;
public class MyProgram
{
    public static void main(String[] args)
    {
        ArrayList<String> str = new ArrayList<String>();
        str.add("Red");
        str.add("Green");
        str.add("Orange");
        str.add("White");
        str.add("Black");
        
        System.out.println("Before swap: " + str);
        
        String a = str.get(1);
        str.set(1,str.get(3));
        str.set(3, a);
        
        System.out.println("After swap: " + str);
        
        
        
    }
}

answers for the CSA labs
