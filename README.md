# app_UI design_portfolio 🌟
**어플리케이션 이름: 바푸리**

> [ 바푸리 캐릭터와 함께 하는 감성 넘치는 데일리 케어 앱]

<br>

## 🚀 앱 프로토타입 (직접 눌러보세요!)

아래 링크를 클릭하면 제가 디자인한 앱을 실제처럼 직접 눌러보고 경험할 수 있습니다.

**[Figma 프로토타입 링크 바로가기](https://www.figma.com/proto/KPxWMlNgh6AkNciOc1YeFi/%EC%95%B1-%EB%94%94%EC%9E%90%EC%9D%B8?page-id=0%3A1&node-id=84-2127&viewport=71%2C915%2C0.29&t=9yVymBgxWuDPM6yF-1&scaling=scale-down&content-scaling=fixed&starting-point-node-id=34%3A5&show-proto-sidebar=1)** <br>

## 핵심 기능

제가 디자인한 앱의 핵심 기능을 소개하겠습니다.
- **어플리케이션의 핵심 설정**
  - 하나의 **미션**이라고 생각할 수도 있을 것 같습니다. **기상에 성공**하거나 **일기 작성**을 해냈을 때 각각 2 포인트 씩 적립됩니다. 포인트를 사용해서 바푸리 캐릭터를 예쁘게 꾸밀 수 있다는 설정을 해보았습니다.(이 점은 따로 구현하진 않았습니다.)
  - 두번째는 바로 **음악 설정**입니다. 전날 일기를 작성한 후 다음 날 아침에 듣고 싶은 노래를 검색하고, 유튜브 링크를 저장해둡니다. 아침이 되고 기상을 위한 미니 게임이 끝나면 이를 틀어주는 시스템입니다.
- **날씨 인터페이스**
  - 홈 화면에는 바푸리 캐릭터, 귀여운 문구와 함께 오늘의 날씨에 따라 바뀌는 인터페이스가 나타납니다.
- **알람**
  - **기상 알람**: '깨기' 버튼을 누르면 파이썬으로 만들었던 반응 속도 게임을 해야 합니다. (일종의 기상 미션!) 게임을 끝내면 기상에 성공했다는 의미에서 2포인트가 적립되고, 어젯밤 선택했던 음악이 유튜브 링크를 타고 들어가집니다. '끄기' 버튼을 누르는 경우 포인트가 적립되지 않고 알람이 꺼집니다.
  - **취침 알람**: 취침 전 일기 작성 및 음악 선정을 위해 선택적으로 활성화할 수 있습니다.
  - **기록 보기**: 매일 기상의 성공 여부, 그 날의 선곡, 일기 작성 여부에 대한 기록을 확인할 수 있습니다.
- **일기**
  - 일기를 작성하면 2 포인트가 적립되고, 음악 검색 탭이 나오면 다음 날 듣고 싶은 음악을 검색 후 그 링크를 저장할 수 있습니다.
- **외출 알림**
  - 외출 시간에 알람을 맞춰놓으면 날씨에 대한 알림과 함께 알람이 울립니다. 비가 오는 날 우산을 챙기라는 메시지 등을 통해 불상사를 피할 수 있습니다!


<br>

## 🎬 핵심 인터랙션 (MP4)
<div style="display: flex; flex-wrap: wrap; gap: 20px;">

  <div>
    <video src="https://github.com/user-attachments/assets/424a4f32-33ef-4861-a15c-e24e40c56ed8" autoplay loop muted width="300"></video>
    <p align="center">날씨 인터페이스</p>
  </div>

  <div>
    <video src="https://github.com/user-attachments/assets/59a4400f-3613-4a42-b7e4-937a944c164d" autoplay loop muted width="300"></video>
    <p align="center">알람 메뉴</p>
  </div>

  <div>
    <video src="https://github.com/user-attachments/assets/8f65294f-afd7-43bc-bccb-60ed45812fe4" autoplay loop muted width="300"></video>
    <p align="center">기상 알람 시안(끈 경우)</p>
  </div>

  <div>
    <video src="https://github.com/user-attachments/assets/00b9e10e-f9d5-41e0-a5b5-b44c47e3df99" autoplay loop muted width="300"></video>
    <p align="center">기상 알람 시안</p>
  </div>

  <div>
    <video src="https://github.com/user-attachments/assets/7a27e12c-a1e9-4af6-8bb5-1581a66c115e" autoplay loop muted width="300"></video>
    <p align="center">일기 메뉴</p>
  </div>

  <div>
    <video src="https://github.com/user-attachments/assets/ff3986b1-cd4f-45a7-8fdb-3f0384ec4351" autoplay loop muted width="300"></video>
    <p align="center">일기-음악 검색</p>
  </div>

  <div>
    <video src="https://github.com/user-attachments/assets/e569e2df-3747-45ee-987c-a8eda3740b6b" autoplay loop muted width="300"></video>
    <p align="center">외출 알림 메뉴</p>
  </div>

  <div>
    <video src="https://github.com/user-attachments/assets/a2b47160-31bf-4674-bc98-91ff34044ade" autoplay loop muted width="300"></video>
    <p align="center">외출 알람 시안</p>
  </div>

</div>

<br>

---

## 📖 프로젝트 상세 설명

### 1. 프로젝트 목표

* 무엇보다 중요한 것은 다양한 기능이 **서로 유기적으로 연결되어** 사용자에게 도움을 줄 수 있으면 좋을 것 같다는 생각이었습니다.
* 개인적으로 음악이 사람에게 미치는 영향이 크다고 생각합니다. 그래서 안그래도 일어나기 괴로운 아침에 일어났을 때, 듣고 싶은 음악을 들음으로서 소소한 행복을 느낄 수 있지 않을까 생각하였습니다.
* 또한 저는 평소에 허둥지둥 나가는 편이라 비 오는 날 우산을 까먹고 나가는 경우가 꽤 많은데, 저와 비슷한 사람들이 외출 알림 기능을 사용하면 매우 유용할 것 같습니다.
* 일기 기능을 활용해 소소하게 감성을 챙기고자 했습니다.
* '포인트 적립' 시스템은 바푸리 캐릭터에 대한 애착을 키울 수 있고, 그를 통해 건강한 생활( 아침에 잘 일어나기, 하루를 돌아볼 수 있는 일기 쓰기)을 루틴처럼 만들 수 있습니다.
* (기능이 꽤 많아서 어려울 것 같기도 하지만 이를 실제로 구현해보고 싶습니다!)

### 2. 디자인 컨셉

* 눈에 편안한 색과 폰트를 사용
  - 이용자가 어플리케이션을 사용할 때 편안함과 행복감을 느낄 수 있으면 좋겠다는 마음으로 이들을 사용했습니다!

### 3. 사용한 툴

* Figma
* Procreate
