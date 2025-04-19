# odd-and-even
public class OddEven {
  public static void checkOddEven(int num) {
    if (num % 2 == 0) {
      System.out.println(num + " is even");
    } else {
      System.out.println(num + " is odd");
    }
  }
  public static void main(String[] args) {
    checkOddEven(10); // Output: 10 is even
    checkOddEven(11); // Output: 11 is odd
  }
}
