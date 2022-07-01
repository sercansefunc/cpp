  int matris[3][3]={5,4,3,4,0,4,7,10,3};
    for (int i = 0; i < 3; ++i) {
        for (int j = 0; j < 3; ++j) {
            cout<<matris[i][j]<<" ";
        }
        cout<<endl;
    }
    for (int i = 0; i < 3; ++i) {
        for (int j = i+1; j < 3; ++j) {
            int g=matris[j][i];
            matris[j][i]=matris[i][j];
            matris[i][j]=g;
        }
    }
    for (int i = 0; i < 3; ++i) {
        for (int j = 0; j < 3; ++j) {
            cout<<matris[i][j]<<" ";
        }
        cout<<endl;
