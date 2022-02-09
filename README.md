- 👋 Hi, I’m @It21167928
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
It21167928/It21167928 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
#include <stdio.h>

int areaRectangle(int, int);

int main()
{
    int l, b, area;
    printf("Enter the length : ");
    scanf("%d", &l);

    printf("Enter the width : ");
    scanf("%d", &b);

    area = areaRectangle(l, b);

    printf("The area of the rectangle : %d", area);

    return 0;
}

int areaRectangle(int length, int width)
{
    return length * width;
}
