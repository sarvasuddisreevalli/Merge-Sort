void SelectionSort(int A[],int n,int B[]){
	for(int i=0;i<n;i++){
		int min=A[0],k=0;
		for(int j=0;j<n;j++){
			if(A[j]<min){
				min=A[j];
				k=j;
			}
		}
		B[i]=min;
		A[k]=1e9;
	}
}
int main() {
	int n;
	scanf("%d",&n);
	
	int A[n];
	for(int i=0;i<n;i++){
	    scanf("%d",&A[i]);
	}
	int B[n];
	// function call
	SelectionSort(A,n,B);
	for(int i=0;i<n;i++){
	    printf("%d ",B[i]);
	}
}
