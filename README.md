# What-Are-Anonymous-Methods-in-C-
What Are Anonymous Methods in C#?
class Example{
delegate double AreaOfSquareDelegate(int side);
Public static void main()
{
AreaOfSquareDelegate areaOfSquare= delegate(int side){
return side*side;
};
Double area= areaOfSquare(4);
}
}
