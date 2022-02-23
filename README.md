# Nh-p-m-t-s-nguy-n-t-b-n-ph-m-ki-m-tra-xem-l-s-ch-n-hay-l-
Nhập một số nguyên từ bàn phím, kiểm tra xem đó là số chẵn hay lẻ  
#include<stdio.h>
#include<conio.h>
main()
{    
    int x;
    printf("Nhap x:");
    scanf("%d",&x);
    if(x%2==0)
    {
        printf("%d la so chan",x);
    }
    else
    {
        printf("%d la so le",x);
    }
    getch();
}
