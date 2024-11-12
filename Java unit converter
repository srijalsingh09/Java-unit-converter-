import java.util.Scanner;

public class UnitConverter {
    
    // Method to convert meters to kilometers
    public static double metersToKilometers(double meters) {
        return meters / 1000;
    }
    
    // Method to convert kilometers to meters
    public static double kilometersToMeters(double kilometers) {
        return kilometers * 1000;
    }
    
    // Method to convert grams to kilograms
    public static double gramsToKilograms(double grams) {
        return grams / 1000;
    }
    
    // Method to convert kilograms to grams
    public static double kilogramsToGrams(double kilograms) {
        return kilograms * 1000;
    }
    
    // Method to convert Celsius to Fahrenheit
    public static double celsiusToFahrenheit(double celsius) {
        return (celsius * 9/5) + 32;
    }
    
    // Method to convert Fahrenheit to Celsius
    public static double fahrenheitToCelsius(double fahrenheit) {
        return (fahrenheit - 32) * 5/9;
    }

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.println("Welcome to the Unit Converter!");
        System.out.println("Choose a conversion option:");
        System.out.println("1. Meters to Kilometers");
        System.out.println("2. Kilometers to Meters");
        System.out.println("3. Grams to Kilograms");
        System.out.println("4. Kilograms to Grams");
        System.out.println("5. Celsius to Fahrenheit");
        System.out.println("6. Fahrenheit to Celsius");
        System.out.print("Enter your choice (1-6): ");
        
        int choice = scanner.nextInt();
        double input, result;

        switch (choice) {
            case 1:
                System.out.print("Enter meters: ");
                input = scanner.nextDouble();
                result = metersToKilometers(input);
                System.out.println(input + " meters = " + result + " kilometers");
                break;
            case 2:
                System.out.print("Enter kilometers: ");
                input = scanner.nextDouble();
                result = kilometersToMeters(input);
                System.out.println(input + " kilometers = " + result + " meters");
                break;
            case 3:
                System.out.print("Enter grams: ");
                input = scanner.nextDouble();
                result = gramsToKilograms(input);
                System.out.println(input + " grams = " + result + " kilograms");
                break;
            case 4:
                System.out.print("Enter kilograms: ");
                input = scanner.nextDouble();
                result = kilogramsToGrams(input);
                System.out.println(input + " kilograms = " + result + " grams");
                break;
            case 5:
                System.out.print("Enter Celsius: ");
                input = scanner.nextDouble();
                result = celsiusToFahrenheit(input);
                System.out.println(input + " Celsius = " + result + " Fahrenheit");
                break;
            case 6:
                System.out.print("Enter Fahrenheit: ");
                input = scanner.nextDouble();
                result = fahrenheitToCelsius(input);
                System.out.println(input + " Fahrenheit = " + result + " Celsius");
                break;
            default:
                System.out.println("Invalid choice!");
                break;
        }

        scanner.close();
    }
}# Java-unit-converter-
