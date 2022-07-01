char c;
    cout<<"Bir buyuk harf giriniz: "<<endl;
    cin>>c;
    if ((int)c<65 | (int)c>90)
        cout<<"Buyuk harf girmediniz."<<endl;
    else {
        for (int i = c - 65; i < 26; ++i) {
            for (int j = c - 65; j <= i; ++j)
                cout << char(j + 65);
            for (int j = i - 1; j >= c - 65; --j)
                cout << char(j + 65);
            cout << endl;
        }
