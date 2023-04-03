# Week2

https://www.notion.so/Week2-e95ad70053ba47a0b37fa368b109f674?pvs=4

[https://www.youtube.com/watch?v=mLQ-ehf3d6Y&feature=youtu.be](https://www.youtube.com/watch?v=mLQ-ehf3d6Y&feature=youtu.be)

# 위젯 넣기

## **글자 위젯**

**→ `Text('안녕')`**

**→ 안녕 위치에 원하는 글자 넣기**

## **아이콘 위젯**

**→ `Icon(Icons.*shop*)`**

**→ Icons. 뒤에 넣고 싶은 아이콘 이름을 넣는다.** 

**→ 아이콘 이름은 [https://api.flutter.dev/flutter/material/Icons-class.html](https://api.flutter.dev/flutter/material/Icons-class.html)에서 찾을 수 있다.**

## **이미지 위젯**

`**Image.asset('경로')**`

**→ 이미지를 넣고 싶을 땐 이미지가 프로젝트 폴더 안에 존재해야 한다.** 

**→ 이미지를 프로젝트 폴더 안에 넣은 후 등록해야 한다. (이 부분이 웹과 다르다.)**

## **박스 위젯**

`**Container()` 혹은 `SizedBox()` 사용**

**→ 박스 위젯을 이용하여 상단바, 하단바, 카드 레이아웃 등을 만들 수 있다.**

**→ 괄호 안에 width : 50, height : 50, color: Colors.blue 와 같이 width, height, color을 지정해준다.**

**→ Flutter의 사이즈 단위는 LP(Logical Pixel)로 50LP는 1.2cm이다.**

# **추가 내용**

## **child 사용하기**

`**위젯(child:(위젯))**`

**→ 위젯 안에 자식 위젯을 넣을 수 있다.**

## **Lint 관련 warning 무시하기**

```
prefer_typing_uninitialized_variables : false
prefer_const_constructors_in_immutables : false
prefer_const_constructors : false
avoid_print : false
```

**→ lint를 하지 않도록 해준다.**

### **lint란?**

**→ 코드의 오류나 버그 등을 미리 점검하기 위해 사용하는 툴**

**→ 오타에 대해 빨간 줄이나 표시로 알려준다.**

**→ 코드의 가독성을 높이고, 동적 언어의 특성인 런타임 버그를 예방하는 역할을 한다.**

### **앱을 구동시키는 명령어**

**→ `runApp(const MyApp());`**

### **pubspecc.yaml 파일**

**→ 앱 만들 때 필요한 모든 자료를 정리한 파일. 외부 패키지, 라이브러리들을 기록하기도 함**

**구글링 출처**

[https://coconuts.tistory.com/738](https://coconuts.tistory.com/738)

[https://jeonghwan-kim.github.io/series/2019/12/30/frontend-dev-env-lint.html](https://jeonghwan-kim.github.io/series/2019/12/30/frontend-dev-env-lint.html)
