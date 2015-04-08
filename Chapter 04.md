# Chapter 04: 스택 스크롤 (Scrolling the Stack) #

by [@justinchronicle](https://twitter.com/justinchronicle)

> 원문은 아래 링크를 확인하시기 바랍니다:
> [https://download.xamarin.com/developer/xamarin-forms-book/BookPreview2-Ch04-Rel0203.pdf](https://download.xamarin.com/developer/xamarin-forms-book/BookPreview2-Ch04-Rel0203.pdf)

만약에 당신도 대부분의 개발자들과 비슷하다면, 지난 챕터에서 나왔던 정적 `Color` 속성 리스트를 보자마자 그것들을 보여주는 프로그램을 작성하고 싶어할 겁니다. 아마도 `Label`의 `Text`속성을 이용해서 색상을 인지한다거나 `TextColor` 속성을 이용해서 실제 색깔을 보여주는 식이겠지요.

비록 당신이 `FormattedString` 객체를 사용해서 `Label` 하나로 작업을 할 수 있다손 치더라도, 차라리 `Label` 여러개로 작업하는 것이 훨씬 편합니다. 이렇게 `Label` 객체 여러개를 사용한다는 것은 화면에 이 `Label` 객체 모두를 어떤 식으로든 보여줘야 한다는 것이기도 합니다.

`ContentPage` 클래스는 `View` 타입의 `Content` 속성을 정의합니다. 이 `View` 타입은 오직 객체 하나만을 설정할 수 있습니다.  