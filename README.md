# maas-zam-hesabi


int main() {
	
//Aylık 2500 TL maaş  kişinin maşına yüzde 12zam yapılırsa 
//yeni maaşı ne kadar olur 

printf("**** ZAM MAAS HESABI ****\n");
printf("\n\n\n");

float maas,yenimaas;
printf("Maasinizi Girin lütfen: ");
scanf("%f",&maas);
yenimaas=maas+maas*19/100;
printf("Yeni Maasiniz: %f",yenimaas);


	return 0;
}
