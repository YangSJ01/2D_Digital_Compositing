# week4
> ### Merge Operations
* 합성 알고리즘
--------------------
* atop
    * Ab+B(1-a)
    * b가 a를 덮은 채로 보여짐
* average
    * (A+B)/2
    * 두 이미지의 평균, 원본보다 어두워짐
* color-burn
    * darken B towards A
    * B가 A의 휘도에 영향을 받아서 어두워짐
* color-dodge
    * brighten B towards A
    * B가 A의 휘도에 영향을 받아서 밝아짐
* conjoint-over
    * A+B(1-a/b), A if a>b
    * over 연산과 유사, 겹치면 a가 위로 보이고 약간 투명한 경계선 생성
* copy
    * A
    * A만 표시
* difference
    * abs(A-B)
    * 유사한 이미지 비교용으로 사용
* disjoint-over
    * A+B(1-a)/b, A+B(1-a)/b,
    * over 연산과 유사, 안겹친다고 가정해서 약간 투명한 경계선 생성
* divide
    * A/B, 0 if A<0 and B<0
    * 곱하기 취소할 때 사용
* exclusion
    * A+B-2AB
    * 살짝 흐리게 겹쳐짐
* from
    * B-A
    * b에서 a를 뺌
* geometric
    * 2AB/(A+B)
    * 두 이미지 평균
* hard-light
    * multiply if A<0.5, screen if A>0.5
    * a가 밝고 선명한 빛이 되고 b는 거기에 비춰지는 형태
* hypot
    * sqrt (A*A+B*B)
    * plus,  screen operations와 유사, 밝기 = 플러스 < hypot < 스크린오퍼레이션
    * screen 대신 사용 가능, 반사 추가에 유용
    * 1 이상의 값으로 작동함
* in
    * Ab
    * 매트 결합에 유용
* mask
    * Ba
    * a의 알파와 겹치는 b 부분만 표시
* matte
    * Aa+B(1-a)
    * a가 b위로 보여짐
* max
    * max (A,B)
    * 머리카락 같은 것에 유용, 겹치는 부분이 서로 합쳐지면서 반투명해짐
* min
    * min (A,B)
    * 겹치는부분만 최소로 보임
* minus
    * A-B
    * a에서 b뻄
* multiply
    * AB, A if A<0 and B<0
    * 두 이미지 겹쳐짐
* out
    * A(1-b)
    * b의 알파와 겹치지 않는 a부분만 보임
* over
    * A+B(1-a)
    * 기본. b위에 a
* overlay
    * multiply if B<0.5, screen if B>0.5
    * a가 b를 밝게함
* plus
    * A+B
    * 진짜 그대로 합쳐짐. 픽셀값이 1보다 커질 수 있어서 레이저빔합성에만 추천. 매트 합성에는 비추
* screen
    * A or B ≤1? A+B-AB: max(A,B)
    * plus와 유사. 대신 매트에도 레이저 빔에도 유용함
* soft-light
    * B(2A+(B(1-AB))) if AB<1, 2AB otherwise
    * 하드 라이트 약한 버전
* stencil
    * B(1-a)
    * out의 역. b에서 a알파랑 안겹쳐진 부분만 표시됨
* under
    * A(1-b)+B
    * over의 역. b가 a위에
* xor
    * A(1-b)+B(1-a)
    * 이미지가 겹치지 않는 부분에 a,b 모두 표시
    
    [출처](https://learn.foundry.com/nuke/13.0/content/comp_environment/merging/merge_operations.html)
