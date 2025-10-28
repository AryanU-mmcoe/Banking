#include <stdio.h>
 struct customer{
     char name[50], address[50];
     int cus_id;
     long long aadhar, mobile_no, balance;
 
 };
 
void sort(struct customer bal[], int n) {
    int i, j;
    struct customer temp;
    for (i = 0; i < n - 1; i++) {
        for (j = 0; j < n - i - 1; j++) {
            if (bal[j].balance < bal[j+1].balance) {
                temp = bal[j];
                bal[j] = bal[j+1];
                bal[j+1] = temp;
            }
        }
    }
}
 
int main() {
 struct customer cus[5];
 int i;
 for (i=0;i<5;i++){
     printf("\nEnter your name: ");
     scanf("%s", cus[i].name);
     
     printf("\nEnter your address: ");
     scanf("%s", cus[i].address);
     
     printf("\nEnter your Customer id: ");
     scanf("%d", &cus[i].cus_id);
     
     printf("\nEnter your Mobile Number: ");
     scanf("%lld", &cus[i].mobile_no);
     
     printf("\nEnter your Aadhar: ");
     scanf("%lld", &cus[i].aadhar);
     
     printf("\nEnter your Account Balance: ");
     scanf("%lld", &cus[i].balance);
 }
 
 sort(cus, 5);
 
  for (i=0;i<5;i++){
     printf("\nACCOUNT DETAILS FOR CUSTOMER ID : %d", cus[i].cus_id);
     
     printf("\nName: %s", cus[i].name);
     
     printf("\nAddress: %s", cus[i].address);
   
     printf("\nMobile Number: %lld", cus[i].mobile_no);
   
     printf("\nAadhar: %lld", cus[i].aadhar);
  
     printf("\nAccount Balance: %lld", cus[i].balance);
   
 }
 
    return 0;
}
