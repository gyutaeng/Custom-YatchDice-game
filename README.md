<img width="1918" height="944" alt="Image" src="https://github.com/user-attachments/assets/f3428212-b0be-4dbb-a6e5-c32ba4b8fe0a" />
<img width="1915" height="941" alt="Image" src="https://github.com/user-attachments/assets/a0608117-79dd-42c6-8c1e-e228e0c9910a" />

`우타우러 트친들끼리 가내 자음원 보이스랑 일러 걸어놓고 야추다이스 할려고 만든 게임입니다`

캐릭터 일러스트와 보이스를 커스텀해서 요트다이스를 할 수 있는 게임입니다. 온라인 대전 지원합니다.
- 문의와 버그제보는 트위터 @GYU_VS로 :: https://x.com/GYU_VS 
- 개발에 사용된 것들 : claude, claude code, Godot, Render
- 전적으로 바이브코딩에만 의존했기에.. 사실 상 클로드가 99% 다 개발했습니다
- 케딩님께서 만드신 보이스 ustx 밀키트 : https://x.com/cosmos_in_cage/status/2100586112628707598

- ### [게임하러 가기](https://gyutaeng.github.io/Custom-YatchDice-game/)

## 참고
- Render 무료 서버를 대여하고 있어서 15분 정도 접속 안 하면 서버가 잠들어요
- 다시 서버를 키려면 서버 접속 시도한 뒤 1분 정도 기다려주셔야 서버가 다시 깨어납니다.
- 서버가 잠든 상태에서 방을 개설하실 때 오래 걸리실텐데 1분 정도 기다려주시면 정상적으로 접속됩니다.
- 게임 내에서 만드신 캐릭터의 음원 소스나 일러스트의 저작권 관련 문제는 전적으로 사용자에게 있음을 명시합니다
- 공개한 소스 코드를 이용해 더 발전시켜 2차배포하셔도 됩니다(제발그래주세요)

# 업데이트 노트
- 2026.09.17 - 공개
- 2026.09.19 - 샘플 캐릭터(아다치 레이, 데포코) 업로드



---


# 캐릭터 만들기 가이드

### 요약표

`발끝까지 나오는 전신보다는 [허벅지까지 자른 반신]이 이쁘게 나옵니다`
| 항목 | 권장 크기/길이 | 최대 한도 |
|---|---|---|
| 스탠딩 이미지 | 1200×2000, 비율 3:5(가로:세로)  | 긴 변 2048px, 4MB |
| 썸네일 | 256×256px | 긴 변 1024px, 1MB |
| 보이스 (개당) | 상황표 참고(1~7초) | 7초, 1MB |
| 전체 용량 | 10MB 이내 | 15MB(온라인 전송 기준) |

| 상황 | 언제 나오나요 | 권장 길이 |
|---|---|---|
| 게임 시작 인사 | 게임이 시작되고 첫 턴이 시작되기 전, 한 판에 한 번 | 5초 이내 |
| 내 차례 | 자기 차례가 될 때마다 | 1~2초 |
| 승리 | 1등으로 이겼을 때 | 7초 이내 |
| 패배 | 최하위 점수로 졌을 때 | 7초 이내 |
| 야추 | 주사위 5개가 같은 눈으로 나왔을 때 | 3~4초 |
| 라지 스트레이트 | 주사위가 라지 스트레이트로 나왔을 때 | 3~4초 |
| 풀 하우스 | 주사위가 풀 하우스로 나왔을 때 | 2~3초 |
| 포 카드 | 같은 눈 4개 이상이 나왔을 때 | 2~3초 |
| 상단 보너스 | 상단 점수 합계 63점을 처음 넘겼을 때 | 3~4초 |

1. 게임 시작 화면에서 [캐릭터 관리] → 왼쪽 하단 [새로 만들기]를 누릅니다.
2. 이름을 정하고, 스탠딩 이미지(1번)와 필요하면 썸네일(2번), **보이스**(3번)를 하나씩 올립니다.
3. [저장]을 누르면 끝입니다. 게임을 시작할 때 캐릭터 선택 화면에서
   방금 만든 캐릭터를 고르면 바로 쓸 수 있습니다.
4. 캐릭터를 내보내고 가져오기를 할 수 있습니다.
5. 캐릭터 생성의 자세한 설명은 이 쪽에서 
: [캐릭터 가이드](https://github.com/gyutaeng/yacht-dice/blob/main/docs/character_guide.md)



---
# 샘플 캐릭터
캐릭터 생성 참고용으로도, 실 사용으로도 쓸 수 있습니다. 문제가 발생하면 파일이 내려갈 수 있습니다.

- [아다치 레이/Adachi Rei](https://github.com/gyutaeng/Custom-YatchDice-game/blob/main/SampleChar/AdachiRei_char.zip)
- [데포코/Defoko](https://github.com/gyutaeng/Custom-YatchDice-game/blob/main/SampleChar/Defoko_char.zip)
---

# 라이선스 안내

## 이 저장소(`Custom-YatchDice-game`)에는 빌드된 웹 클라이언트만 들어 있습니다.
전체 소스코드(서버 포함)는 [gyutaeng/yacht-dice](https://github.com/gyutaeng/yacht-dice)에서
공개하고 있습니다.

- **게임 엔진**: [Godot Engine](https://godotengine.org/) (MIT License) - 라이선스
  전문은 [godotengine.org/license](https://godotengine.org/license/)에서 확인할
  수 있습니다.
- **폰트**: [Pretendard](https://github.com/orioncactus/pretendard)
  (Copyright (c) Kil Hyung-jin, SIL Open Font License 1.1)
- **파일 업로드 애드온**: [godot-file-access-web](https://github.com/Scrawach/godot-file-access-web)
  (Copyright (c) Scrawach, MIT License)
- **효과음**: Pixabay의 로열티프리 음원을 씁니다(출처 표기 의무는 없는
  라이선스입니다).
