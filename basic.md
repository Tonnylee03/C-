```c++
int main()
{
    string name = "Tonny";
    int age = 21;
    double gpa = 3.98;
    char grade = 'A';  //single quotation mark

    cout << "Hello, my name is " << name << endl;
    cout << "My age is " << age << " Nice to meet you guys" <<endl;
    cout << "Grade: " << grade << " \nGpa: " << gpa; // endl and \n: print out a new line

    return 0;
}

```

```c++
int main()
{
    string name;
    int age;
    char grade;

    cout << "name: ";
    getline(cin, name);

    cout << "age: ";
    cin >> age; // automatically ends line

    cout << "grade: ";
    cin >> grade;

    cout << "my name is " << name << endl << age << " years old\n" << "grade: " << grade;

    return 0;
}
```
