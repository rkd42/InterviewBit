vector<int> Solution::wave(vector<int> &A) {
    long long int n=A.size();
    long long int i ;
    long long int temp;
    sort(A.begin(), A.end()); 
    for(i=0;i<n-1;i=i+2){
        temp=(long long int)A[i];
        A[i]=(long long int)A[i+1];
        A[i+1]=temp;
        
    }
    return A;
}
