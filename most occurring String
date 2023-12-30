public class maxRepeat
/**
 * This file includes a method which finds most repating String in an array
 * @author Melike Kara
 */
{
    public static void main(String[] args) 
    {
        String names [] = {"Tarcin", "Melike", "Alperen", "Emiralp", "Tarcin", "Tarcin", 
        "Alperen", "Emiralp", "Melike", "Melike", "Tarcın", "Tarcın"};
        System.out.println("This is the most repeating String in the list: " + maxRepatingString(names));
    }
    
    public static String maxRepatingString(String[] names)
    {
        int occuranceNum = 0;
        int indexOfMost = 0;

        for (int i = 0; i < names.length; i++) {
            int count = 0; 
            for (int j = 0; j < names.length; j++) {
                if(names[i].equals(names[j])){
                    count ++;
                }
            }
            if(count>occuranceNum)
            {
                occuranceNum = count;
                indexOfMost = i;
            }
        }
        return names[indexOfMost];
    }
}
