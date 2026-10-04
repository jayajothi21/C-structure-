# C-structure-

1.Write a C program to create a structure Student with the members name, roll_no, and marks. Read the details of one student and display them.  

#include <stdio.h>

struct Student {
    char name[50];
    int roll_no;
    float marks;
};

int main() {
    struct Student s;

  printf("Enter name: ");
  scanf(" %[^\n]", s.name);
    printf("Enter roll number: ");
    scanf("%d", &s.roll_no);
    printf("Enter marks: ");
    scanf("%f", &s.marks);
    printf("\n--- Student Details ---\n");
    printf("Name   : %s\n", s.name);
    printf("Roll No: %d\n", s.roll_no);
    printf("Marks  : %.2f\n", s.marks);
    return 0;
}
2. Write a C program to create a structure Employee with the members id, name, and salary. Read and display the details of an employee.

#include <stdio.h>

struct Employee {
    int id;
    char name[50];
    float salary;
};

int main() {
    struct Employee e;

  printf("Enter employee id: ");
    scanf("%d", &e.id);
    printf("Enter name: ");
    scanf(" %[^\n]", e.name);
    printf("Enter salary: ");
    scanf("%f", &e.salary);

  printf("\n--- Employee Details ---\n");
    printf("ID     : %d\n", e.id);
    printf("Name   : %s\n", e.name);
    printf("Salary : %.2f\n", e.salary);
    return 0;
}
3. Write a C program to create a structure Book with the members title, author, and price. Read the details of one book and display them

#include <stdio.h>

struct Book {
    char title[100];
    char author[50];
    float price;
};

int main() {
    struct Book b;
    printf("Enter book title: ");
    scanf(" %[^\n]", b.title);
    printf("Enter author: ");
    scanf(" %[^\n]", b.author);
    printf("Enter price: ");
    scanf("%f", &b.price);

  printf("\n--- Book Details ---\n");
    printf("Title  : %s\n", b.title);
    printf("Author : %s\n", b.author);
    printf("Price  : %.2f\n", b.price);
    return 0;
}
