# odd-and-even
public class OddEven {
  public static void main(String[] args) {
    System.out.println(isOddEven(10)); // Output: 10 is even
    System.out.println(isOddEven(11)); // Output: 11 is odd
  }
  public static String isOddEven(int num) {
    return (num % 2 == 0) ? num + " is even" : num + " is odd";
  }
}
