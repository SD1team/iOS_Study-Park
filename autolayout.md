#iOS AutoLayout
  
**constraints-based layout system 제약 기반의 레이아웃 시스템**  
View 들간의 상호적인 관계를 정의하는 유저 인터페이스  
  
개발자는 화면의 크기와 디바이스에 따라 적절하게 바뀌는 적응형 인터페이스를 만들 수 있다.  
다양한 기기들의 각각 다른 해상도에 따라서 View의 크기나 위치를 자동으로 조절해준다.   
개발자는 View들에 Constraints(제약)을 걸어둔다. AutoLayout System은 그 제약에 따라 뷰드르이 크기와 위치를 정한다.  

(새 프로젝트 생성 single view application iOS app templete > storyboard 열기)  
**storyboard 오른쪽 하단의 4가지 버튼**  
1) **Align** 정렬 제약 생성 (ex. view들을 왼쪽정렬 )  
2) **Pin** 공간 제약 생성 (ex. 다른 view와의 거리 제약)  
3) **Issues** 레이아웃 이슈 해결  
4) **Resizing**  

AutoLayout은 control + drag를 사용  

**Constraints Line Color**  
Orange Color Line : 부족한 제약  
Blue Color Line : 적절한 레이아웃  
  
제약 생성 후, Interface Builder outline view 의 red arrow > 충돌이나 애매한 이슈  
arrow 클릭 시, 이슈 목록을 볼 수 있다.  
  
size조절탭 > constraints 섹션에서 추가된 모든 제약들을 확인할 수 있다.   