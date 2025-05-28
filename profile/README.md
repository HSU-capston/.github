## Sporty Up
> Hansung University x Qualcomm - Capston design 

![KakaoTalk_20250429_185317295](https://github.com/user-attachments/assets/8f247b34-db36-4c8e-bbae-c82691c88b2c)

<br/><br/>

## 🍨 *****Contributors*****
| 손주완 <br> [@vvan2](https://github.com/vvan2) | 임승택 <br> [@SeungtaekLim](https://github.com/SeungtaekLim) | 장우진 <br> [@Santoragi](https://github.com/Santoragi) | 황준현 <br> [@Hwnsgus](https://github.com/Hwnsgus) |
|:---:|:---:|:---:|:---:|
| <img width="150" src="https://avatars.githubusercontent.com/u/113279387?v=4"/> | <img width="150" src="https://avatars.githubusercontent.com/u/172005208?v=4"/> | <img width="150" src="https://avatars.githubusercontent.com/u/147162427?v=4"/> | <img width="150" src="https://avatars.githubusercontent.com/u/90452546?v=4"/> |
<br>

## 📄 *****Description*****
**Sporty-UP** is a mobile-based system for real-time posture assessment and feedback, developed using Qualcomm AI Hub. It utilizes on-device AI to provide instant posture corrections during physical activities, and integrates server-based analysis for high-precision results. The system also features a community platform where users can share experiences and feedback. This hybrid approach ensures efficient performance on mobile devices, offering a convenient, real-time solution for improving posture and supporting indoor sports activities.

>※ Qualcomm University Relations Platforms Symposium 2025 초청
><br>
>※ 한국디지털콘텐츠학회 2025 하계종합학술대회 논문투고

<br/><br/>

## *****Background*****
최근 인공지능 기술, 특히 딥러닝 기반의 컴퓨터 비전 기술은 다양한 산업 분야에서 혁신적인 변화를 이끌고 있으며, 스포츠 분야에서도 활발히 응용되고 있다. 그중에서도 운동 수행 중의 자세를 정확하게 인식하고 분석하는 기술은 부상 예방, 기술 향상, 운동 효율성 증대 등에서 높은 가치를 지니며, 이에 따라 영상 데이터를 활용한 자세 분석 및 동작 유사도 평가에 관한 시스템 개발이 활발히 이루어지고 있다.
<br/>
<table>
  <tr>
    <td align="center" width="50%">
      <img src="https://github.com/user-attachments/assets/76dbc7c3-f966-4d1b-9859-f24fe2516131" width="450"/><br/>
      <strong>SSTC 모션 애널라이저</strong><br/>
      SSTC가 개발한 스포츠 데이터 분석 소프트웨어<br/>
    </td>
    <td align="center" width="50%">
      <img src="https://github.com/user-attachments/assets/ea26caca-6a55-4ae3-836e-b5424487287a" width="450"/><br/>
      <strong>딥스크라이크 (DeepStrike)</strong><br/>
      Jabbr가 개발한 격투 스포츠용 통계 분석 AI 프로그램<br/>
    </td>
  </tr>
</table>
<br/>
하지만 기존의 시스템들은 스포츠 동작을 정량적으로 분석하거나 실시간 피드백을 제공함으로써, 운동 보조 기술의 정밀성과 유용성을 입증해왔다. 그러나 대부분의 시스템은 단일 디바이스나 서버 중심 구조에 기반하고 있어, 실시간 피드백을 위해 고정된 장비나 고성능 서버에 의존해야 하는 구조적 한계가 존재한다. 이로 인해 실시간성, 접근성, 휴대성 측면에서 사용자 경험이 제한되며, 일반 대중이 활용하기에는 제약이 따른다. 특히 실내 스포츠의 경우 공간 제약이나 장비 설치의 어려움으로 인해, 개인 사용자가 접근할 수 있는 자세 분석 시스템은 매우 제한적이다. 또한 많은 시스템이 분석 결과를 수치나 그래프 형태로만 제공하기 때문에, 운동 초보자가 이를 직관적으로 이해하고 동작을 교정하기 어렵다는 문제도 있다. 따라서 보다 실용적인 자세 분석 시스템을 위해서는 모바일 기기를 활용한 높은 접근성과 실시간 반응성, 그리고 자연어 기반의 직관적인 피드백 제공이 동시에 고려되어야 한다.

<br/><br/>

## *****Abstract*****
이러한 배경을 바탕으로 본 시스템은 모바일 디바이스와 서버를 결합한 하이브리드 구조를 기반으로, 실내 스포츠 환경에서 실시간 자세 분석 및 피드백이 가능하도록 설계되고 구현되었다. 본 시스템은 YOLOv11 객체 탐지 모델과 포즈 추정 모델을 이용해 사용자의 자세를 인식하고, 이를 분석한 결과를 ChatGPT-4 API를 활용하여 자연어로 해석하고 피드백함으로써 직관적인 운동 가이드를 제공한다.

![image](https://github.com/user-attachments/assets/302978a1-6e04-437b-820b-efaaf142bb6c)


본 시스템은 특히 볼링을 사례로 선정하여, 투구 동작의 실시간 분석과 피드백 기능을 모바일 애플리케이션에 구현하였다. 또한 모바일 디바이스에서의 경량화 및 최적화를 통해 추론 속도와 메모리 사용량을 효과적으로 개선함으로써, 실제 환경에서의 실시간 동작 가능성을 확인하였다. 이처럼 본 시스템은 기존 시스템이 갖는 실시간성, 직관성, 범용성의 한계를 극복할 수 있는 실용적인 접근을 제시하며, 향후 다양한 실내 스포츠 종목 및 운동 환경으로의 확장 가능성을 보여준다. 특히 개인 맞춤형 운동 교정, 반복 학습 기반의 자세 개선, 그리고 대규모 언어 모델을 활용한 자연어 피드백 제공이라는 측면에서 기존 시스템과 차별화된 가치를 제공한다.

<br/><br/>

## 🖥️ *****System Structure*****
![2  21조_이미지_주요 적용 기술 및 구조](https://github.com/user-attachments/assets/16e4a05f-0b8c-48c4-8348-b992407617dd)
<br>

Sporty-up 애플리케이션은 다음과 같은 핵심 기능을 포함한다.

● 자동 촬영 및 영상 업로드
<br>
● 분석 결과 수신 및 시각화
<br>
● 사용자 피드백 출력 및 히스토리 관리

애플리케이션은 자동 촬영, 영상 업로드, 분석 결과 수신, 피드백 표시 기능을 통합하여 사용자 친화적인 인터페이스를 제공한다. 시스템은 Flask 기반의 분석 서버와 Spring Boot 기반의 사용자 관리 서버로 구성된 이중 구조로 운영된다.

분석 서버는 Python 기반 Flask 프레임워크로 구성되며, YOLOv11 기반 Pose Estimation 모델을 통해 사용자의 투구 영상을 분석하고 결과를 생성한다. 분석된 결과는 AWS S3에 저장되며, 결과 스코어 및 관절 분석 정보는 사용자에게 제공된다. 한편, Spring Boot 기반 서버는 사용자 인증, 분석 히스토리 저장 및 조회, 사용자 레벨 관리 등의 기능을 담당한다. Spring Boot는 모바일에서 들어온 분석 요청을 Flask 서버로 전달하고, 분석 결과 및 히스토리 관련 데이터는 Spring Boot 서버와 통신하여 연동된다.

<br/><br/>

## 📱 *****Expected screen*****
![2](https://github.com/user-attachments/assets/98656c9d-0256-4eee-ba3d-109b27bcaa36)

주요 개발 기술:
- 모바일 앱 내 데이터 시각화 기능 구현 ( 차트/점수/진행도 시각화 등 )
- 사용자 인증 및 권한 제어 ( 로그인/회원가입 API에 JWT 적용, 사용자 정보 식별 및 접근 제어 )
- 사용자 정보 기반 영상 추천 및 사용자 레벨 기반 피드백 등 개인화된 시스템 구현
- Spring Boot와 Flask 간 비동기 API 통신 구조 설계
- YOLO 기반 자세 추정 모델과 LLM 모델을 활용한 실시간 자세 분석 및 피드백 알고리즘 구현
- Qualcomm AI Hub를 통한 온디바이스 모델 경량화 및 타겟 디바이스 최적화 ( W8A8 양자화 )

<br/><br/>

## ⚙️ *****Score Algorithm*****
![image](https://github.com/user-attachments/assets/fc2e5a1a-28d7-40a4-badb-73125a169059)

모바일 디바이스에서 YOLOv11 Object Detection 모델은 사용자의 투구 시점을 자동 판별하여 촬영 타이밍을 제어하며 서버로 투구 영상을 보내고 서버에서 YOLOv11 Pose Estimation 모델은 프레임별 17개 관절 좌표를 추출한다. 추출된 데이터를 기반으로 어깨 평균 각도 편차, 상체 평균 이동 거리, 손목 누적 이동 거리, 발목 위치 변화 횟수, 사용자 정보를 통해 습득한 사용자의 숙련도등의 지표를 계산하고, 이를 다음과 같은 점수 함수로 종합하여 하나의 스코어로 환산한다.
<br>
<img width="360" src="https://github.com/user-attachments/assets/b76cab43-41bb-422c-bd2f-21def77e155e"/> 
<br>
<img width="360" src="https://github.com/user-attachments/assets/1ac2276e-9a0d-4415-b8a5-2cc8d5521125"/> 
<br>
더 자세한 자세 분석 알고리즘은 (https://github.com/HSU-capston/Back-flask) 에서 확인하실 수 있습니다.

<br/><br/>

## ⚙️ *****Optimization for Mobile Devices*****
모바일 환경은 연산 자원, 메모리 용량, 전력 소비 등의 제약이 존재하므로, 딥러닝 모델의 경량화가 필수적이다. 이에 본 시스템에서는 YOLOv11 Object Detection 모델을 Qualcomm AI Hub를 활용하여 weights와 activation을 각각 8비트 고정소수점과 INT8로 양자화(W8A8)하였고 TensorFlow Lite 형식으로 변환되어 모바일에 최적화되었다. 최적화는 Qualcomm Snapdragon 8 Elite 기반 디바이스(Samsung Galaxy S25)를 기준으로 수행되었으며 최적화 전후의 성능 비교 결과는 다음과 같다.

<br/>

<img width="560" src="https://github.com/user-attachments/assets/47d5328c-be84-496e-9d8e-1ce9393e604c"/> 
<br>

<br/><br/>

## *****Conclusion*****

본 연구에서 개발한 YOLOv11과 ChatGPT-4 기반의 실시간 자세 분석 및 자연어 피드백 시스템은 다양한 기대효과를 지닌다. 먼저, 모바일 환경에 최적화된 설계를 통해 별도의 전문 장비 없이도 실시간 자세 분석과 직관적인 피드백 제공이 가능해져, 사용자는 언제 어디서나 손쉽게 운동 상태를 점검하고 개선할 수 있다. 또한 자동 촬영 및 맞춤형 영상 추천 기능은 사용자의 반복 학습을 효과적으로 지원하며, 운동 데이터를 기반으로 한 개인 맞춤형 콘텐츠 제공을 통해 학습 효율을 극대화할 수 있다.

자연어 기반 피드백 시스템은 사용자가 복잡한 용어나 전문 지식 없이도 쉽게 이해할 수 있는 방식으로 자세 교정 정보를 제공함으로써, 보다 친숙하고 접근성 높은 운동 가이드를 구현한다. 분석 결과는 점수 및 차트 형태로 시각화되어 사용자가 자신의 자세 변화 추이를 한눈에 확인할 수 있어, 자기주도적인 운동 관리와 동기 부여에 기여한다. 나아가 본 시스템은 다양한 스포츠 종목으로의 확장이 가능하도록 설계되어, 향후 더 많은 분야에서 활용 가능성을 지니며 실질적인 운동 효과 향상에 이바지할 것으로 기대된다.

<br/><br/>

## *****Detailed analysis screen*****
![image](https://github.com/user-attachments/assets/cab0cd99-0f7e-46c5-a137-65423d168285)

<br/><br/>

## *****Main Tech Stack & Development Environment*****

- 개발 환경: Android, Windows, Ubuntu (GPU EC2)
- 주요 라이브러리: TensorFlow Lite, OpenCV
- 프레임워크: Spring Boot, Flask, TensorFlow, Qualcomm AI Hub
- 개발 도구: Amazon EC2, Amazon RDS, Amazon S3, Android Studio, VSCode, Swagger

<br/><br/>

## *****Additional*****

| 항목 | 링크 |
|:---:|:---:|
| 📑 Qualcomm University Relations Platforms Symposium 2025 | [Qualcomm_symposium_2025_Sport-up.pdf](https://github.com/user-attachments/files/20391725/Qualcomm_symposium_2025_Sport-up.pdf)|
| 📽️ Sporty-up 어플리케이션 시연 영상 | https://youtu.be/d-IZN6-IJSI | 
| 📑 Sporty-up 책자 | [Sporty-up_panel.pdf](https://github.com/user-attachments/files/20391718/Sporty-up_panel.pdf) |


## 구현화면

<table>
  <tr>
    <td width="25%"><img src="https://github.com/user-attachments/assets/50d0cd21-54a2-4730-9512-0acf61b3d18a" width="100%" /></td>
    <td width="25%"><img src="https://github.com/user-attachments/assets/851e8980-2b17-4a9e-8eb6-b79ac92f9236" width="100%" /></td>
    <td width="25%"><img src="https://github.com/user-attachments/assets/2f759aab-e0b8-40cc-9c0f-4a510d98aced" width="100%" /></td>
    <td width="25%"><img src="https://github.com/user-attachments/assets/aa64e650-beb6-4013-a8ac-0e1a42a48dca" width="100%" /></td>
  </tr>
  <tr>
    <td align="center"><b>스플래시</b></td>
    <td align="center"><b>로그인</b></td>
    <td align="center"><b>회원가입1</b></td>
    <td align="center"><b>회원가입2</b></td>
  </tr>
</table>
<table>
  <tr>
    <td width="25%"><img src="https://github.com/user-attachments/assets/7f83da30-69a2-432a-b856-ee6ec20bd980" width="100%" /></td>
    <td width="25%"><img src="https://github.com/user-attachments/assets/a271a04a-4fdd-48e9-892e-280f067fda0b" width="100%" /></td>
    <td width="25%"><img src="https://github.com/user-attachments/assets/d31f3834-21b1-4732-96f7-6a26c1ee276c" width="100%" /></td>
    <td width="25%"><img src="https://github.com/user-attachments/assets/38a60f86-e614-4aea-8780-0d3878f11758"width="100%" /></td>
  </tr>
  <tr>
    <td align="center"><b>회원가입3</b></td>
    <td align="center"><b>온보딩+설문조사</b></td>
    <td align="center"><b>홈 (메인)</b></td>
    <td align="center"><b>카메라 (수동촬영)</b></td>
  </tr>
</table>
<table>
  <tr>
    <td width="25%"><img src="https://github.com/user-attachments/assets/87f11da1-1901-4e4e-9fb5-78a16c62e583" width="100%" /></td>
    <td width="25%"><img src="https://github.com/user-attachments/assets/f2e94414-678a-4398-9cdc-3d14b47b7b9c" width="100%" /></td>
    <td width="25%"><img src="https://github.com/user-attachments/assets/712068ca-d5a1-4c26-9a6c-f5ec479b835d" width="100%" /></td>
    <td width="25%"><img src="https://github.com/user-attachments/assets/1a3466ce-6bc6-4708-a7dd-c07b2bb99302" width="100%" /></td>
  </tr>
  <tr>
    <td align="center"><b>지도</b></td>
    <td align="center"><b>마이페이지</b></td>
    <td align="center"><b>분석(차트+캘린더)</b></td>
    <td align="center"><b>세부분석(전체영상)</b></td>
  </tr>
</table>
<table>
  <tr>
     <td width="25%"><img src="https://github.com/user-attachments/assets/ad8e3ff8-01c1-4385-bc5a-6f14d74e78cd" width="100%" /></td>
    <td width="25%"><img src="https://github.com/user-attachments/assets/9ec1b9f4-eeca-4c14-a1e4-bb0fa0c2c680" width="100%" /></td>
    <td width="25%"><img src="https://github.com/user-attachments/assets/ba15ae9d-55cc-4730-a373-f00224029d14" width="100%" /></td>
    <td width="25%"><img src="https://github.com/user-attachments/assets/5adb64ab-c522-479a-904b-4c13e32264d6" width="100%" /></td>
  </tr>
  <tr>
    <td align="center"><b>카메라(자동촬영)</b></td>
    <td align="center"><b>카메라 피드백</b></td>
    <td align="center"><b>가이드라인</b></td>
    <td align="center"><b>세부분석(하이라이트)</b></td>
  </tr>
</table>



<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
