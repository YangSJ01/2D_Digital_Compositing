# week12
> ### Particle Environment in Nuke
[참고영상1](https://learn.foundry.com/course/4129/view/particle-environments-in-nuke)
* card 로 하는 방법보다 이 방법이 더 효율적일 수 있다.

> ### Particle in nuke
* 파티클 노드는 연기, 안개, 떨어지는 눈, 폭발 및 거품과 같은 것을 만들 수 있다. 다양하게 응용도 가능하다.
    * 1. ParticleEmitter 노드를 만들고 뷰어에 연결
    * 2. 방출 소스와 파티클 표현을 ParticleEmitter 의 방출 및 파티클 입력에 연결
    * 3. ParticleEmitter 속성 패널에서 파티클의 수명, 속도 및 기타 기본 속성을 수정
    * 4. 다른 파티클 노드를 ParticleEmitter의 출력에 연결
    * 5. 필요한 경우 다시 계산할 필요 없이 다시 읽을 수 있도록 입자 시뮬레이션을 캐시

[참고자료1](https://learn.foundry.com/nuke/content/comp_environment/particles/creating_3d_particles.html)
