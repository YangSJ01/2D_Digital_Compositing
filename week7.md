# week7
> ### Tracker
* 이미지의 위치, 회전 및 크기에서 움직임 데이터를 추출할 수 있다. 또한, 데이터를 적용해 다른 요소로 변환하고 이동시킬 수도 있다.

[참고1](https://learn.foundry.com/nuke/content/reference_guide/transform_nodes/tracker.html)
--------------------------
> ### 1 point tracking
* 이미지의 원근이 거의 변경되지 않은 상태에서 x축과 y축 위치 추적
> ### 2 point tracking
* 수평 및 수직 위치 추적에다가 회전(z축)까지 수행함.
> ### 3 point tracking
* z축의 정확도를 높이기 위해 추가 추적 데이터와 함께 2point tracking의 장점 포함되어있음.
> ### 4 point tracking
* 4개의 트랙과 CornerPin2D 노드를 사용하여 추적하는 기능의 점으로 다른 요소를 왜곡하고 일치 이동시킬 수 있음.
[참고2](https://learn.foundry.com/nuke/content/tutorials/written_tutorials/tutorial2/1_2_3_4_point_tracks.html)
