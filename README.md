# Decoder-by.c
Developer by Ayush kumar decoder coding by C

//Developed by Ayush kumar
//8 May 2020
/*Take a text that includes some random
symbols and translate it into a text that
has none of them. The resulting text should
only include letters and numbers.*/


// please upvote this


//eg: M-a&₹n₹+s#+oo#+_r;    &p:;₹as+₹+_-ha&*+


#include <stdio.h>
#include<string.h>
int main() {
char s[100];
gets(s);
int i, len=strlen(s);
for(i=0;i<len;i++){
if(s[i]>64 && s[i]<91 || s[i]>96 && s[i]<123 || s[i]>47 && s[i]<58){
printf("%c",s[i]);
}
if(s[i]==32)
printf("%c",s[i]);
}

    return 0;
}

