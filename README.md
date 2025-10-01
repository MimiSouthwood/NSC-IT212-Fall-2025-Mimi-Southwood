/*# NSC IT212-Fall 2025-Mimi Southwood

Week 1 - Switch - Convert GPA to Percentage Range*/





import java.util.Scanner;

   public class Main {
    
       public static void main(String[] args) {

            Scanner input = new Scanner(System.in);
        
            System.out.print("Enter a grade point, such as 4.0, 3.9, etc.: ");
        
            String gradepointInput = input.next();
                
                switch (gradepointInput) {
                    case "4.0":
                        System.out.println("100% to 95.0%");
                        break;
                    case "3.9":
                        System.out.println("95.0% to 94.0%");
                        break;
                    case "3.8":
                        System.out.println("94.0% to 93.0%");
                        break;
                    case "3.7":
                        System.out.println("93.0% to 92.0%");
                        break;
                    case "3.6":
                        System.out.println("92.0% to 91.0%");
                        break;
                    case "3.5":
                        System.out.println("91.0% to 90.0%");
                        break;
                    case "3.4":
                        System.out.println("90.0% to 89.0%");
                        break;
                    case "3.3":
                        System.out.println("89.0% to 88.0%");
                        break;
                    case "3.2":
                        System.out.println("88.0% to 87.0%");
                        break;
                    case "3.1":
                        System.out.println("87.0% to 86.0%");
                        break;
                    case "3.0":
                        System.out.println("86.0% to 85.0%");
                        break;
                    case "2.9":
                        System.out.println("85.0% to 84.0%");
                        break;
                    case "2.8":
                        System.out.println("84.0% to 83.0%");
                        break;
                    case "2.7":
                        System.out.println("83.0% to 82.0%");
                        break;
                    case "2.6":
                        System.out.println("82.0% to 81.0%");
                        break;
                    case "2.5":
                        System.out.println("81.0% to 80.0%");
                        break;
                    case "2.4":
                        System.out.println("80.0% to 79.0%");
                        break;
                    case "2.3":
                        System.out.println("79.0% to 78.0%");
                        break;
                    case "2.2":
                        System.out.println("78.0% to 77.0%");
                        break;
                    case "2.1":
                        System.out.println("77.0% to 76.0%");
                        break;
                    case "2.0":
                        System.out.println("76.0% to 75.0%");
                        break;
                    case "1.9":
                        System.out.println("75.0% to 74.0%");
                        break;
                    case "1.8":
                        System.out.println("74.0% to 73.0%");
                        break;
                    case "1.7":
                        System.out.println("73.0% to 72.0%");
                        break;
                    case "1.6":
                        System.out.println("72.0% to 71.0%");
                        break;
                    case "1.5":
                        System.out.println("71.0% to 70.0%");
                        break;
                    case "1.4":
                        System.out.println("70.0% to 69.0%");
                        break;
                    case "1.3":
                        System.out.println("69.0% to 68.0%");
                        break;
                    case "1.2":
                        System.out.println("68.0% to 67.0%");
                        break;
                    case "1.1":
                        System.out.println("67.0% to 66.0%");
                        break;
                    case "1.0":
                        System.out.println("66.0% to 65.0%");
                        break;
                    case "0.0":
                        System.out.println("65.0% to 0.0%");
                        break;
                    default:
                        System.out.println("The number you entered is not valid. Please try again.");
                        break; 
                }
            input.close();   
        }
    }
