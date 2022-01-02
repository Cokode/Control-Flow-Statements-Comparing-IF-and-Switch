# Control-Flow-Statements-Comparing-IF-and-Switch

public class DayOfTheWeekChallenge {
    public static void printDayOfTheWeek(int day) {

        if (day < 0 || day > 6 ) {
            System.out.println("invalid day");
        } else if (day == 0) {
            System.out.println("Sunday");
        } else if (day == 1) {
            System.out.println("Monday");
        } else if (day == 2) {
            System.out.println("Tuesday");
        } else if (day == 3) {
            System.out.println("Wednesday");
        } else if (day == 4) {
            System.out.println("Thursday");
        } else if (day == 5) {
            System.out.println("Friday");
        } else {
            System.out.println("Saturday");
        }

      /*  switch (day) {    // This part was blurred so that we can use the ifThen statement. 
            case 0:
                System.out.println("Sunday");
                break;
            case 1:
                System.out.println("Monday");
                break;
            case 2:
                System.out.println("Tuesday");
                break;
            case 3:
                System.out.println("Wednesday");
                break;
            case 4:
                System.out.println("Thursday");
                break;
            case 5:
                System.out.println("Friday");
                break;
            case 6:
                System.out.println("Saturday");
                break;
            default:
                System.out.println("Invalid day");
                break;
        }  */
    }

    public static void main(String[] args) {
        printDayOfTheWeek(-7);
    }
}
