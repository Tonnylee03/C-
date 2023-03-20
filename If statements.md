```c++
int main()
{   
    bool isMale = true;
    
    if(isMale){
        cout << "You are a male";
    } else {
        cout << "You are not male";
    }
    return 0;
}
// output
// You are a male
```

## && (and)

```c++
int main()
{   
    bool isMale = true;
    bool isTall = true;
    
    if(isMale && isTall){    // both have to be true
        cout << "You are a tall male";
    } else {
        cout << "You are not a tall male";
    }
    return 0;
}

// You are a tall male
```
## || (or)
```
if(A || B){
  ...
}
```

## Comparisons 
```
>
<
>=
<=
!=
```
```c++
int getMax(int num1, int num2){
    int result;
    if(num1>num2){
        result=num1;
    } else {
        result=num2;
    }
    return result;
    
}

int main()
{   
    cout << getMax(3, 999);
    return 0;
}
// 999
```
### practice: compare 3 numbers
