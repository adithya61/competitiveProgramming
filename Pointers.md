### Pointers
```
        int b[2][3] = {{1, 3, 4},{9,10,11}};
        int (*p)[3] = b;
        cout << &b << endl; // address of b
        cout << b[0] << endl; // address of b
        cout << b << endl; // address of b
        cout << *(b + 1) + 2 << endl; // address of 11
        cout << *(*b + 1) << endl; // 3
        cout << *(*b + 2) << endl; // 4
        cout << *(*(b + 1) + 1)<< endl; // 10
        cout << *(*b ) << endl; // 1
        cout << *(*b + 1) << endl; // 3
        cout << *(*b + 2) << endl; // 4
        cout << *(*(b + 1)) << endl;  // 9
        cout << *(*(b + 1) + 1) << endl;  // 10
        cout << *(*(b + 1) + 2) << endl;  // 11
