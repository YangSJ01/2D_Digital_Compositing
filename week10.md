# week10
> ### EXR format
* OpenEXR 비트 맵 파일. HDR(High Dynamic Range) 이미지 파일 형식이다.
    * 고품질 이미지를 저장할 수 있고, 무손실과 손실 압축 둘다 가능하다.
    * 여러 레이어로 저장할 수 있다.
    * 높은 휘도 범위와 색상
* 사진 편집, 시각 효과, 애니메이션 프로그램 등에서 사용된다.

[참고자료1](https://www.lifewire.com/exr-file-2621157)
[참고자료2_openEXR](https://www.openexr.com/)
> ### AOV
* Arbitrary output variables (AOVs) : 임의 출력 변수
* 렌더 할 때, 셰이더 또는 렌더러의 데이터를 출력해 합성 중에 추가 옵션을 제공한다.

[참고자료3](https://learn.foundry.com/katana/Content/ug/rendering_scene/define_aov_output.html)
> ### Raytracing / Scanling render differnce
* Raytracing : 픽셀 하나하나를 통과하는 광선이 있다 가정하고 광선(ray)을 역추적(trace)하는 방식
    * 빛을 자세하게 표현할수록 리얼리티가 커지고, 표현력이 풍부해진다.
    * 단, 입자 하나하나를 전부 계산해야하기 때문에 렌더링 시간이 많이 소요된다.

[참고자료4](https://ko.wikipedia.org/wiki/%EA%B4%91%EC%84%A0_%EC%B6%94%EC%A0%81)
* Scanling render(Scanline render) : 스캔하는 선이 폴리곤과 스캔 선의 교차점을 이용해 계산하는 방식
    * 주 메모리 정점에 다시 엑세스하지만 않는다면, 속도가 많이 향상된다.
[참고자료5](https://en.wikipedia.org/wiki/Scanline_rendering)
>> 비교
* 속도 : Raytracing < Scanline render
    * 스캔라인이 기본이고 레이트레이싱이 보조 역할.
* Raytracing-수학적 객체와 함께 / Scanline render-폴리곤과 함께 작동한다.
[참고자료6](https://www.cgvizstudio.com/difference-between-scanline-rendering-and-raytracing-rendering/)
> ### Visual Language
>> #### Value Contrast
>>> ###### Contrast
* 사진의 가장 밝은 부분과 가장 어두운 부분의 차이 정도
>>> ###### Value
* 색의 상대적 명암 / 명암과 관련하여 그림의 한 부분과 다른 부분의 관계
