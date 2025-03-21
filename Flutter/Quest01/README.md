# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 홍지수, 박지윤
- 리뷰어 : 전승아, 곽현정

# PRT(Peer Review Template)
- [x]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
        - ![image](https://github.com/user-attachments/assets/d2a0b814-c9bf-4ef6-a5a6-aa99cd4d686a)

- [x]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - ![image](https://github.com/user-attachments/assets/f8e8b8f0-b0b3-438d-8444-55042d9b580f)
        - 코드가 간결하고, 5회반복으로 횟수를 제한 해 기능적으로 안정적입니다. 
        
- [x]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - ![image](https://github.com/user-attachments/assets/5bbcd740-916f-40ee-93ed-929469694815)
        - 어떠한 로직으로 작동되는지 기재되어 있습니다. 
        
- [x]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - ![image](https://github.com/user-attachments/assets/7de16e3d-fd5c-40ab-a135-46f8548f370c)
        - 추가 실험을 비롯하여 자세한 회고가 작성되어 있습니다.
        - 클래스를 사용하는 것도 좋은 방법이었을것으로 생각하나, 전반적으로 기능이 단순해 해당코드로도 충분했다고 판단됩니다. 
        
- [x]  **5. 코드가 간결하고 효율적인가요?**
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - ![Uploading image.png…]()
        - 작업타이머와 기본 휴식타이머등 기본 모듈들이 잘 기재되어 있고 효율적입니다. 


# 회고(참고 링크 및 코드 개선)
```
(전승아)
간결하고 깔끔한 코드입니다. 핵심기능이 잘 구현되어 있습니다.
배운내용이 함축적으로 정리되어 있습니다.

(곽현정)
회고: 최대 반복 횟수를 추가하신 점이 인상적이었습니다. 저희 조의 경우에는 무제한으로 반복으로 하고 일시정지/재개 버튼을 눌렀는데 또 다른 발상을 적용하셔서 신기했습니다.
저희 조는 옆에 모바일 화면을 두고 ui 수정에 집중한 면이 있는데, 정석대로 아래에 초별로 타이머가 돌아가는 버전을 하셔서 코드를 보고 많이 배울 수 있었습니다.
앞에 로직을 적고 시작하셔서 일목요연하게 코드를 읽어낼 수 있었던 것 같고 중간중간에 여러 시도를 해보려고 하신 게 엿보였습니다.
이를테면 초 단위를 '분:초' 형식으로 변환할 때, const는 사용이 불가능한지 생각해보신 것도 기록으로 남겨주셔서 좋았습니다.

 
```
