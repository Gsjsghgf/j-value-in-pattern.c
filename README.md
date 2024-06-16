 #include<stdio.h>
int main()
{
    int n;
    printf("enter n value");
    scanf("%d",&n);
    for(int i=1;i<=n;i++)//row
    
    

    {
        for(int j=1;j<=n-i+1;j++)
        {
        printf("%d",n-i+1);
    }
    printf("\n");
    }
}
