int main()

{
    
 char letra;
 printf("digite uma letra: ");
 scanf("%d" , &letra);
 
 switch (letra) {
 case 'a':
 case 'e':
 case 'i':
 case 'o':
 case 'u':
 printf("vogal\n");
 break;
 default:
 printf("consoante\n");
 }
 return 0;
 }

