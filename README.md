# 25.04.22
Convert number to reversed array of digits
On 1-st 
public class Kata {
  public static int[] digitize(long n) {
        return new StringBuilder().append(n)
                                  .reverse()
                                  .chars()
                                  .map(Character::getNumericValue)
                                  .toArray();
  }
}
