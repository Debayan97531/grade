int main()
{
    int s1,s2,s3,s4,s5,per;
    printf("enter marks of 5subjects:");
    scanf("%d%d%d%d%d",&s1,&s2,&s3,&s4,&s5);
    per=(s1+s2+s3+s4+s5)/5;
    if(per>=80)
    {
        printf("grade A\n");
    }
    else
    {
        if(per>=60)
        {
        printf("grade B\n");
        }
        else
        {
            if(per>=40)
            {
                printf("grade C\n");
            }
            else
            {
                printf("faied\n");
            }
            
        }
    }
}
