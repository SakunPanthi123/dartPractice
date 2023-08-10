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


