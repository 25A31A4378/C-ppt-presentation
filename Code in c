#include <stdio.h>

struct Student {
    int id;
    char name[20];
};

int main() {
    struct Student s[5];
    int n, i, search, found = 0;

    printf("Enter number of students: ");
    scanf("%d", &n);

    
    for (i = 0; i < n; i++) {
        printf("Enter ID and Name: ");
        scanf("%d %s", &s[i].id, s[i].name);
    }

    
    printf("\nStudent List:\n");
    for (i = 0; i < n; i++) {
        printf("%d %s\n", s[i].id, s[i].name);
    }
    printf("\nEnter ID to search: ");
    scanf("%d", &search);

    for (i = 0; i < n; i++) {
        if (s[i].id == search) {
            printf("Found: %s\n", s[i].name);
            found = 1;
        }
    }

    if (!found)
        printf("Not Found\n");

    return 0;
}
