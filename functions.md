## function stub
```c++
void sayHi(); // defined a function first

int main()
{   
    
    cout <<"before calling sayHi()\n";
    sayHi(); // Calling function
    cout <<"after calling sayHi()";
    
    return 0;
}
void sayHi(){
    cout << "Hello User\n";
}
```
```c++
void sayHi(){
    cout << "Hello User\n";
}

int main()
{   
    
    cout <<"before calling sayHi()\n";
    sayHi(); // Calling function
    cout <<"after calling sayHi()";
    
    return 0;
}
```
```
output
before calling sayHi()
Hello User
after calling sayHi()
```



## Parameters
```c++
void sayHi(string name){
    cout << "Hello " << name;
}

int main()
{   
    
    cout <<"Passing value to sayHi()\n";
    sayHi("Tonny"); // Passing "Tonny" as an argument
    
    return 0;
}
```
```
output
------
Passing value to sayHi()
Hello Tonny
```

## Return
- It's telling c++ that we're done executing the code
### Return Types
cube a number
```c++
double cube(double num){
    double result = num * num * num;   
    return result;           // return num * num * num;
    cout << "Hello";         // will not be executed
}

int main()
{   
    cube(5.0);               // return a value
    cout << cube(5.0);
    
    double answer=cube(5.0); //store value in a variable
    cout << "\n" << answer;
    
    return 0;
}
```
```
output
------
125
125
```
