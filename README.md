Programa David incompleto
==========
/*Base de programa para David*/
#include <stdio.h>
#include <stdlib.h>
main()
{
    char nombre[60],objeto[20];
    int cst,OPCION,art,OPCION2,con,con1;
    float pr1=8.50,pr2=2.50,pr3=2.00,pr4=1.50,pr5=1.00;
    printf("Introduce el nombre del cliente: ");
    fflush(stdin);
    gets(nombre);
    printf("Esta es la lista de articulos:\n");
    printf("1.-Libreta\n");
    printf("2.-Pluma\n");
    printf("3.-Lapiz\n");
    printf("4.-Borrador\n");
    printf("5.-Sacapunta\n");
    printf("Presiona el numero correspondiente al articulo para agregarlo\n");
    printf("Dame el numero del primer articulo: ");
    scanf("%d", &art);
    con++;
    printf(" \n");
    if(art>5)
    {
        do
        {
            printf("El articulo selecionado no existe porfavor verifica e intente de nuevo:\n");
            printf("Dame el numero del primer articulo: ");
    scanf("%d", &art);
    printf(" \n");
        }while(art>5);
    }
    printf("¿Desea otro articulo?, Presiona 1 para continuar: ");
    scanf("%d",&OPCION);
    if(OPCION=1)
    do
    {
        printf("Dame el numero del siguiente articulo: ");
        scanf("%d", &art);
        con++;
    printf("¿Desea otro articulo?, Presiona 1 para continuar y cualquier otra tecla para terminar: ");
    scanf("%d",&OPCION);
    }while(OPCION=1);
    if(con=10)
    {
        
    }
    





}
