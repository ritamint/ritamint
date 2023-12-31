- 👋 Hi, I’m @ritamint
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
ritamint/ritamint is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
#include <stdio.h>
/**
 *  ++*
 *  +**
 *  ***
 * 
*/
int main()
{

    int i=1, j, n = 8;
    
//line change
    for (i = 1; i <= n; i++)
    {
        // plus print
        for (j = 1; j <= n-i; j++)
        {
            printf(" ");   
        }
        // star print
        for (j = 1; j <= i; j++)
        {

            printf("*");
        }
        printf("\n");
    }

    return 0;
}


