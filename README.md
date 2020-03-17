#include<stdio.h>

int main() {
	int days,year,weeks,months;
	
	printf("Enter days = ");
	scanf("%d",&days);
	
	year=days/365;
	weeks=(days % 365)/7;
	days= days - ((year * 365) + (weeks *7));
	
	printf("year=%d \n",year);
	printf("weeks=%d \n",weeks);
	printf("days=%d",days);
	
	return 0;
}
