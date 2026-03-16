//To enter yuour name using string 
#include<stdio.h>
int main()
{
char name[20];
printf("Enter your name: ");
scanf("%s",name);
printf("Your name is %s",name);
return 0;
}

//To fidn the length of the string
#include<stdio.h>
#include<string.h>
int main()
{
char str[50]="PUTTURMOHITHKUMARREDDY";
int len=strlen(str);
printf("Length of the string:%d",len);
return 0;
}

//To find the lowercase,uppercase and string reverse
#include<stdio.h>
#include<string.h>
int main()
{
char str[50]="PUTTURMOHITHKUMARREDDY";
char str1[50]="putturmohithkumarreddy";
char str2[50]="PUTTURMOHITHKUMARREDDY";
strlwr(str);
strupr(str1);
strrev(str2);
printf("In uppercase:%s\n",str);
printf("In lowercase:%s\n",str1);
printf("In reverse:%s",str2);
return 0;
}

//To compare two strings
#include<stdio.h>
#include<string.h>
int main()
{
char s1[20]="YOSHINA";
char s2[20]="YAVANIKA";
if(strcmp(s1,s2)==0){
printf("s1 and s2 are equal");
}
else{
printf("s1 and s2 are not equal");
}
return 0;
}

//To concatenation a string
#include<stdio.h>
int main()
{
char s1[50]="PUTTURMOHITH";
char s2[30]="KUMARREDDY";
strcat(s1,s2);
printf("After concatenation:%s",s1);
return 0;
}

//To copy a string into another
#include<stdio.h>
int main()
{
char s1[30]="PUTTURMOHITH";
char s2[30]="KUMARREDDY";
strcpy(s1,s2);
printf("Output string copy:%s",s1);
return 0;
}

//To find the string lenght without using string ffunction
#include<stdio.h>
int main()
{
char str[30]="PUTTURMOHITHKUMARREDDY";
//gets [str]
int i=0,len=0;
while (str[i]!='\0'){
len++;
i++;
}
printf("Length of the string:%d",str);
return 0;
}

//To count the no of words in the given statement
#include<stdio.h>
#include<string.h>
int main()
{
char [50]="PUTTUR MOHITH KUMAR REDDY";
int i; count=1;
for (i=0;str[i]!='\0';i++){
if(str[i]==' '){
count++;
}
}
printf("No.of words:%d",count);
return 0;
}

//To concatenate without using string function
#include<stdio.h>
int main()
{
char str1[20]="PUTTURMOHITH";
char str2[20]="KUMARREDDY";
int i=0,j=0;
while(str1[i]!='\0'){
i++;}
str1[i]=str2[j];
while (str2[j]!='\0'){
i++;
j++;
}
str1[i]='\0';
printf("Concatenated string=%s",str1);
return 0;
}

//To convert to uppercase without using str function
#include<stdio.h>
int main()
{
char str[20]="putturmohithkumarreddy"
int i=0;
while(str[i]!='\0'){
if (str[i]>='a'&&str[i]<='z'){
str[i]=str[i]-32;
}
i++;
}
printf(str);
return 0;
}

//to convert into lower case letters without uing the the string fuctions
#include<stdio.h>
int main()
{
int i=0;
char str[20]="PUTTURMOHITHKUMARREDDY";
int i=0;
while (str[i]>='A'&&str[i]<='Z'){
str[i]=str[i]+32;
}
i++;
printf(str);
return 0;
}
