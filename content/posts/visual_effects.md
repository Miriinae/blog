---
title: "시각 효과 모음"
date: 2021-01-17T14:52:23+09:00

tags: "visual_effect"
categories: ""
---

착시, 시각 효과, 촬영 기법 등 여러가지 시각적인 효과들을 모아 보았다.
밑의 효과들을 나중에 glsl, blender등으로 구현할 예정이다.
# 작성중, 후에 효과들을 분류할 예정.

## Visual artifacts
시각 아티팩트. '아티팩트'는 '왜곡'이라고 번역하는 것이 가장 적절한듯 하다.
## Optical illusion
optical illusion(착시)는 이미지가 실제 사물의 모습과 다르게 보이는 것을 뜻한다.



## Compression artifact 
compression artifact(압축 왜곡)은 이미지, 오디오, 비디오 파일등을 손실압축을 했을 때 나타날 수 있는 눈에띄는 왜곡을 말한다.
## GPU malfunction
gpu malfunction(gpu 오작동)은 Hardware malfunction의 일종으로, 하드웨어의 물리적 손상을 포함한 오작동으로 인해 왜곡이 나타나게 된다.
## Software malfunction
software malfunction(소프트웨어 오작동)은 비디오나 오디오를 인코딩 하는 등의 과정에서 알고리즘의 결점으로 발생할 수 있다.
## Aliasing
Aliasing은 위신호라고 하며, 위신호 현상은 신호가 샘플로부터 다시 구성될 때 결과가 원래의 현속적인 신호와 달라지는 일그러짐을 가리킨다. 계단 현상으로 부르기도 한다.
## Anti-Aliasing
Anti-Aliasing, AA로 부르기도 하는 위신호 제거는 높은 해상도의 신호를 낮은 해상도에서 나타날 때 생기는 계단 현상을 최소화하는 방법이다.
## Rolling Shutter
rolling shutter(롤링 셔터)는 카메라가 사진을 캡쳐할 때 한번에 하나의 이미지 전체를 찍는 것이 아니라 빠르게 가로나 세로로 시간차를 두고 찍는 방법이다. 이는 하나의 사진이 같은 시간에 찍히지 않았다는 것을 의미하며, 이 특성으로 인해 빠르게 움직이는 물체나 빠른 불빛 깜빡임은 왜곡을 만들어낸다.
## Image noise
Image noise(이미지 잡음)는 이미지에서 나타나는 랜덤한 빛이나 색 정보들을 말한다. 디지털 카메라나 스캐너와 같은 장치에 의해 발생할 수 있다.
## Screen-door effect
screen-door effect(스크린도어 효과)는 디스플레이에서 미세한 선의 픽셀들이 보이는 것이다.
## Ghosting
Ghosting(고스트 현상)은 tv에서 ghost라 부르는 전달된 이미지의 복제본이 원래의 이미지와 겹치는 현상을 말한다.
## Distortion
distortion(디스토션)은 영상이나 오디오의 신호의 모양을 변화시키는 것이다.
## Screen tearing
screen tearing(스크린 티어링)이란 디스플레이가 한 스크린에 여러 프레임을 표시할 때 생기는 현상이다.
## Moiré pattern
Moiré pattern(무아레 패턴)은 간섭 무늬, 물결 무늬, 격자 무늬라고도 하며, 비슷한 규칙적인 무늬를 겹칠 때 나타난다.
## Maze artifacts
maze artifacts는 센서가 세부사항을 다룰 수 있는 한계치를 넘을 만큼 평행선들이 있을 때 나타난다.
## Colour banding
colour banding(컬러 밴딩)은 색을 표시할 때 부정확한 색이 나타나는 것을 말한다.
## Posterization
posterization은 연속적인 색의 그라디언트가 더 적은 톤으로 바뀔 때 나타나는 현상이다.
## Ringing artifacts
ringing artifacts은 급격한 신호의 변화가 있는 부분에서 나타난다.
## Diffraction spike
diffraction spike는 밝은 광원에서 방사하는 선들로 나타난다.
## Pixelization
pixelization(mosaic, 모자이크)는 이미지의 일부를 눈에띄게 낮은 해상도로 바꾸는 기법이다.
## Chromatic aberration
chromatic aberration(색수차)은 렌즈에서 같은 지점에 모든 파장의 색의 초점이 맺히지 않는 현상이다. 
## Chromostereopsis
chromostereopsis는 주로 빨강-파랑이나 빨강-초록등의 2개의 색을 지닌 이미지에서 깊이가 느껴지는 착시현상이다.
## Stereoscopy
stereoscopy는 이미지에서 깊이의 착시를 느끼게 하는 기술이다. 이러한 기술을 적용한 이미지를 stereogram이라 한다.
## Depth perception
depth perception(깊이 감각)은 3차원 세계와 물체간의 거리를 인지하는 시각 능력이다.
## Kinetic depth effect
kinetic depth effect란 3차원 물체가 움직이는 것으로 인해 인지할 수 있다는 것을 말한다.
## Autostereogram
한국어로 매직아이라고도 불리는 autostereogram는 2차원 이미지에서 3차원 장면을 보는 듯한 착시를 만들어내는 단일 이미지의 stereogram이다.
## Lenticular printing
lenticular printing(렌티큘러 인쇄물)은 이미지를 깊이감이 있게 하거나 다른 각도에서 다르게 보이게 하는 기술이다.
## Wiggle stereoscopy
wiggle stereoscopy는 stereogram의 왼쪽과 오른쪽의 이미지를 번갈아가며 표시해 입체감을 불러 일으킨다.
## Panorama, Panoramic photography
panorama(파노라마)는 넓은 각도의 시야를 담는 이미지이다.
## Image stitching
image stitching은 여러개의 사진을 겹쳐서 파노라마를 만들거나 높은 해상도의 이미지를 만드는 과정이다.
## Optical flow
optical flow는 물체, 표면이나 선의 움직임의 패턴을 말한다.
## Structure from motion
structure from motion(SfM)은 움직임과 연결된 연속의 2차원의 이미지에서 3차원 구조를 파악하는 기술이다.
## Binocular vision
binocular vision은 두 개의 눈이 하나의 3차원 이미지를 같은 방향에서 볼 수 있는 시각이다.
## Motion estimation
motion estimation은 하나의 2차원 이미지에서 다른 이미지로의 이동을 표시하는 움직임 벡터를 결정하는 과정이다.
## Moving object detection
moving object detection은 연속적인 동영상에서 움직이는 물체를 감지하는 기술이다.
## Video tracking
video tracking은 움직이는 물체를 계속해서 추적하는 과정이다.
## Teknomo-Fernandez algorithm
TF algorithm은 주어진 동영상에서 배경을 추출하는 효과적인 알고리즘이다.
## Image registration
image registration(영상 정합)은 다른 종류의 영상들을 하나의 좌표계로 변환하는 처리기법이다.
## Spherical aberration
spherical aberration(구면수차)는 구면을 가진 광학 시스템에서 발견된다.
## Soft focus
soft focus(연초점)은 렌즈가 구면수차로 인해 흐려진 상을 형성하는 것이다.
## Depth of field
DOF(피사계 심도)는 한 사진의 초점이 맞은것으로 인식되는 범위이다.
## Deep focus, Shallow focus
deep focus는 넓은 피사계 심도를 사용한 촬영 기법이다. 반대로 shallow focus는 작은 심도로 촬영하는 기법이다.
## Bokeh
bokeh(보케)는 초점 밖에서 흐리게 나타나는 예술적 표현이다.
## Zernike polynomials
zernike polynomials은 단위 원판에서 .?. 방정식이다.
## Defocus aberration
defocus aberration은 초점 밖에 있는 영상에서 나타나는 광학 수차이다.
## Purple fringing
purple fringing은 흐릿한 보라색으로 불리는 광학 수차 현상이다.
## Motion blur
motion blur는 연속한 그림들이나 이미지에서 빠르게 움직이는 물체에 의해 나타나는 뚜렷한 줄무늬이다.
## Backscatter
backscatter는 사진을 찍을 때 카메라의 플래시가 초점에 맞지 않은 먼지, 물방울같은 입자들에 서 반사되어 나타나는 광학 현상이다.
## Image warping
image warping(이미지 변형)은 영상의 형태를 왜곡하는 방법이다.
## Anamorphosis
anamorphosis는 특정한 장치를 통해서 원래의 이미지를 볼 수 있게 하는 왜곡된 투영(?)이다.
## Visual snow
visual snow는 전체나 일부 시야에서 희거나 까만색의 점들을 보는 상태이다.
## Entoptic phenomenon
entoptic phnomenon은 눈 자체가 시각 효과의 근원이 되는 것이다.
## Scan line
scan line은 하나의 선으로, CRT나 모니터에서 나타난다.
## Raster scan
raster scan은 이미지를 캡쳐하고 tv에서 재구조화 할때 나타나는 사각형의 패턴이다.
## Screen burn-in
screen burn-in(번인)은 CRT, OLED등의 디스플레이에서 픽셀을 균일하지 않게 사용했을 때 그 부분이 변색되는 현상이다.
## Halftone
halftone(망점)이란 점을 사용하여 그 크기나 간격을 달리해 그라디언트와 같은 효과를 낸다.
## Glitch art
glitch art는 디지털이나 아날로그의 에러들을 예술적인 목적으로 사용하는 예술이다.
## Data mosh
data mosh(datamoshing)은 비디오나 이미지의 데이터를 변형하는 것이다.
## VJing
VJing은 리얼타임 비주얼 퍼포먼스의 광범위한 명칭이다.
## Morphing
morphing(모핑)은 하나의 형태가 전혀 다른 이미지로 변화하는 기법이다.
## Dither
dithering(디더링)은 제한된 색을 이용하여 음영이나 색을 나타내는 것이며, 여러 색을 최대한 맞추는 과정이다.
## Kaleidoscope
kaleidoscope(만화경)은 다른 각도로 기울어진 여러 개의 거울을 두어 여러번의 반사로 대칭적인 패턴을 나타내는 장치이다.
## Generation loss
generation loss는 데이터를 전달하거나 복사함으로서 데이터가 변형되는 것이다.
## Barrier-grid animation and stereography
Barrier-grid animation
## Interlaced video
interlaced video는 하나의 영상을 홀수와 짝수 가로줄로 나눠 번갈아가며 표시하는 방식이다.
## Zoetrope
zoetrope(조이트로프)는 착시 원리를 활용한 애니매이션 장난감이다.
## Blend mode
blend mode는 디지털 이미지 편집에서 두 개의 레이어가 혼합되는 방식을 결정한다.

## 이미지 촬영 장치
### Camera
### CCTV
### Infrared Camera
### Night Vision
### Telescope
### Radio Telescope
### Microscope
### Electron Microscope
### MRI
### X-ray(computed tomography)

## 자료 출처
+ [Visual artifact](https://en.wikipedia.org/wiki/Visual_artifact)
+
