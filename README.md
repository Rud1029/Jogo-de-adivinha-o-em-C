# Jogo-de-adivinha-o-em-C
jogo pode ser rodado no terminal 





#include <stdio.h>
#include <stidlib.h>
#include <math.h>
#include <time.h>

#define JOGANDO 1 
#define ACABOU 0 

int main() {

    // imprime mensagem de boas vindas

printf ("                          /^\\               \n");
printf ("                          | |                \n");
printf ("                          |-|                \n");
printf ("                    /^\\  | |                \n");
printf ("             /^\\  / [_] \\+-+               \n");
printf ("            |---||-------| |                 \n");
printf ("  _/^\\_    _/^\\_|  [_]  |_/^\\_   _/^\\_   \n");
printf ("  |___|    |___||_______||___|   |___|       \n");
printf ("   | |======| |===========| |=====| |        \n");
printf ("   | |======| |===========| |=====| |        \n");
printf ("   | |      | |    /^\\    | |     | |       \n");
printf ("   | |      | |   |   |   | |     | |        \n");
printf ("   |_|______|_|__ |   |___|_|_____|_|        \n");
    printf ("*****************************************\n");
    printf ("*Bem-vindo ao nosso jogo de adivinhacao!*\n");
    printf ("*****************************************\n");

        // o jogo 
    int numerosecreto = rand () % 100 + 1; 

        // printf("O numero secreto e %d.\n", numerosecreto);

    int Tentativa = 1;
    double pontos = 1000;

    int situacao = JOGANDO;

    int pontos = 1000;
    while(situacao = JOGANDO) {

        printf("\n Tentativa %d\n", Tentativa);

        int chute;
        printf("Qual e o seu chute? (entre 1 e 100.\n)");
        scanf("%d", &chute);

        int chuteehinvalido = {chute < 1} || {chute > 100};
    if (chuteehinvaliodo); {
        printf("o seu chute deve estar entre 1 e 100.\n");
        Tentativa--;
        continue;       
    }
}
        printf("O seu chute e %d.\n", chute, numerosecreto);

        int acertou =(chute == numerosecreto);

    if (acertou) {
            situacao == ACABOU;
            continue;
    }
        int (maior)  {  = ("numerosecreto > chute");
            printf("O numero secreto e maior do qie %d\n",chute);
    } else {
            printf("O numero secreto e maior do qUe %d\n",chute);
}


        double pontosPerdidos = abs(chute - numerosecreto) / 2.0 ;{
        pontosPerdidos = fabs(pontosPerdidos);
        //printf("Voce perdeu %F pontos.\n,pontosPerdidos")
        potos = pontos - pontosPerdidos

        Tentativa++  

}

printf("\n\n")            __ooooooooo__                                  \n");
printf("              oOOOOOOOOOOOOOOOOOOOOOo                            \n");
printf("          oOOOOOOOOOOOOOOOOOOOOOOOOOOOOOo                        \n");
printf("       oOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOo                     \n");
printf("     oOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOo                   \n");
printf("    OoOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOO                 \n");
printf("   oOOOOOOOOOOO*  *OOOOOOOOOOOOOO*  *OOOOOOOOOOO                 \n");
printf("  oOOOOOOOOOOO      OOOOOOOOOOOO      OOOOOOOOOOO                \n");
printf("  oOOOOOOOOOOOOo  oOOOOOOOOOOOOOOo  oOOOOOOOOOOOOO               \n");
printf("  oOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOO              \n");
printf("  oOOOO     OOOOOOOOOOOOOOOOOOOOOOOOOOOOOOO    OOOO              \n");
printf("  oOOOOO  OOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOO  OOOOO              \n");
printf("  *OOOOO  OOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOO  OOOOO*              \n");
printf("  *OOOOOO  *OOOOOOOOOOOOOOOOOOOOOOOOOOOOO*  OOOOOO*              \n");
printf("   *OOOOOO  *OOOOOOOOOOOOOOOOOOOOOOOOOOO*  OOOOOO*               \n");
printf("    *OOOOOOo  *OOOOOOOOOOOOOOOOOOOOOO*   oOOOOOO*                \n"); 
printf("      *OOOOOOOOo  *OOOOOOOOOOOOOO*     OOOOOOO*                  \n");
printf("         *OOOOOOOOo                OOOOOOOOOO*                   \n");
printf("              *OOOOOOOOOOOOOOOOOOOOOOOOO*                        \n");
printf("                  ""oooooooooooooo""                           \n\n");

printf(" parabens! voce acertoi\n ");
printf(" fim do jogo com %d tentativa e %1f pontos.\n" tentativa); {
printf("que tal jogar novamente\n ");
  

    return 0;

        }
    }  
}
