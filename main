#include<bits/stdc++.h>
#define reg register
#define file(f) freopen(#f".in","r",stdin);freopen(#f".out","w",stdout)
extern "C"{
	namespace io{
		const int in=100000,out=100000;
		static char buf[in],duf[out],*q1=duf,*p1=buf,*p2=buf,ch[20];
		inline char gcf(){
			return (p1==p2&&(p2=(p1=buf)+fread(buf,1,in,stdin),p1==p2)?EOF:*p1++);
		}
		inline int read(){
			reg int f=0,x=0;
			char ch=gcf();
			while(!isdigit(ch))f|=ch=='-',ch=gcf();
			while(isdigit(ch))x=(x<<3)+(x<<1)+(ch^48),ch=gcf();
			return f?-x:x;
		}
		inline void write(int ans){
			reg int i=0;
			ans<0?ans=-ans,*q1++='-':EOF;
			do{ch[i++]=ans%10+48;ans/=10;}while(ans);
			while(i)*q1++=ch[--i];
		}
		inline void flush(){
			fwrite(duf,q1-duf,1,stdout);
		}
	}	
	
}
using namespace std;
#define rd io::read
#define wt io::write
int main(){
	file(test);
	int n;
	n=rd();
	wt(n);
	io::flush();
	fclose(stdin),fclose(stdout);
	return 0;
};
