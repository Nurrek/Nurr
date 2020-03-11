# Nurr
new repository
package javaapplication1;

class telephone {
    String brand;
    long  number ;
    double inches;
  

    public telephone(String brand,
                 double inches, long number ) {
        this.brand = brand;
        this.inches = inches;
        this.number = number;
    }
        
     public void Sending_SMS (String X_massage, long Y_Number){
           System.out.println("Sending the masssage "+X_massage +"to number"+ Y_Number);
                 
                 
                 }
}           
