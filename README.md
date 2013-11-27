Ortalamaya-en-yakin
===================


#include<stdio.h>
#include<stdlib.h>

void main()

{
	int say[20], i;
	float toplam=0;
	int N, a;
	float ort; 
	float fark, min;

	printf("N degeri giriniz: ");
	scanf("%d",&N);
	
    for(i=0; i<N; i++)
	{ 
		printf("%d.sayiyi giriniz: ", i+1);
		scanf("%d", &say[i]);


		toplam = toplam + say[i];
	}

	ort = (float)toplam / (float)N;
	printf("Ortalamasi :%f\n", ort);
	
	for(i=0; i<N; i++)
	{
		fark = ort - say[i];
	
	if(a < fark)
       a = min;
	
	}
	

	printf("Ortalamaya en yakin sayi: %d", a);
	
	system("pause");
}


