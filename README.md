# kotlin-calculator-precourse
## 구현할 기능 목록 정리

1. 입력 안내 메시지 출력  
- 콘솔에 "덧셈할 문자열을 입력해 주세요."라는 메시지를 띄운다.  
2. 입력 값 받기  
- readLine()을 사용하여 사용자의 입력을 받는다.  
3. 입력 값 처리 및 계산  
- 비어있을 경우  
    - 비어있을 경우 0을 출력
- 커스텀 구분자 처리  
    - 입력값에 //와 \n이 포함된 경우 // 이후의 문자열을 커스텀 구분자로 인식하여 이를 기준으로 숫자를 분리한후 숫자의 합을 출력  
- 기본 구분자(쉼표 또는 콜론)로 문자열 분리  
    - 입력값에 // 또는 \n이 포함되어 있지 않다면, 쉼표(,) 또는 콜론(:)을 구분자로 사용하여 문자열을 숫자로 분리한후 분리된 숫자의 합을 출력  
- 예외 처리  
    - 위의 두 조건을 만족하지 않는다면 IllegalArgumentException을 발생시키고 프로그램을 종료한다.  
