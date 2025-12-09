#include <stdio.h>
#include <math.h>

#define N 5

int main()
{
    int i;
    float x;
    float racx;

    printf("------ Practical Work N° 8 ------\n");
    printf("Calculating %d square roots\n", N);

    for (i = 0; i < N; i++)
    {
        printf("Give a number: ");
        scanf("%f", &x);

        if (x < 0.0)
        {
            printf("%f does not have a square root\n", x);
        }
        else
        {
            racx = sqrt(x);
            printf("%f has the square root = %f\n", x, racx);
        }
    }

    printf("Work Done - Goodbye\n");

    return 0;
}

