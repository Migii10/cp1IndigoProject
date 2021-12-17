#include <stdio.h>

int main(void) {
	int choice, quantity, i;
	float payment, x, y;

    printf("Menu:\n");
	printf("1. Yumbuger w/ Fries and Drink (₱87.00)\n");
	printf("2. Cheesy Yumburger w/ Fries and Drink (₱99.00)\n");
	printf("3. Bacon Cheesy Yumburger Meal w/ Fries and Drinks (₱109.00)\n");
	printf("4. 1pc Chickenjoy w/ Drink (₱99.00)\n");
	printf("5. Jolly Spaghetti (₱55.00)\n");
	printf("6. 1pc Burger Steak w/ Drink (₱65.00)\n");
	printf("7. Exit\n");

	choice = 0;
	payment = 0;

	printf("\n");
	do{
		choice = 0;
		while (choice < 1 || choice > 7){
			printf("What choice would you like to order? ");
			scanf(" %f", &x);

			choice = (int) x;
		}
		if (choice==7){
			printf("\nTotal Payment = ₱%0.2f", payment);
			return 0;
		}
		printf("Quantity? ");
		scanf(" %f", &y);

		quantity = (int) y;

		for(i = 0; i < quantity; i++){
			if (choice==1) payment = payment + 87;
			else if (choice==2) payment = payment + 99;
			else if (choice==3) payment = payment + 109;
			else if (choice==4) payment = payment + 99;
			else if (choice==5) payment = payment + 55;
			else if (choice==6) payment = payment + 65;
	}
	}	while(choice != 7);
	
    return 0;
}
