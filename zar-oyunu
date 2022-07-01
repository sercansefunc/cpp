cout<<"kac kez zar atilacak?"<<endl;
    int kackez;
    cin>>kackez;
    srand(time(NULL));
    int skor=0;
    int a[kackez];
    int b[kackez];
    int random1,random2;
    for (int i = 0; i < (kackez); ++i) {
        random1=rand()%6+1;
        random2=rand()%6+1;
        b[i]=random2;
        a[i]=random1;
        if (random1>random2)
            skor++;
        else if (random1<random2)
            skor--;
    }
    for (int i = 0; i < kackez; ++i)
        cout<<a[i]<<" | ";
    cout<<endl;
    for (int i = 0; i < kackez; ++i){

        cout<<b[i]<<" | ";}
    cout<<endl;
    if (skor>0)
        cout<<"1. kullanici kazandi"<<endl;
    else if (skor<0)
        cout<<"2. kullanici kazandi"<<endl;
    else if (skor==0)
        cout<<"berabere"<<endl;
