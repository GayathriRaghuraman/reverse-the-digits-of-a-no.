# reverse-the-digits-of-a-no.
int reverse(int num)
{
int rev=0;
while(num>0)
{
rev=rev*10+num%10;
num=num/10;
}
return rev;
}
void main()
{
int numo;
scanf("%d",&numo);
printf(reverse(numo);
}
