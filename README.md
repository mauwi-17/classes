# classes
<?php
#Class 1
#Coffee shop employee
//class Employee {
    //public $employee_id;
   // public $name;
   // public $age;
    //public $gender;

    // Constructor
   // public function __construct($pemployee_id, $pname, $page, $pgender)
    //{
        //$this->employee_id = $pemployee_id;
       // $this->name = $pname;
        //$this->age = $page;
        //$this->gender = $pgender;

       // echo "Employee_Id: $this->employee_id, Name: $this->name, Age: $this->age, Gender: $this->gender<br>";
    //}

    // Methods
   // public function logIn() {
        //echo "Logged In <br>";
   // }
    
    //public function takeOrder() {
      //  echo "Take Order <br>";}
    
    
   // public function makeCoffee() {
        //echo "Make Coffee <br>";
    //}
   // public function logOut(){ 
    //    echo "Logged Out <br> <br>";
    //}
//}

//$employee = new Employee ("1234", "Erica Mae", "20", "Female");

//employee->logIn();
//$employee->takeOrder();
//$employee->makeCoffee();
//$employee->logOut();



#class 2
//class Bank{
    //public $number;
    //public $owner;
    //public $balance;
   // public $type;

//constructor
//public function __construct($pnumber, $powner, $pbalance, $ptype){
   // $this->number =$pnumber;
    //$this->owner = $powner;
    //$this->balance = $pbalance;
    //$this->type = $ptype;

   // echo "Account Number: $this->number, Account Owner: $this->owner, Balance: $this->balance, Account Type: $this->type <br>";

//}
//methods

//public function deposit($amount){
   // $this->balance += $amount;
    //echo "Deposited: $amount | New Balance: $this->balance <br>";

//}
//public function withdraw($amount){
     //if ($amount <= $this->balance) {
       // $this->balance -= $amount;
      //echo "Withdrew: $amount | New Balance: $this->balance <br>";
    // } 
     
    // else {
           // echo "Insufficient funds! Cannot withdraw $amount <br>"; }
    // }  
     
//public function check (){
    //echo "Current Balance: $this->balance <br>";
    //return $this->balance;
//}
//public function transfer($amount, $recipientAccount) {
  //   if ($amount <= $this->balance) {
      //  $this->balance -= $amount;
  //  echo "Transferred: $amount to $recipientAccount | New Balance: $this->balance <br>";}
  //  else { echo "Insufficient funds! Cannot transfer $amount <br>";

//}}
//}
//$bank = new Bank ("202411561", "Kaye Evalla", "50000", "Savings");

//$bank->deposit(3000);
//$bank->withdraw(2000);
//$bank->check();
//$bank->transfer(2500, "202411562");
//$bank->check();

//
#class 3
//class Cat {
   // public $name;
   // public $color;
    //public $age;
  // public $breed;
//constructor
     //public function __construct($pname, $pcolor, $page, $pbreed) {
      // $this->name = $pname;
       // $this->color = $pcolor;
        //$this->age = $page;
       // $this->breed = $pbreed;
       // echo "Meet {$this->name}, a {$this->color} cat who is {$this->age} years old, and has breed {$this->breed} <br>";
    //}
   // public function meow() {
        //echo "{$this->name} says: Meow! Meow!<br>";
   //}
   // public function sleep() {
     //   echo "{$this->name} is sleeping... Zzzzz<br>";
    //}//
    // function eat($food) {
      //  echo "{$this->name} is eating {$food}<br>";
    //}
   // public function play() {
   //    echo "{$this->name} is playing with a toy<br>";
    //}
//}

//$cat = new Cat("Mauwi", "orange", 3, "Persian");
//$cat->meow();
//$cat->eat("fish");
//$cat->play();
//$cat->sleep();

//
# class 4
//class Bike {
   // public $brand;
   // public $color;
    //public $speed;

    // Constructor
    //public function __construct($pbrand, $pcolor) {
      //  $this->brand = $pbrand;
      //  $this->color = $pcolor;
      //  $this->speed = 0;
       // echo "{$this->color} {$this->brand} bike is ready!<br>";
// Methods
   // public function pedal() {
       // $this->speed += 5;
      //  echo "Pedaling... Speed: {$this->speed} km/h<br>";
  //  }
    
   // public function brake() {
   //     $this->speed = max(0, $this->speed - 5);
   //     echo "Braking... Speed: {$this->speed} km/h<br>";
   // }
    
  //  public function ringBell() {
  //      echo "Ring! Ring! 🚲<br>";
//    }
    
    //public function checkSpeed() {
  //      echo "Current speed: {$this->speed} km/h<br>";
   // }
//}

//$bike = new Bike("Trek", "Blue");
//$bike->pedal();
//$bike->pedal();
//$bike->ringBell();
//$bike->brake();
//$bike->checkSpeed();

//
#class 5
//class LightSwitch {
   //public $isOn = false;
    
   // public function toggle() {
   //     $this->isOn = !$this->isOn;
        //echo "Light is " . ($this->isOn ? "ON" : "OFF") . "<br>";
   // }
//}

//$light = new LightSwitch();
//$light->toggle();
//$light->toggle();

//
#vending machine
//function vendingMachine($coinSlot, $choice){
//  if($choice == "C"){
  //  return "Coke";
 // }
//  if($choice == "P"){
   // return "Pepsi";
 // }
  //if($choice == "R"){
   // return "Royal";
//  }

//}
//echo vendingMachine(200, "R");

// vending machine 2

//function useVendingMachine($money, $choice) {
   // if ($choice == "01") {
      //  $change = $money - 50;
      //  return "Coca-Cola. <br> Change: $" . number_format($change, 2);
   // }
    //if ($choice == "02") {
     //   $change = $money - 40;
      //  return "Sprite. <br> Change: $" . number_format($change, 2);
   // if ($choice == "03") {
     //   $change = $money - 40;
       // return "Royal. <br> Change: $" . number_format($change, 2);
    //}
    //if ($choice == "04") {
       // $change = $money - 50;
      // return "Pepsi. <br> Change: $" . number_format($change, 2);
   // }
    //return "Invalid selection";
//}

// Example usage:
//echo "Order 1: " . useVendingMachine(100, "01") . "<br>";
//echo "Order 2: " . useVendingMachine(100, "02") . "<br>";
//echo "Order 3: " . useVendingMachine(100, "03") . "<br>";
//echo "Order 4: " . useVendingMachine(100, "04") . "<br>";

?>
