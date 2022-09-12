# MPG
Mile per gallon 
// In this program I will calculate MilesPerGallon 
#include<iostream> 
using namespace std;
int main()
{
    //declare the variable for the program
    double MileTravelled, OdmeterTwo, OdometerOne, MPG, Gallons;

    cout<<"\nThis program determines the average miles per gallon that your car can achieve.\n";
    cout<<"First, we will calculate the mile travelled.\n";
    cout<<"Please enter your odemeter at your previous fill up:\n";
    cin>> OdometerOne; // odometer at previous fill up
    cout<< "Please now enter your odemeter at your latest fill up:\n";
    cin>> OdmeterTwo; // odoneter at the latest fill up

    // calculate mile travelled
    MileTravelled= OdmeterTwo-OdometerOne;
    cout<<"Your mile travelled is: " << MileTravelled<<"\n";

    // get the input from the user
    cout<<"Now we will calculate the mile per gallon\n";
    cout<<"Please enter gallon purchased at the latest fill up:\n";
    cin>>Gallons;

    // calculate mile per gallon 
    MPG= MileTravelled/Gallons;

    // display the MPG
    cout<<"The mile per gallon that your car can acheive is: "<<MPG<<"\n";

    return 0; 

}