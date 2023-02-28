#include<stdio.h>
#include<conio.h>
struct HonSo{
	int soNguyen,tuSo,mauSo;
};

typedef struct HonSo HONSO;

void nhapHonSo(HONSO &);
void xuatHonSo(HONSO);


void nhapHonSo(HONSO &hs){
	printf("Nhap so nguyen : ");
	scanf("%d",&hs.soNguyen);
	do{
		printf("Nhap tu so : ");
		scanf("%d",&hs.tuSo);
		printf("Nhap mau so  :");
		scanf("%d",&hs.mauSo);
		if(hs.mauSo==0)
			printf("\Nhap mau so khac 0 !  : \n");
		if(hs.mauSo <= hs.tuSo)
			printf("\nNhap mau so lon hon tu so\n ");
	}while(hs.mauSo==0 || hs.mauSo <= hs.tuSo );
}

void xuatHonSo(HONSO hs){
	printf("%d(%d/%d)",hs.soNguyen,hs.tuSo,hs.mauSo);
}

int main(){
	HONSO hs;
	nhapHonSo(hs);
	xuatHonSo(hs);
	getch();
	return 0;
}
