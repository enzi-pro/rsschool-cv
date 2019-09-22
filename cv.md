# Nurmukhamed Zhanibek

## Contact Information
Email address: zhanibek.n.karaganda@gmail.com

or alternatively [@enzi.vue](https://www.instagram.com/enzi.vue/) on Instagram / [@enzipage](https://vk.com/enzipage) on VK

## Summary
There are a couple of rules that I stick by
1. Committing to something I started
1. Making the most out of my day
1. Permanently learning

My goals in life are aligned with these rules as I strive to help those in need, while advancing myself.

## Skills

Skill | Level of Proficiency
:---: | :---
HTML & CSS | Upper-Intermediate
PHP | One Year of Practice
C# in .NET | 120 hours of Courses
3D Modeling | Took a Class in College
Responsive Design | Saw a Guide on Youtube

## Code Examples
This code snippet is from my latest assignment in **Programming for Engineers**
```C
float my_det(float x1, float x2, float y1, float y2)
{
    return (x1*y2-x2*y1);
}

int main()
{
    float a1, b1, k1, a2, b2, k2, x, y;
    printf("Enter a1, b1, k1, a2, b2, k2: ");
    scanf("%f %f %f %f %f %f", &a1, &b1, &k1, &a2, &b2, &k2);

    if ((my_det(a1, a2, b1, b2) < 0.001) && (my_det(a1, a2, b1, b2) > -0.001))
    {
        printf("A unique solution does not exist.");
        return 0;
    }
    x = my_det(k1, k2, b1, b2) / my_det(a1, a2, b1, b2);
    y = my_det(a1, a2, k1, k2) / my_det(a1, a2, b1, b2);

    printf("The solution is:\nx = %f", x);
    printf("\ny = %f", y);
    return 0;
}
```

## Experience
* 6 month of practicing the MVC Framework
* 2 school projects in PHP ([Mathematics Club Website](http://t77759pa.beget.tech/kz/) / [Football Website](http://o77870mk.beget.tech))
* Studied Computer Science in school