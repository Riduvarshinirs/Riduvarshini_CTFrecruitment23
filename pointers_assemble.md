#Pointers Assemble
- we are taking number of elements in array as input
- input elements of array
- print sorted array
- https://github.com/Riduvarshinirs/Riduvarshini_CTFrecruitment23/blob/main/screenshots/ef3f324a-47dc-4933-a0df-d36161ec16ed.jpg
-#include <stdio.h>
-int main()
-{
-    int p, q, r, s, greatest, points;

-    printf("\nInput the first integer: ");
-    scanf("%d", &p);
-    printf("\nInput the second integer: ");
-    scanf("%d", &q);
-    printf("\nInput the third integer: ");
-    scanf("%d", &r);
-    printf("\nhow many times u want the programme to run?: ");
-    scanf("%d", &s);
-    for (int i = 0; i < s; i++)
-    {
-
 -       if (p > q && p > r)
 -       {
 -           greatest=p;
 -           p=p-1;
  -          //printf("%d is greatest", p);
  -      }
 -       if (q > p && q > r)
 -       {
 -           greatest=q;
 -           q=q-1;
 -           //printf("%d is greatest", q);
 -       }
-        if (r > q && r > p)
 -       {
 -           greatest=r;
 -           r=r-1;
-            //printf("%d is greatest", r);
-      }
-       printf("number becomes=%d\n", greatest = greatest - 1);
-       points = points + greatest;
-    }
  -  printf("points=%d\n", points);

 -   return 0;
-}
