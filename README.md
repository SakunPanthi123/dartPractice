# dartPractice

// Switch case statements
void main(){
  var j = 2;
  converter(j);
}

// this function compares the values of i and j
void converter(int j){
  switch (j){
    case 1:
      print('The number is one');
      
    case 2:
      print('The number is two');
     
    case 3:
      print('The number is three');
      
    case 4:
      print('The number is four');
     
    default:
      print('The number you have inserted is beyond range');
      
  }
}


// for statements
void main(){
  var j = 10;
  printer(j);
}

// this function compares the values of i and j
void printer(int j){
  for(int k = 0; k<j; k++){
    print('Hello');
  }
}

// class for creating a person and their properties
void main(){
  Person p1 = Person(name: 'Abhishek', age: 21);
  print('My name is ${p1.name} and my age is ${p1.age} years old');
}


// class called person
class Person{
  String? name;
  int? age;
  
  Person({required this.name, required this.age});
}

// static keyword
void main(){
  Person.printer();
}


// class called person
class Person{
  static final String name = 'name';
  static final String age = 'number';
  
  
  static void printer(){
    print('My name is $name and my age is $age years old');
  }
}



