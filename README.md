
#include <stdio.h>

int main() {
    // Declare variables
    int initial_balance = 50000;
    int withdraw_amount = 20000;
    int final_balance;

    // Check if withdrawal is possible
    if (withdraw_amount > initial_balance) {
        printf("Insufficient balance!\n");
    } else {
        // Perform withdrawal
        final_balance = initial_balance - withdraw_amount;

        // Display the balance details
        printf("Initial Balance: %d\n", initial_balance);
        printf("Withdraw Amount: %d\n", withdraw_amount);
        printf("Remaining Balance: %d\n", final_balance);
    }

    return 0;
}
   
        
