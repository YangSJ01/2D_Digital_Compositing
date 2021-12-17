# week6
> ### Grade
* 픽셀을 샘플링해 흰색, 검은색 점을 정의하는 방식으로 이미지의 노출을 조절할 수 있다.
    * Ctrl + 클릭 = 단일 픽셀 샘플링
    * Ctrl + Shift + 드래그 = 픽셀 영역 샘플링
    * Ctrl + Alt + 클릭 = 노드의 출력을 보는 동안 노드의 입력에서 단일 픽셀 샘플링
    * Ctrl + Alt + Shift + 드래그 = 출력을 보면서 노드 입력에서 픽셀 영역 샘플링
    * Ctrl + 오른쪽 클릭 = 픽셀선택 취소
* black point/white point
가장 어두운 색과 가장 밝은 색을 선택. 입력된 값은 0 또는 1이 된다.
* Lift & Gain/Multiply
Lift = destination black, Gain = destination white / Multiply는 단순한 곱셈
* Offset
단순한 추가. 범위의 모든 값을 같은 양만큼 올리거나 내림.
* Gamma
곧은 선이 아니라 곡선으로 휘게 하는 것. 흑백 값을 건드리지 않고 어둡게하거나 밝게 할 수 있음.
* Clamping
경사도를 이용하여 값을 리매핑
* Demonstration

[참고1](https://learn.foundry.com/nuke/content/reference_guide/color_nodes/grade.html)
[참고2](https://www.chrisbturner.com/blog/nukes-grade-node-demystified)

> ### Color correct
* 대비, 감마, 게인 및 오프셋을 빠르게 조정하는 데 사용된다.
    * ColorCorrect 노드 > Range tab
    * 하이라이트는 흰색, 중간 색은 회색, 그림자는 검은색으로 표시됨.
    * 녹색과 자홍색 영역은 두가지 범위가 혼합된 영역을 나타냄.

[참고1](https://learn.foundry.com/nuke/content/reference_guide/color_nodes/colorcorrect.html)
[참고2](http://defocusedeye.com/2014/01/color-nodes-grade-colorcorrect-colorlookup-hsvtool-huecorrect/)
