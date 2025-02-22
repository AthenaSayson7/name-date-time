import java.time.LocalDateTime;  
import java.time.format.DateTimeFormatter;  

public class MyInfo {
    public static void main(String[] args) {
        // Print full name
        System.out.println("Full Name: Athena Louise A. Sayson"); // Replace with your actual name

        // Hardcoded Date and Time: February 22, 2025, at 4:22 PM
        LocalDateTime fixedDateTime = LocalDateTime.of(2025, 2, 22, 16, 22);

        // Format the date and time as MM/dd/yyyy and 12-hour format
        DateTimeFormatter formatter = DateTimeFormatter.ofPattern("MM-dd-yyyy hh:mm:ss a");

        // Print the formatted date and time
        System.out.println("Current Date and Time: " + fixedDateTime.format(formatter));
    }
}
