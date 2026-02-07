![Near Catch](/media/post/Project_NearCatch/NearCatch_Banner.png)

## :sparkles: Project Info
* * *
- **Near Catch** : 관심사를 공유하며 친해지는 아이스브레이킹 앱
- 개발 기간 : 2022.05.16 ~ 2022.06.19

## :open_book: Description
* * *
> WWDC20 에서 발표된 **Nearby Interaction** 기술을 사용한 어플리케이션입니다.  
Multipeer Connectivity를 통해 동일한 WiFi 환경, 또는 Peer-to-Peer WiFi, 블루투스를 통해 근처 주변 디바이스와 서로의 관심사를 비교하고, 일치하는 항목이 3개 이상일 때 진동으로 앱 사용자에게 알려줍니다. 두 사람이 가까이서 스마트폰을 서로 교차하면 공통 키워드가 서로의 스마트폰에 나타나며 정보가 공유됩니다.  

1. For What **Situation**
    - 다수의 아이폰 사용자가 처음 만나 어색한 자리
    - 애플 아카데미의 각종 행사
    - iOS 개발자 컨퍼런스
    - **WWDC**

2. **Who** it's for
    - 애플 아카데미에 입학해 처음 보는 주니어, 시니어 러너
    - 애플 관련 컨퍼런스에 참석한 개발자들
    - 평소에 다른 사람들과 친해지고 싶지만 대화주제를 몰라 어려워했던 아이폰 사용자들
    - 더 많은 사람들과 쉽게 친해지고 싶은 아이폰 사용자들


## :pushpin: Features
* * *
- 프로필 등록 : 닉네임, 사진, 관심사 등을 등록하고 수정
- 내 주변 어플 사용자 수 확인 : 내 주변 어플을 통해 탐색 중인 인원 수 표시
- 햅틱 알람 : 공통 관심사가 있는 사람이 주변에 오면 심장 소리 진동 알람
- 공통 관심사 확인 : Bump Action을 통해 상대방과 나의 공통 관심사 키워드 확인


## :pencil2: Contributors
* * *
- **Apple Developer Academy @ POSTECH** - Team NearCatch
- [@김예훈](https://github.com/eraser3031) | [@류현선](https://www.github.com/hs-ryu) | [@이준영](https://github.com/User-Lawn) | [@조현민](https://github.com/Tempnixk) | [@최원혁](https://github.com/DevLuce) | [**@황찬기**](https://github.com/DevMizeKR)


## :wrench: Dev Environment
* * *
- Dev Environment
    - OS : MacOS(M1Pro)
    - IDE : Xcode 13.4.1
- Tech Stack
```Swift
import SwiftUI
import UIKit
import NearbyInteraction
import MultipeerConnectivity
import Lottie
import CoreData
import CoreMotion
import CoreHaptics
```


## :movie_camera: Demo
* * *
<iframe
  src="https://www.youtube.com/embed/bBylSazJQlQ?si=sk-807NQQHbuAuLD"
  title="NearCatch Demo Video"
  frameborder="0"
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
  allowfullscreen>
</iframe>

<iframe
  src="https://www.youtube.com/embed/0zftlcXqkXs?si=G-Sb-4JAV4SUDMeg"
  title="NearCatch Simulation Video"
  frameborder="0"
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
  allowfullscreen>
</iframe>


## :camera: Screenshots
* * *

| 닉네임 설정 | 관심사 저장 | 메인 화면 |
|:---:|:---:|:---:|
|![Screenshot 01](/media/post/Project_NearCatch/NearCatch_Screenshot_01.png)|![Screenshot 02](/media/post/Project_NearCatch/NearCatch_Screenshot_02.png)|![Screenshot 03](/media/post/Project_NearCatch/NearCatch_Screenshot_03.png)|

<br>

| 탐색 중 | 탐색 완료 | 공통 관심사 |
|:---:|:---:|:---:|
|![Screenshot 04](/media/post/Project_NearCatch/NearCatch_Screenshot_04.png)|![Screenshot 05](/media/post/Project_NearCatch/NearCatch_Screenshot_05.png)|![Screenshot 06](/media/post/Project_NearCatch/NearCatch_Screenshot_06.png)|


## :link: Links
* * *
- [Near Catch | GitHub Repository](https://github.com/DevMizeKR/MC2-Team13-NearCatch)