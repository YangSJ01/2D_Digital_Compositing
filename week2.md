# 2D디지털합성 - week2
> ### CMYK, RGB
* CMYK
    = Cyan Magenta Yellow Key(Black). 마젠타, 시안, 노랑, 검정을 원색으로한 감산혼합의 색 모형이다. RGB나 HSB보다 표현 가능한 색이 적다.(ex. 보라색)
    주로 인쇄에서 사용된다.
 * RGB
    = Red Green Blue. 빨강, 초록, 파랑 세 종류의 광원을 이용한 가산혼합으로 색을 표현하는 방식이다.
    RGB 가산혼합의 종류로는 sRGB, 어도비 RGB등이 있다. 포토샵 등에서 기본으로 지원하는 채널이다.
![Alt text](/path/to/cmyk_rgb.jpg)
> ### RGBA
* RGBA는 빨간색, 녹색, 파란색, 알파를 뜻하며, RGB에 알파채널이 추가된 형태이다.
    알파영역을 통해 투명/불투명 정보를 추가해 이미지의 결합을 가능하게 만들었다.
>    > #### alpha Channel
* 색상의 투명도/불투명도를 제어한다.
        소스 색상의 알파값을 이용해 다른 색상과 혼합될 떄의 결과 색상을 결정한다.
        투명하면 다른 색상(배경)이 보이고, 불투명하면 소스 색상이 보인다. 값이 그 사이에 있다면 반투명 효과를 볼 수 있다.
        또한, 알파 채널은 주로 알파 혼합 및 알파 합성에 사용된다.
> ### Color Space
* 우리가 보는 색을 명도, 채도, 색상을 이용해 3차원 공간에 표현한 것이다.   대부분의 촬영 장치나 출력 장치로는 표현할 수 없는 방대한 색 공간이 존재한다.
>    > #### Gamut
* 색영역(Gamut)은 원본의 색상을 화면에서 어느정도 표헌할 수 있는지를 수치화한 것이다. 디스플레이에서 표현 가능한 색상의 범위를 뜻한다.
--------------------------------------------------------------------------------------
> ##### 출처
[CMYK](https://ko.wikipedia.org/wiki/CMYK)
[RGB](https://ko.wikipedia.org/wiki/RGB#RGB_%EC%B1%84%EB%84%90)
[RGBA](https://en.wikipedia.org/wiki/RGBA_color_model)
[Alpha Channel](https://www.techopedia.com/definition/1945/alpha-channel)
[Color space](https://www.khanacademy.org/computing/pixar/color/color-space/v/color6-final)
[Gamut](https://en.wikipedia.org/wiki/Gamut)
[cmyk&rgb](http://snq.co.kr/guides/basic/index4.php])
