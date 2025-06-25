# 🧠 생성형 AI와 음성 인식 기반의 가상 면접 시스템 개발

> Unity 기반으로 개발된 **가상 면접 시뮬레이션 시스템**입니다.  
> 본 시스템은 GPT-4 기반의 생성형 인공지능과 음성 인식(STT), 음성 합성(TTS) 기술을 활용하여, 실시간으로 질문을 생성하고 음성으로 출력하며, 사용자 음성 응답을 받아 자동으로 평가 및 피드백을 제공하는 기능을 갖추고 있습니다.  
> 특히 디지털 휴먼(가상 면접관)은 질문에 맞는 음소(`a`, `e`, `i`, `o`, `u`)를 분석하여 입모양을 자동으로 동기화하는 립싱크 기술이 적용되어, 실제 사람과 면접을 보는 듯한 몰입감을 제공합니다.  
>  
> 사용자는 키오스크 형식의 인터페이스를 통해 면접장(예: 삼성, LG, Naver 등)과 직무(예: IT, 마케팅, 디자인 등)를 선택할 수 있으며, 환경에 따라 다양한 가상 공간에서 면접이 진행됩니다. 면접은 시작 버튼을 누르면 진행되며, 사용자의 답변은 음성으로 녹음되어 서버로 전송된 뒤 자동 분석됩니다.  
>  
> 면접 종료 후, 시스템은 GPT-4의 분석 결과를 기반으로 사용자의 답변을 항목별(예: 의사소통, 진실성, 팀워크 등)로 평가하고, 레이더 차트와 텍스트 피드백을 제공하여 취업 준비생이 자신의 부족한 점을 파악하고 개선할 수 있도록 돕습니다.  
>  
> 본 프로젝트는 **국립금오공과대학교 산학협력단 명의로 특허 출원**되었으며,  
> 📌 **출원번호: 10-2023-0173246**  
> 📌 **출원명: 생성형 인공지능과 음성 인식을 활용한 가상 면접 시스템**

---

## 🖼️ 시연 화면

### 🔹 사용자 정보 입력  
![사용자데이터정보-removebg-preview](https://github.com/user-attachments/assets/c36cbbc7-20c8-427d-a115-7cfd7ce646ca)

### 🔹 면접장 & 직무 선택  
![직무선택_resized](https://github.com/user-attachments/assets/11c945ea-01c0-4629-aca1-2097b19e4037)
![면접장선택-removebg-preview](https://github.com/user-attachments/assets/3b3c0376-fc98-4943-9020-f1de92ae0839)

### 🔹 면접 진행 화면  
![면접장1](https://github.com/user-attachments/assets/9d3c417b-ba64-4c9c-8139-561323987454)
![면접장2](https://github.com/user-attachments/assets/1a40d239-ec9d-4349-af37-499351d6ed92)
![면접장3](https://github.com/user-attachments/assets/a7859524-16a9-4fe2-bb9a-7664a177e715)

### 🔹 결과 분석 화면  
![면접 결과](https://github.com/user-attachments/assets/eda5c2e5-9c24-4663-87a1-6826c684de9f)
![키오스크_결과-removebg-preview](https://github.com/user-attachments/assets/b36239bd-2b00-44fa-b83e-fb4b6a844227)

---

## 🔧 사용 기술

| 분야 | 기술 |
|------|------|
| Engine | Unity |
| AI | GPT-4 (Prompt Engineering), Whisper (STT), VITS (TTS) |
| Networking | Python TCP Socket |
| 립싱크 | uLipSync (음소 매핑 기반 입모양 애니메이션) |
| UI | Unity UI Toolkit + C# |
| 기타 | JSON 분석, Scene 구성 자동화 |

---

## 🙋‍♂️ 기여 내용

- Unity 기반 전체 메타버스 UI 및 면접장 제작
- 디지털 휴먼 캐릭터 구성 및 **uLipSync 기반 립싱크 시스템 적용**
- 질문 음성 → 립모양 자동 애니메이션 동기화
- 면접 데이터 입력, 녹음/재생/전송, 결과 분석 UI 제작

---

## 🏆 프로젝트 성과

- 🎓 **특허 출원** 완료 (국립금오공과대학교 산학협력단 명의)
- 🗣️ GPT + 음성 기술 + Unity 융합 프로젝트 완성
- 🎯 사용자 입력부터 결과 분석까지 완전한 가상 면접 파이프라인 구축

---
