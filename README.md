#include <stdio.h>

int main() {
    // Declare variables for prices
    float rice_price = 20.0, sugar_price = 5.0, oil_price = 15.0;
    float total_before_tax, tax, total_after_tax;

    // Calculate total price before tax
    total_before_tax = rice_price + sugar_price + oil_price;

    // Calculate tax (5%)
    tax = total_before_tax * 0.05;

    // Calculate total price after tax
    total_after_tax = total_before_tax + tax;

    // Print the result
    printf("Total cost before tax: $%.2f\n", total_before_tax);
    printf("Tax (5%%): $%.2f\n", tax);
    printf("Total cost after tax: $%.2f\n", total_after_tax);

    return 0;
}
