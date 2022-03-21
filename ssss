#include <stdio.h>

int main(int argc, char const *argv[])
{
    int Nighttarif = 1;
    int Daytarif = 2;
    int Eveningtarif = 3;

    int usedpower;
    printf("Enterusedpower: ");
    scanf("%d", &usedpower);

    int time;
    printf("Entertime(hours): ");
    scanf("%d", &time);

    int result;
    if (time >= 0 && time < 8) {
        result = Nighttarif * usedpower; 
    }else if (time >= 8 && time < 16) {
        result = Daytarif * usedpower;
    }else if (time >= 16 && time < 24) {
        result = Eveningtarif * usedpower;
    }
    printf("totalprice: %d", result);
    return 0;
}
