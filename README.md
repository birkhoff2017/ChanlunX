# ChanlunX

## ��α���

### Visual Studio 2019

ͨ���Ų����Ҫ�����32λ��������Visual Studio 2019�����������õ���Visual Studio 2019�����档

```cmd
mkdir build
cd build
cmake -G "Visual Studio 16 2019" -A Win32 ..
cmake --build . --config Release
```

### Visual Studio 2015 ���� Visual Studio 2017

����Ŀ��Ŀ¼������ִ����������

```cmd
mkdir build
cd build
cmake ..
cmake --build . --config Release
```

## ��ͼ����

�ѱ���õ�DLL�ŵ�ͨ���ŵ�T0002\dllsĿ¼����Ϊ2�ź���������Ĵ�������ͨ������ͼ��ʽ��

```text
FRAC:=TDXDLL2(2,H,L,0);{��׼��}
NOTEXT��������2:DRAWLINE(FRAC=-1,L,FRAC=+1,H,0), DOTLINE,COLORYELLOW;
NOTEXT���½���2:DRAWLINE(FRAC=+1,H,FRAC=-1,L,0), DOTLINE, COLORYELLOW;

BIZG:=TDXDLL2(5,FRAC,H,L);{���BI�����}
BIZD:=TDXDLL2(6,FRAC,H,L);{���BI�����}
BISE:=TDXDLL2(7,FRAC,H,L);{���BI���࿪ʼ�ͽ���}

NOTEXT_BIZG:IF(BIZG,BIZG,DRAWNULL),COLORYELLOW;{��BI�����}
NOTEXT_BIZD:IF(BIZD,BIZD,DRAWNULL),COLORYELLOW;{��BI�����}
NOTEXT_BISE:STICKLINE(BISE,BIZD,BIZG,0,0),COLORYELLOW;{��BI������ʼ����};

DUAN1:=TDXDLL2(3,FRAC,H,L);{����εĶ˵�,3�ĳ�4��1+1�սử��}
NOTEXT��������1:DRAWLINE(DUAN1=-1,L,DUAN1=+1,H,0), COLORFF8000;
NOTEXT���½���1:DRAWLINE(DUAN1=+1,H,DUAN1=-1,L,0), COLORFF8000;

DUANZG1:=TDXDLL2(5,DUAN1,H,L);{����������}
DUANZD1:=TDXDLL2(6,DUAN1,H,L);{����������}
DUANSE1:=TDXDLL2(7,DUAN1,H,L);{��������࿪ʼ�ͽ���}

NOTEXT_DDUANZG1:IF(DUANZG1,DUANZG1,DRAWNULL),COLORFF8000;{���������}
NOTEXT_DDUANZD1:IF(DUANZD1,DUANZD1,DRAWNULL),COLORFF8000;{���������}
NOTEXT_DDUANSE1:STICKLINE(DUANSE1,DUANZD1,DUANZG1,0,0),COLORFF8000;{����������ʼ����};
```

## ����

QQȺ�����ҽ�����������Ⱥ�������ż�����ȡһ������Ϊ��Ŀ�ĳ���ά�������൱�������ߺ����ο��ȣ����߱�����ṩ��������ʹ�á��������Ⱥ�Ŀ���ͨ������ķ�ʽ����ϵ���ߡ���Ⱥ������������δ��Դ�İ汾��Դ�룬���߿������Ա�Ч���ġ������Դ����밲װҲ������Ⱥ��ð�����

- WeChat: kldcty
- QQ: 1106628276
- ΢�Ź��ں�: zeroquant

## ��Դ��Ч��ͼ

![](Ч��ͼ.png)
