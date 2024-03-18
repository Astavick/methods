//import
import java.util.Scanner;
public class AreaOfTriangle{

    public static double computeArea(double height, double base) {
        // Calculate and return the area
        return 0.5*height * base;
      }
    
      public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
    
        // Get dimensions from the user
        System.out.print("Enter the height of the traingle: ");
        double height = scanner.nextDouble();
        System.out.print("Enter the base of the triangle: ");
        double base = scanner.nextDouble();
    
        // Call the method to calculate the area
        double area = computeArea(height, base);
    
        // Print the calculated area
        System.out.println("The area of the triangle: " + area);
      }
}
