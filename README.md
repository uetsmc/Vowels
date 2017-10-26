# Vowels
CodeWars Vowels Solution

public class Vowels {

  public static int getCount(String str) {
    int vowelsCount = 0;
    char[] vowelsOut = str.toCharArray();
    for(int i = 0; i < vowelsOut.length; i++){
    if (vowelsOut[i] == 'a' || vowelsOut[i] == 'e'
    || vowelsOut[i] == 'i' || vowelsOut[i] == 'o' || vowelsOut[i] == 'u')
    {
    vowelsCount++;
    }
    
    }
    return vowelsCount;
  }
}
