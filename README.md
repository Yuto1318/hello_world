# ������demo������
---
## ����

1.�������������߳�

2.���������ε������������ε�������ܳ�


 û������**һ�������cܳ��Ŀ**��
 ֻ��һ��cܳ��**�˼�**���ã������ѧ��cܳ������Ѿ��ߵ��˸��˵ı���۷塣
 �����ѹ�һ����أ���˵��δ����ǿ���⣬û���漰ָ�����鼰һЩ�����ӵ�Ӧ�ã�
 ������**չʾĿǰ����ˮƽ**��Ҫ�󣬰������������Ǻ��ʺϵġ�
## ����
```c++
#include <iostream>
#include <cmath>
using namespace std;
class sjx
{
	int a, b, c;
public:
	void setbian(int aa, int bb, int cc)
	{
		a = aa; b = bb; c = cc;
	}
	void showbianchang()
	{
		cout << "���߳�Ϊ��" << a << ',' << b << ',' << c << endl;
	}
	double mianji()
	{
		int p = (a + b + c) / 2;
		return sqrt(p*(p - a)*(p - b)*(p - c));
	}
	double zhouchang()
	{
		return (a + b + c);
	}
};
int main()
{
	sjx x;
	int a, b, c;
	cout << "���������������߳���" << endl;
	cin >> a >> b >> c;
	x.setbian(a, b, c);
	cout << "���������Ϊ��" << x.mianji() << endl;
	cout << "�������ܳ�Ϊ��" << x.zhouchang() << endl;
	cout << "�Ƿ���ʾ���߳�����--1 ��--0" << endl;
	int t;
	cin >> t;
	if (t == 1)
		x.showbianchang();
	return 0;
}
```
## ִ��ͼƬ
![������](\markdownר��\yxt.png '�����ڼ��س�����')