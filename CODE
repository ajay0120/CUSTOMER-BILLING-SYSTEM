#include <stdio.h>
#include <string.h>
void coupon(char z[50], int sum, char name[50]) {
  int add = 0;
  char y[6] = "FRIDAY";
  for (int i = 0; i < 6; i++) {
    if (y[i] == z[i]) {
      add++;
    }
  }
  if (add == 6) {
    float discount = 0.15 * sum;
    float netTotal = sum - discount;
    float cgst = 0.03 * netTotal;
    float grandTotal = netTotal + (2 * cgst);
    printf("\t================= BVRIT CAFE CORNER =================\n\n");
    printf("NAME: %s\n", name);
    printf("---------------------------------------\n");
    printf("Sub Total\t\t\t : %d", sum);
    printf("\nDiscount @15 percent\t: %f", discount);
    printf("\n\t\t\t\t----------");
    printf("\nNet Total\t : %f", netTotal);
    printf("\nCGST @3 percent\t : %f", cgst);
    printf("\nSGST @3 percent\t : %f", cgst);
    printf("\n---------------------------------------");
    printf("\nGrand Total\t\t\t : %f", grandTotal);
    printf("\n---------------------------------------\n");
  }

  else {
    printf("The Entered coupon code is INVALID\n\n");
    float netTotal = sum;
    float cgst = 0.03 * netTotal;
    float grandTotal = netTotal + (2 * cgst);
    printf("---------------------------------------\n");
    printf("\t================= BVRIT CAFE CORNER =================\n\n");
    printf("NAME: %s\n", name);
    printf("Sub Total\t\t\t : %d", sum);
    printf("\n\t\t\t\t----------");
    printf("\nNet Total\t : %f", netTotal);
    printf("\nCGST @3 percent\t : %f", cgst);
    printf("\nSGST @3 percent\t : %f", cgst);
    printf("\n---------------------------------------");
    printf("\nGrand Total\t\t\t : %f", grandTotal);
    printf("\n---------------------------------------\n");
  }
}
struct order {
  int item;
  char size[100];
  int quant;
};
void menu() {
  FILE *fp;
  fopen("fp", "r");
  char ch;
  fp = fopen("menu.txt", "r");
  while (1) {
    ch = fgetc(fp);
    if (ch == EOF)
      break;
    printf("%c", ch);
  }
  fclose(fp);
}
int main() {
  int i = 0, opt;
  int sum = 0, key = 1;
  char b[7] = "REGULAR", c[6] = "MEDIUM", d[5] = "LARGE", e[100];
  char x[50], a[100], name[50];
  int flag = 0, R, M, L;
  struct order ord;

  printf(" * * * * * * * * * * * * * * * * * * * * * * * * * * * * * *");
  printf("\n");
  printf("\t");
  printf("\t================= BVRIT CAFE CORNER =================\n\n");
  printf("Please Select an Option: ");
  printf("\n");
  printf("\t");
  printf("* * * * * * * * * * * * * * * * * * * * * * * * * * * * * * ");
  printf("\n");
  printf("\t");
  printf("01. CUSTOMER");
  printf("\n\t");
  printf("02. EXIT");
  printf("\n");
  printf("\n\t");
  printf("Enter your option:");
  scanf("%d", &opt);
  switch (opt) {
  case 1:
    menu();
    printf("\t================= BVRIT CAFE CORNER =================\n\n");
    printf("Name of the customer:");
    scanf(" %[^\n]", name);
    while (key > 0) {
      printf("Enter your item number:- \n");
      scanf("%d", &ord.item);
      printf("Enter the size of the item i.e. (REGULAR,MEDIUM,LARGE) of the "
             "item:- \n");
      scanf("%s", a);
      // printf("%s",strupr(a));
      printf("Enter the quantity of the item:- \n");
      scanf("%d", &ord.quant);
      switch (ord.item) {
      case 1:
        R = strcmp(a, b);
        if (R == 0) {
          sum = sum + 235 * ord.quant;
        }

        M = strcmp(a, c);
        if (M == 0) {
          sum = sum + 270 * ord.quant;
        }

        L = strcmp(a, d);
        if (L == 0) {
          sum = sum + 305 * ord.quant;
        }
        break;

      case 2:
        R = strcmp(a, b);
        if (R == 0) {
          sum = sum + 185 * ord.quant;
        }

        M = strcmp(a, c);
        if (M == 0) {
          sum = sum + 210 * ord.quant;
        }

        L = strcmp(a, d);
        if (L == 0) {
          sum = sum + 235 * ord.quant;
        }
        break;

      case 3:
        R = strcmp(a, b);
        if (R == 0) {
          sum = sum + 195 * ord.quant;
        }

        M = strcmp(a, c);
        if (M == 0) {
          sum = sum + 215 * ord.quant;
        }

        L = strcmp(a, d);
        if (L == 0) {
          sum = sum + 240 * ord.quant;
        }
        break;

      case 4:
        R = strcmp(a, b);
        if (R == 0) {
          sum = sum + 300 * ord.quant;
        }

        M = strcmp(a, c);
        if (M == 0) {
          sum = sum + 330 * ord.quant;
        }

        L = strcmp(a, d);
        if (L == 0) {
          sum = sum + 395 * ord.quant;
        }
        break;

      case 5:
        R = strcmp(a, b);
        if (R == 0) {
          sum = sum + 255 * ord.quant;
        }

        M = strcmp(a, c);
        if (M == 0) {
          sum = sum + 285 * ord.quant;
        }

        L = strcmp(a, d);
        if (L == 0) {
          sum = sum + 320 * ord.quant;
        }
        break;

      case 6:
        R = strcmp(a, b);
        if (R == 0) {
          sum = sum + 335 * ord.quant;
        }

        M = strcmp(a, c);
        if (M == 0) {
          sum = sum + 375 * ord.quant;
        }

        L = strcmp(a, d);
        if (L == 0) {
          sum = sum + 420 * ord.quant;
        }
        break;

      case 7:
        R = strcmp(a, b);
        if (R == 0) {
          sum = sum + 295 * ord.quant;
        }

        M = strcmp(a, c);
        if (M == 0) {
          sum = sum + 335 * ord.quant;
        }

        L = strcmp(a, d);
        if (L == 0) {
          sum = sum + 380 * ord.quant;
        }
        break;

      case 8:
        R = strcmp(a, b);
        if (R == 0) {
          sum = sum + 320 * ord.quant;
        }

        M = strcmp(a, c);
        if (M == 0) {
          sum = sum + 350 * ord.quant;
        }

        L = strcmp(a, d);
        if (L == 0) {
          sum = sum + 385 * ord.quant;
        }
        break;

      case 9:
        R = strcmp(a, b);
        if (R == 0) {
          sum = sum + 255 * ord.quant;
        }

        M = strcmp(a, c);
        if (M == 0) {
          sum = sum + 285 * ord.quant;
        }

        L = strcmp(a, d);
        if (L == 0) {
          sum = sum + 320 * ord.quant;
        }
        break;

      case 10:
        R = strcmp(a, b);
        if (R == 0) {
          sum = sum + 295 * ord.quant;
        }

        M = strcmp(a, c);
        if (M == 0) {
          sum = sum + 335 * ord.quant;
        }

        L = strcmp(a, d);
        if (L == 0) {
          sum = sum + 400 * ord.quant;
        }
        break;

      case 11:
        R = strcmp(a, b);
        if (R == 0) {
          sum = sum + 85 * ord.quant;
        }

        M = strcmp(a, c);
        if (M == 0) {
          sum = sum + 110 * ord.quant;
        }

        L = strcmp(a, d);
        if (L == 0) {
          sum = sum + 135 * ord.quant;
        }
        break;

      case 12:
        R = strcmp(a, b);
        if (R == 0) {
          sum = sum + 120 * ord.quant;
        }

        M = strcmp(a, c);
        if (M == 0) {
          sum = sum + 155 * ord.quant;
        }

        L = strcmp(a, d);
        if (L == 0) {
          sum = sum + 185 * ord.quant;
        }
        break;

      case 13:
        R = strcmp(a, b);
        if (R == 0) {
          sum = sum + 140 * ord.quant;
        }

        M = strcmp(a, c);
        if (M == 0) {
          sum = sum + 175 * ord.quant;
        }

        L = strcmp(a, d);
        if (L == 0) {
          sum = sum + 220 * ord.quant;
        }
        break;

      case 14:
        R = strcmp(a, b);
        if (R == 0) {
          sum = sum + 210 * ord.quant;
        }

        M = strcmp(a, c);
        if (M == 0) {
          sum = sum + 245 * ord.quant;
        }

        L = strcmp(a, d);
        if (L == 0) {
          sum = sum + 290 * ord.quant;
        }
        break;

      case 15:
        R = strcmp(a, b);
        if (R == 0) {
          sum = sum + 165 * ord.quant;
        }

        M = strcmp(a, c);
        if (M == 0) {
          sum = sum + 190 * ord.quant;
        }

        L = strcmp(a, d);
        if (L == 0) {
          sum = sum + 220 * ord.quant;
        }
        break;

      default:
        printf("\nThe Item You Entered is Not Available in the Menu\n");
        break;
      }

      printf("\nDo you want to order any other item?\n");
      printf("If yes click: 1 or else click:0\n");
      scanf("%d", &key);
    }

    printf("\nENTER COUPON (IF ANY):\n");
    scanf("%s", x);
    coupon(x, sum, name);
    printf("\t\t\tHAVE A GOOD DAY.\n\n");
    printf("\t\t\tTHANK YOU! VISIT AGAIN :)\n");
    break;

  case 2:
    printf("\t\t\tHAVE A GOOD DAY.\n\n");
    printf("\t\t\tTHANK YOU! VISIT AGAIN :)\n");
  default:
    printf("\n\t\t\tINVALID OPTION");
    break;
  }
  return 0;
}
