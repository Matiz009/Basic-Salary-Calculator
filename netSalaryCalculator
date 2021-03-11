#include <stdio.h>
int main() {
  char dec;
  int age;
  int exp;
  float rPay=0;
  printf("Enter your scale:\t");
  scanf("%c",&dec );
  if(dec=='w'||dec=='W'){
  float bPay=10000.00;
   printf("Enter your age:\t\t");
   scanf("%d",&age);
   printf("Enter your experience in Years:\t\t\t");
   scanf("%d",&exp);
   rPay=bPay+(exp*700);
   printf("\n\n---------------------------------\n");
   printf("Basic Pay\n\n");
   printf("-------\n");
   printf("Basic Salary:\t\t%f\n",bPay);
   printf("No of Increments:\t\t%d\n",exp);
    printf("Running Pay:\t\t%f\n",rPay);
    printf("\nAllowances\n\n");
    printf("--------\n");
    float hRA=rPay*0.45;
    float sSB=rPay*0.30;
    float aRA=0.0;
    printf("House Rent Allowance :\t\t%f\n",hRA );
    printf("Social Security Benifits :\t\t%f\n",sSB );
    if(age>45){
      aRA=3000;
      printf("Adhoc Relief Allowance :\t\t%f\n",aRA );
      int gPay=rPay+hRA+sSB+aRA;
      printf("Gross Pay:\t\t\t%d\n",gPay);
      printf("\n\nDeductions\n\n" );
      printf("----------\n\n" );
      int donations=gPay%100;
      int nGPay=gPay-donations;
      int annualGPay=nGPay*12;
      printf("Annual Pay : %d\n",annualGPay );
      if(annualGPay<=400000){
        float ITRate=0.0;
        float gPF=nGPay*0.1;
        float tDonations=donations+ITRate+gPF;
        float netPay=gPay-tDonations;
        printf("Income Tax:\t\t%f\n",ITRate );
        printf("General Provident Fund:\t\t%f\n",gPF );
        printf("Donations:\t\t%d\n",donations );
        printf("Total Donations:\t\t\t%f\n",tDonations );
        printf("\n\n Total Pay :\t\t\t\t%f\n",netPay );
      }else
      if(annualGPay>400000&&annualGPay<=650000){
        float ITRate=0.025*gPay;
        float gPF=nGPay*0.1;
        float tDonations=donations+ITRate+gPF;
        float netPay=gPay-tDonations;
        printf("Income Tax:\t\t%f\n",ITRate );
        printf("General Provident Fund:\t\t%f\n",gPF );
        printf("Donations:\t\t%d\n",donations );
        printf("Total Donations:\t\t\t%f\n",tDonations );
        printf("\n\n Total Pay :\t\t\t\t%f\n",netPay );
      }else
      if(annualGPay>650000&&annualGPay<=1000000){
        float ITRate=0.0475*gPay;
        float gPF=nGPay*0.1;
        float tDonations=donations+ITRate+gPF;
        float netPay=gPay-tDonations;
        printf("Income Tax:\t\t%f\n",ITRate );
        printf("General Provident Fund:\t\t%f\n",gPF );
        printf("Donations:\t\t%d\n",donations );
        printf("Total Donations:\t\t\t%f\n",tDonations );
        printf("\n\n Total Pay :\t\t\t\t%f\n",netPay );
      }else
      if(annualGPay>1000000&&annualGPay<=1500000){
        float ITRate=0.070*gPay;
        float gPF=nGPay*0.1;
        float tDonations=donations+ITRate+gPF;
        float netPay=gPay-tDonations;
        printf("Income Tax:\t\t%f\n",ITRate );
        printf("General Provident Fund:\t\t%f\n",gPF );
        printf("Donations:\t\t%d\n",donations );
        printf("Total Donations:\t\t\t%f\n",tDonations );
        printf("\n\n Total Pay :\t\t\t\t%f\n",netPay );
      }else{
        float ITRate=0.115*gPay;
        float gPF=nGPay*0.1;
        float tDonations=donations+ITRate+gPF;
        float netPay=gPay-tDonations;
        printf("Income Tax:\t\t%f\n",ITRate );
        printf("General Provident Fund:\t\t%f\n",gPF );
        printf("Donations:\t\t%d\n",donations );
        printf("Total Donations:\t\t\t%f\n",tDonations );
        printf("\n\n Total Pay :\t\t\t\t%f\n",netPay );
      }

    }else{
      aRA=1500;
      printf("Adhoc Relief Allowance :\t\t%f\n",aRA );
      int gPay=rPay+hRA+sSB+aRA;
      printf("Gross Pay:\t\t\t%d\n",gPay);
      printf("\n\nDeductions\n\n" );
      printf("----------\n\n" );
      int donations=gPay%100;
      int nGPay=gPay-donations;
      int annualGPay=nGPay*12;
      printf("Annual Pay : %d\n",annualGPay );
      if(annualGPay<=400000){
        float ITRate=0.0;
        float gPF=nGPay*0.1;
        float tDonations=donations+ITRate+gPF;
        float netPay=gPay-tDonations;
        printf("Income Tax:\t\t%f\n",ITRate );
        printf("General Provident Fund:\t\t%f\n",gPF );
        printf("Donations:\t\t%d\n",donations );
        printf("Total Donations:\t\t\t%f\n",tDonations );
        printf("\n\n Total Pay :\t\t\t\t%f\n",netPay );
      }else
      if(annualGPay>400000&&annualGPay<=650000){
        float ITRate=0.025*gPay;
        float gPF=nGPay*0.1;
        float tDonations=donations+ITRate+gPF;
        float netPay=gPay-tDonations;
        printf("Income Tax:\t\t%f\n",ITRate );
        printf("General Provident Fund:\t\t%f\n",gPF );
        printf("Donations:\t\t%d\n",donations );
        printf("Total Donations:\t\t\t%f\n",tDonations );
        printf("\n\n Total Pay :\t\t\t\t%f\n",netPay );
      }else
      if(annualGPay>650000&&annualGPay<=1000000){
        float ITRate=0.0475*gPay;
        float gPF=nGPay*0.1;
        float tDonations=donations+ITRate+gPF;
        float netPay=gPay-tDonations;
        printf("Income Tax:\t\t%f\n",ITRate );
        printf("General Provident Fund:\t\t%f\n",gPF );
        printf("Donations:\t\t%d\n",donations );
        printf("Total Donations:\t\t\t%f\n",tDonations );
        printf("\n\n Total Pay :\t\t\t\t%f\n",netPay );
      }else
      if(annualGPay>1000000&&annualGPay<=1500000){
        float ITRate=0.070*gPay;
        float gPF=nGPay*0.1;
        float tDonations=donations+ITRate+gPF;
        float netPay=gPay-tDonations;
        printf("Income Tax:\t\t%f\n",ITRate );
        printf("General Provident Fund:\t\t%f\n",gPF );
        printf("Donations:\t\t%d\n",donations );
        printf("Total Donations:\t\t\t%f\n",tDonations );
        printf("\n\n Total Pay :\t\t\t\t%f\n",netPay );
      }else{
        float ITRate=0.115*gPay;
        float gPF=nGPay*0.1;
        float tDonations=donations+ITRate+gPF;
        float netPay=gPay-tDonations;
        printf("Income Tax:\t\t%f\n",ITRate );
        printf("General Provident Fund:\t\t%f\n",gPF );
        printf("Donations:\t\t%d\n",donations );
        printf("Total Donations:\t\t\t%f\n",tDonations );
        printf("\n\n Total Pay :\t\t\t\t%f\n",netPay );
      }

    }
  }else
  if(dec=='x'||dec=='X'){
  float bPay=12900.00;
   printf("Enter your age:\t\t");
   scanf("%d",&age);
   printf("Enter your experience in Years:\t\t\t");
   scanf("%d",&exp);
   rPay=bPay+(exp*910);
   printf("\n\n---------------------------------\n");
   printf("Basic Pay\n\n");
   printf("-------\n");
   printf("Basic Salary:\t\t%f\n",bPay);
   printf("No of Increments:\t\t%d\n",exp);
   printf("Running Pay:\t\t%f\n",rPay);
   printf("\nAllowances\n\n");
   printf("--------\n");
   float hRA=rPay*0.45;
   float sSB=rPay*0.30;
   float aRA=0.0;
   printf("House Rent Allowance :\t\t%f\n",hRA );
   printf("Social Security Benifits :\t\t%f\n",sSB );
   if(age>45){
     aRA=3000;
     printf("Adhoc Relief Allowance :\t\t%f\n",aRA );
     int gPay=rPay+hRA+sSB+aRA;
     printf("Gross Pay:\t\t\t%d\n",gPay);
     printf("\n\nDeductions\n\n" );
     printf("----------\n\n" );
     int donations=gPay%100;
     int nGPay=gPay-donations;
     int annualGPay=nGPay*12;
     printf("Annual Pay : %d\n",annualGPay );
     if(annualGPay<=400000){
       float ITRate=0.0;
       float gPF=nGPay*0.1;
       float tDonations=donations+ITRate+gPF;
       float netPay=gPay-tDonations;
       printf("Income Tax:\t\t%f\n",ITRate );
       printf("General Provident Fund:\t\t%f\n",gPF );
       printf("Donations:\t\t%d\n",donations );
       printf("Total Donations:\t\t\t%f\n",tDonations );
       printf("\n\n Total Pay :\t\t\t\t%f\n",netPay );
     }else
     if(annualGPay>400000&&annualGPay<=650000){
       float ITRate=0.025*gPay;
       float gPF=nGPay*0.1;
       float tDonations=donations+ITRate+gPF;
       float netPay=gPay-tDonations;
       printf("Income Tax:\t\t%f\n",ITRate );
       printf("General Provident Fund:\t\t%f\n",gPF );
       printf("Donations:\t\t%d\n",donations );
       printf("Total Donations:\t\t\t%f\n",tDonations );
       printf("\n\n Total Pay :\t\t\t\t%f\n",netPay );
     }else
     if(annualGPay>650000&&annualGPay<=1000000){
       float ITRate=0.0475*gPay;
       float gPF=nGPay*0.1;
       float tDonations=donations+ITRate+gPF;
       float netPay=gPay-tDonations;
       printf("Income Tax:\t\t%f\n",ITRate );
       printf("General Provident Fund:\t\t%f\n",gPF );
       printf("Donations:\t\t%d\n",donations );
       printf("Total Donations:\t\t\t%f\n",tDonations );
       printf("\n\n Total Pay :\t\t\t\t%f\n",netPay );
     }else
     if(annualGPay>1000000&&annualGPay<=1500000){
       float ITRate=0.070*gPay;
       float gPF=nGPay*0.1;
       float tDonations=donations+ITRate+gPF;
       float netPay=gPay-tDonations;
       printf("Income Tax:\t\t%f\n",ITRate );
       printf("General Provident Fund:\t\t%f\n",gPF );
       printf("Donations:\t\t%d\n",donations );
       printf("Total Donations:\t\t\t%f\n",tDonations );
       printf("\n\n Total Pay :\t\t\t\t%f\n",netPay );
     }else{
       float ITRate=0.115*gPay;
       float gPF=nGPay*0.1;
       float tDonations=donations+ITRate+gPF;
       float netPay=gPay-tDonations;
       printf("Income Tax:\t\t%f\n",ITRate );
       printf("General Provident Fund:\t\t%f\n",gPF );
       printf("Donations:\t\t%d\n",donations );
       printf("Total Donations:\t\t\t%f\n",tDonations );
       printf("\n\n Total Pay :\t\t\t\t%f\n",netPay );
     }

   }else{
     aRA=1500;
     printf("Adhoc Relief Allowance :\t\t%f\n",aRA );
     int gPay=rPay+hRA+sSB+aRA;
     printf("Gross Pay:\t\t\t%d\n",gPay);
     printf("\n\nDeductions\n\n" );
     printf("----------\n\n" );
     int donations=gPay%100;
     int nGPay=gPay-donations;
     int annualGPay=nGPay*12;
     printf("Annual Pay : %d\n",annualGPay );
     if(annualGPay<=400000){
       float ITRate=0.0;
       float gPF=nGPay*0.1;
       float tDonations=donations+ITRate+gPF;
       float netPay=gPay-tDonations;
       printf("Income Tax:\t\t%f\n",ITRate );
       printf("General Provident Fund:\t\t%f\n",gPF );
       printf("Donations:\t\t%d\n",donations );
       printf("Total Donations:\t\t\t%f\n",tDonations );
       printf("\n\n Total Pay :\t\t\t\t%f\n",netPay );
     }else
     if(annualGPay>400000&&annualGPay<=650000){
       float ITRate=0.025*gPay;
       float gPF=nGPay*0.1;
       float tDonations=donations+ITRate+gPF;
       float netPay=gPay-tDonations;
       printf("Income Tax:\t\t%f\n",ITRate );
       printf("General Provident Fund:\t\t%f\n",gPF );
       printf("Donations:\t\t%d\n",donations );
       printf("Total Donations:\t\t\t%f\n",tDonations );
       printf("\n\n Total Pay :\t\t\t\t%f\n",netPay );
     }else
     if(annualGPay>650000&&annualGPay<=1000000){
       float ITRate=0.0475*gPay;
       float gPF=nGPay*0.1;
       float tDonations=donations+ITRate+gPF;
       float netPay=gPay-tDonations;
       printf("Income Tax:\t\t%f\n",ITRate );
       printf("General Provident Fund:\t\t%f\n",gPF );
       printf("Donations:\t\t%d\n",donations );
       printf("Total Donations:\t\t\t%f\n",tDonations );
       printf("\n\n Total Pay :\t\t\t\t%f\n",netPay );
     }else
     if(annualGPay>1000000&&annualGPay<=1500000){
       float ITRate=0.070*gPay;
       float gPF=nGPay*0.1;
       float tDonations=donations+ITRate+gPF;
       float netPay=gPay-tDonations;
       printf("Income Tax:\t\t%f\n",ITRate );
       printf("General Provident Fund:\t\t%f\n",gPF );
       printf("Donations:\t\t%d\n",donations );
       printf("Total Donations:\t\t\t%f\n",tDonations );
       printf("\n\n Total Pay :\t\t\t\t%f\n",netPay );
     }else{
       float ITRate=0.15*gPay;
       float gPF=nGPay*0.1;
       float tDonations=donations+ITRate+gPF;
       float netPay=gPay-tDonations;
       printf("Income Tax:\t\t%f\n",ITRate );
       printf("General Provident Fund:\t\t%f\n",gPF );
       printf("Donations:\t\t%d\n",donations );
       printf("Total Donations:\t\t\t%f\n",tDonations );
       printf("\n\n Total Pay :\t\t\t\t%f\n",netPay );
     }

   }


  }else
  if(dec=='y'||dec=='Y'){
  float bPay=21700.00;
   printf("Enter your age:\t\t");
   scanf("%d",&age);
   printf("Enter your experience in Years:\t\t\t");
   scanf("%d",&exp);
   rPay=bPay+(exp*1500);
   printf("\n\n---------------------------------\n");
   printf("Basic Pay\n\n");
   printf("-------\n");
   printf("Basic Salary:\t\t%f\n",bPay);
   printf("No of Increments:\t\t%d\n",exp);
   printf("Running Pay:\t\t%f\n",rPay);
   printf("\nAllowances\n\n");
   printf("--------\n");
   float hRA=rPay*0.45;
   float sSB=rPay*0.30;
   float aRA=1500.00;
   printf("House Rent Allowance :\t\t%f\n",hRA );
   printf("Social Security Benifits :\t\t%f\n",sSB );
   if(age>45){
     aRA=3000;
     printf("Adhoc Relief Allowance :\t\t%f\n",aRA );
     int gPay=rPay+hRA+sSB+aRA;
     printf("Gross Pay:\t\t\t%d\n",gPay);
     printf("\n\nDeductions\n\n" );
     printf("----------\n\n" );
     int donations=gPay%100;
     int nGPay=gPay-donations;
     int annualGPay=nGPay*12;
     printf("Annual Pay : %d\n",annualGPay );
     if(annualGPay<=400000){
       float ITRate=0.0;
       float gPF=nGPay*0.1;
       float tDonations=donations+ITRate+gPF;
       float netPay=gPay-tDonations;
       printf("Income Tax:\t\t%f\n",ITRate );
       printf("General Provident Fund:\t\t%f\n",gPF );
       printf("Donations:\t\t%d\n",donations );
       printf("Total Donations:\t\t\t%f\n",tDonations );
       printf("\n\n Total Pay :\t\t\t\t%f\n",netPay );
     }else
     if(annualGPay>400000&&annualGPay<=650000){
       float ITRate=0.025*gPay;
       float gPF=nGPay*0.1;
       float tDonations=donations+ITRate+gPF;
       float netPay=gPay-tDonations;
       printf("Income Tax:\t\t%f\n",ITRate );
       printf("General Provident Fund:\t\t%f\n",gPF );
       printf("Donations:\t\t%d\n",donations );
       printf("Total Donations:\t\t\t%f\n",tDonations );
       printf("\n\n Total Pay :\t\t\t\t%f\n",netPay );
     }else
     if(annualGPay>650000&&annualGPay<=1000000){
       float ITRate=0.0475*gPay;
       float gPF=nGPay*0.1;
       float tDonations=donations+ITRate+gPF;
       float netPay=gPay-tDonations;
       printf("Income Tax:\t\t%f\n",ITRate );
       printf("General Provident Fund:\t\t%f\n",gPF );
       printf("Donations:\t\t%d\n",donations );
       printf("Total Donations:\t\t\t%f\n",tDonations );
       printf("\n\n Total Pay :\t\t\t\t%f\n",netPay );
     }else
     if(annualGPay>1000000&&annualGPay<=1500000){
       float ITRate=0.070*gPay;
       float gPF=nGPay*0.1;
       float tDonations=donations+ITRate+gPF;
       float netPay=gPay-tDonations;
       printf("Income Tax:\t\t%f\n",ITRate );
       printf("General Provident Fund:\t\t%f\n",gPF );
       printf("Donations:\t\t%d\n",donations );
       printf("Total Donations:\t\t\t%f\n",tDonations );
       printf("\n\n Total Pay :\t\t\t\t%f\n",netPay );
     }else{
       float ITRate=0.115*gPay;
       float gPF=nGPay*0.1;
       float tDonations=donations+ITRate+gPF;
       float netPay=gPay-tDonations;
       printf("Income Tax:\t\t%f\n",ITRate );
       printf("General Provident Fund:\t\t%f\n",gPF );
       printf("Donations:\t\t%d\n",donations );
       printf("Total Donations:\t\t\t%f\n",tDonations );
       printf("\n\n Total Pay :\t\t\t\t%f\n",netPay );
     }

   }else{
     aRA=1500;
     printf("Adhoc Relief Allowance :\t\t%f\n",aRA );
     int gPay=rPay+hRA+sSB+aRA;
     printf("Gross Pay:\t\t\t%d\n",gPay);
     printf("\n\nDeductions\n\n" );
     printf("----------\n\n" );
     int donations=gPay%100;
     int nGPay=gPay-donations;
     int annualGPay=nGPay*12;
     printf("Annual Pay : %d\n",annualGPay );
     if(annualGPay<=400000){
       float ITRate=0.0;
       float gPF=nGPay*0.1;
       float tDonations=donations+ITRate+gPF;
       float netPay=gPay-tDonations;
       printf("Income Tax:\t\t%f\n",ITRate );
       printf("General Provident Fund:\t\t%f\n",gPF );
       printf("Donations:\t\t%d\n",donations );
       printf("Total Donations:\t\t\t%f\n",tDonations );
       printf("\n\n Total Pay :\t\t\t\t%f\n",netPay );
     }else
     if(annualGPay>400000&&annualGPay<=650000){
       float ITRate=0.025*gPay;
       float gPF=nGPay*0.1;
       float tDonations=donations+ITRate+gPF;
       float netPay=gPay-tDonations;
       printf("Income Tax:\t\t%f\n",ITRate );
       printf("General Provident Fund:\t\t%f\n",gPF );
       printf("Donations:\t\t%d\n",donations );
       printf("Total Donations:\t\t\t%f\n",tDonations );
       printf("\n\n Total Pay :\t\t\t\t%f\n",netPay );
     }else
     if(annualGPay>650000&&annualGPay<=1000000){
       float ITRate=0.0475*gPay;
       float gPF=nGPay*0.1;
       float tDonations=donations+ITRate+gPF;
       float netPay=gPay-tDonations;
       printf("Income Tax:\t\t%f\n",ITRate );
       printf("General Provident Fund:\t\t%f\n",gPF );
       printf("Donations:\t\t%d\n",donations );
       printf("Total Donations:\t\t\t%f\n",tDonations );
       printf("\n\n Total Pay :\t\t\t\t%f\n",netPay );
     }else
     if(annualGPay>1000000&&annualGPay<=1500000){
       float ITRate=0.070*gPay;
       float gPF=nGPay*0.1;
       float tDonations=donations+ITRate+gPF;
       float netPay=gPay-tDonations;
       printf("Income Tax:\t\t%f\n",ITRate );
       printf("General Provident Fund:\t\t%f\n",gPF );
       printf("Donations:\t\t%d\n",donations );
       printf("Total Donations:\t\t\t%f\n",tDonations );
       printf("\n\n Total Pay :\t\t\t\t%f\n",netPay );
     }else{
       float ITRate=0.115*gPay;
       float gPF=nGPay*0.1;
       float tDonations=donations+ITRate+gPF;
       float netPay=gPay-tDonations;
       printf("Income Tax:\t\t%f\n",ITRate );
       printf("General Provident Fund:\t\t%f\n",gPF );
       printf("Donations:\t\t%d\n",donations );
       printf("Total Donations:\t\t\t%f\n",tDonations );
       printf("\n\n Total Pay :\t\t\t\t%f\n",netPay );
     }

   }
  }else
  if(dec=='z'||dec=='Z'){
  float bPay=32600.00;
   printf("Enter your age:\t\t");
   scanf("%d",&age);
   printf("Enter your experience in Years:\t\t\t");
   scanf("%d",&exp);
   rPay=bPay+(exp*2800);
   printf("\n\n---------------------------------\n");
   printf("Basic Pay\n\n");
   printf("-------\n");
   printf("Basic Salary:\t\t%f\n",bPay);
   printf("No of Increments:\t\t%d\n",exp);
   printf("Running Pay:\t\t%f\n",rPay);
   printf("\nAllowances\n\n");
   printf("--------\n");
   float hRA=rPay*0.45;
   float sSB=rPay*0.30;
   float aRA=1500.00;
   printf("House Rent Allowance :\t\t%f\n",hRA );
   printf("Social Security Benifits :\t\t%f\n",sSB );
   if(age>45){
     aRA=3000;
     printf("Adhoc Relief Allowance :\t\t%f\n",aRA );
     int gPay=rPay+hRA+sSB+aRA;
     printf("Gross Pay:\t\t\t%d\n",gPay);
     printf("\n\nDeductions\n\n" );
     printf("----------\n\n" );
     int donations=gPay%100;
     int nGPay=gPay-donations;
     int annualGPay=nGPay*12;
     printf("Annual Pay : %d\n",annualGPay );
     if(annualGPay<=400000){
       float ITRate=0.0;
       float gPF=nGPay*0.1;
       float tDonations=donations+ITRate+gPF;
       float netPay=gPay-tDonations;
       printf("Income Tax:\t\t%f\n",ITRate );
       printf("General Provident Fund:\t\t%f\n",gPF );
       printf("Donations:\t\t%d\n",donations );
       printf("Total Donations:\t\t\t%f\n",tDonations );
       printf("\n\n Total Pay :\t\t\t\t%f\n",netPay );
     }else
     if(annualGPay>400000&&annualGPay<=650000){
       float ITRate=0.025*gPay;
       float gPF=nGPay*0.1;
       float tDonations=donations+ITRate+gPF;
       float netPay=gPay-tDonations;
       printf("Income Tax:\t\t%f\n",ITRate );
       printf("General Provident Fund:\t\t%f\n",gPF );
       printf("Donations:\t\t%d\n",donations );
       printf("Total Donations:\t\t\t%f\n",tDonations );
       printf("\n\n Total Pay :\t\t\t\t%f\n",netPay );
     }else
     if(annualGPay>650000&&annualGPay<=1000000){
       float ITRate=0.0475*gPay;
       float gPF=nGPay*0.1;
       float tDonations=donations+ITRate+gPF;
       float netPay=gPay-tDonations;
       printf("Income Tax:\t\t%f\n",ITRate );
       printf("General Provident Fund:\t\t%f\n",gPF );
       printf("Donations:\t\t%d\n",donations );
       printf("Total Donations:\t\t\t%f\n",tDonations );
       printf("\n\n Total Pay :\t\t\t\t%f\n",netPay );
     }else
     if(annualGPay>1000000&&annualGPay<=1500000){
       float ITRate=0.070*gPay;
       float gPF=nGPay*0.1;
       float tDonations=donations+ITRate+gPF;
       float netPay=gPay-tDonations;
       printf("Income Tax:\t\t%f\n",ITRate );
       printf("General Provident Fund:\t\t%f\n",gPF );
       printf("Donations:\t\t%d\n",donations );
       printf("Total Donations:\t\t\t%f\n",tDonations );
       printf("\n\n Total Pay :\t\t\t\t%f\n",netPay );
     }else{
       float ITRate=0.115*gPay;
       float gPF=nGPay*0.1;
       float tDonations=donations+ITRate+gPF;
       float netPay=gPay-tDonations;
       printf("Income Tax:\t\t%f\n",ITRate );
       printf("General Provident Fund:\t\t%f\n",gPF );
       printf("Donations:\t\t%d\n",donations );
       printf("Total Donations:\t\t\t%f\n",tDonations );
       printf("\n\n Total Pay :\t\t\t\t%f\n",netPay );
     }

   }else{
     aRA=1500;
     printf("Adhoc Relief Allowance :\t\t%f\n",aRA );
     int gPay=rPay+hRA+sSB+aRA;
     printf("Gross Pay:\t\t\t%d\n",gPay);
     printf("\n\nDeductions\n\n" );
     printf("----------\n\n" );
     int donations=gPay%100;
     int nGPay=gPay-donations;
     int annualGPay=nGPay*12;
     printf("Annual Pay : %d\n",annualGPay );
     if(annualGPay<=400000){
       float ITRate=0.0;
       float gPF=nGPay*0.1;
       float tDonations=donations+ITRate+gPF;
       float netPay=gPay-tDonations;
       printf("Income Tax:\t\t%f\n",ITRate );
       printf("General Provident Fund:\t\t%f\n",gPF );
       printf("Donations:\t\t%d\n",donations );
       printf("Total Donations:\t\t\t%f\n",tDonations );
       printf("\n\n Total Pay :\t\t\t\t%f\n",netPay );
     }else
     if(annualGPay>400000&&annualGPay<=650000){
       float ITRate=0.025*gPay;
       float gPF=nGPay*0.1;
       float tDonations=donations+ITRate+gPF;
       float netPay=gPay-tDonations;
       printf("Income Tax:\t\t%f\n",ITRate );
       printf("General Provident Fund:\t\t%f\n",gPF );
       printf("Donations:\t\t%d\n",donations );
       printf("Total Donations:\t\t\t%f\n",tDonations );
       printf("\n\n Total Pay :\t\t\t\t%f\n",netPay );
     }else
     if(annualGPay>650000&&annualGPay<=1000000){
       float ITRate=0.0475*gPay;
       float gPF=nGPay*0.1;
       float tDonations=donations+ITRate+gPF;
       float netPay=gPay-tDonations;
       printf("Income Tax:\t\t%f\n",ITRate );
       printf("General Provident Fund:\t\t%f\n",gPF );
       printf("Donations:\t\t%d\n",donations );
       printf("Total Donations:\t\t\t%f\n",tDonations );
       printf("\n\n Total Pay :\t\t\t\t%f\n",netPay );
     }else
     if(annualGPay>1000000&&annualGPay<=1500000){
       float ITRate=0.070*gPay;
       float gPF=nGPay*0.1;
       float tDonations=donations+ITRate+gPF;
       float netPay=gPay-tDonations;
       printf("Income Tax:\t\t%f\n",ITRate );
       printf("General Provident Fund:\t\t%f\n",gPF );
       printf("Donations:\t\t%d\n",donations );
       printf("Total Donations:\t\t\t%f\n",tDonations );
       printf("\n\n Total Pay :\t\t\t\t%f\n",netPay );
     }else{
       float ITRate=0.115*gPay;
       float gPF=nGPay*0.1;
       float tDonations=donations+ITRate+gPF;
       float netPay=gPay-tDonations;
       printf("Income Tax:\t\t%f\n",ITRate );
       printf("General Provident Fund:\t\t%f\n",gPF );
       printf("Donations:\t\t%d\n",donations );
       printf("Total Donations:\t\t\t%f\n",tDonations );
       printf("\n\n Total Pay :\t\t\t\t%f\n",netPay );
     }

   }

  }else{
    printf("Invalid input\n");
  }



  return 0;
}
