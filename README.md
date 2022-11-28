# 13.-odev

//say�n�n karesini alan fonksiyon

#include<stdio.h>

int kareal(int);

int main(void)
{
	int sayi;
	printf("karesini almak istediginiz sayiyi giriniz.");
	scanf("%d" , &sayi);
	
	printf("sonuc: %d" , kareal(sayi));
	
	return 0;
	
}

int kareal(int x)
{
	int sonuc;
	
	sonuc=x*x;
	
	return sonuc;
}
