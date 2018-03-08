# Restaurant-Bill

package restaurantbill;

public class RestaurantBill {

    public static void main(String[] args) {
        double mealPrice = 58.70;
        double taxes = 7.63;
        double mealTotal = 0.0;
        mealTotal = mealPrice+taxes;
        System.out.println("Restaurant Bill");
        System.out.println("****************************");
        System.out.println("Meal Price = " + mealPrice + "$");
        System.out.println("HST = " + taxes + "$");
        System.out.println("Total = " + mealTotal + "$");
    }
    
}
