# Miracle Brain

## 프로젝트 개요
**Miracle Brain**은 iOS 기반의 두뇌 훈련 앱으로, 간단한 연산 문제를 통해 사용자들의 집중력과 계산 능력을 향상시키는 데 초점을 맞춘 앱 서비스입니다.  
사용자는 다양한 연산 옵션과 난이도를 선택하여 제한 시간 내 문제를 해결하고, 자신의 성과를 확인할 수 있습니다.  

📲 [App 다운로드하기](https://apps.apple.com/kr/app/%EB%AF%B8%EB%9D%BC%ED%81%B4-%EB%B8%8C%EB%A0%88%EC%9D%B8-miracle-brain/id6479227526)

<br>

## 주요 기능

#### 1. 동적 인트로 애니메이션
- 앱 시작 시 **Lottie 애니메이션**을 통해 생동감 있는 화면 제공
- LaunchScreen을 대체하여 사용자 경험 강화

#### 2. 연산 및 난이도 옵션
- **연산 옵션**: 더하기, 빼기, 곱하기 중 선택 가능  
- **난이도**: 초급, 중급, 고급 설정 (난이도에 따라 숫자 자릿수 조정)  
- **UI 구성**: 직관적인 PickerView와 버튼 인터페이스 제공  

#### 3. 제한 시간 내 문제 풀이
- 60초 제한 시간 동안 난이도와 옵션에 맞는 **랜덤 생성 문제** 풀이  
- **정답/오답 처리**: 정답 시 다음 문제, 오답 시 동일 문제 유지  
- 뺄셈 연산에서는 음수가 나오지 않도록 설계

#### 4. 결과 및 점수 확인
- 제한 시간 종료 후 **정답 개수**를 알림 창에 표시  
- 확인 버튼 클릭 시 메인 화면으로 복귀

<br>

## 개발 기간
- **2024년 3월 10일** ~ **2024년 3월 14일**

<br>

## 기술 스택

| **분야**              | **기술 및 도구**                                   |
|-----------------------|--------------------------------------------------|
| **iOS 개발**          | Swift, UIKit, Storyboard                         |
| **라이브러리**         | CocoaPods, Lottie                                |
| **백엔드 연동**        | Firebase Analytics, Firebase DynamicLinks        |

<br>

## 앱 구조 및 흐름

```plaintext
📱 앱 실행
 ├── 동적 인트로 애니메이션
 ├── 연산 및 난이도 옵션 선택
 │     ├── 연산 옵션: 더하기, 빼기, 곱하기
 │     └── 난이도 설정: 초급, 중급, 고급
 ├── 문제 풀이
 │     ├── 정답: 다음 문제로 이동
 │     └── 오답: 동일 문제 유지
 ├── 제한 시간 종료
 │     └── 정답 개수 결과 확인
 └── 메인 화면으로 복귀
```

<br>

## 스크린샷
<p align="center"> <img src="./img/intro1.png" width="20%" /> <img src="./img/mode.png" width="20%" /> <img src="./img/level.png" width="20%" /> <img src="./img/plus.png" width="20%" /> </p>
