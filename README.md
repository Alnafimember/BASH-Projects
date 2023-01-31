# BASH-Project
Project 1

Given three integers (X,Y, and Z) representing the three sides of a triangle, identify whether the triangle is scalene, isosceles, or equilateral.

-->If all three sides are equal, output EQUILATERAL.
-->Otherwise, if any two sides are equal, output ISOSCELES.
-->Otherwise, output SCALENE.

echo -e "Enter the values of x, y and z:"
read x
read y
read z
if [ $x == $y ];
then
    if [ $x == $z ];
    then 
    echo "EQUILATERAL"
    else
    echo "ISOSCELES"
fi
elif [ $x == $z]
then
    echo "ISOSCELES"
else
    echo "SCALENE"
fi


