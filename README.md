# -mang1chieu
void mang::chenk(int k, int x){
	if(k<0||k>n){
		return;
	}
	for(int i=n;i>k;i--){
		a[i]=a[i-1];
	}
	a[k]=x;
	n++;
}
