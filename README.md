# StopWatch(END)

## Basic knowledge
<details> 
    <summary></summary>  
<img src="https://github.com/Seoin-A/StopWatch/assets/129828463/899dcd95-f5f4-4796-81a7-e78ab4b7c4fe).png" width="600" height="400"/>
    
    - Program : 명령과 데이터로 구성되어 저장 장치에 저장된 형태의 실행코드 파일
    
    - Thread : 한 프로세스 내에서 실행되는 흐름의 단위
             : 두 개 이상의 스레드가 있는 경우 멀티 스레드 
             
    - MainThread : Activity의 모든 라이프 사이클 관련 콜백 실행 담당
                 : Button, EditText와 같은 UI위젯을 사용한 사용자 이벤트와 UI 드로잉 이벤트 담당
    
    - BackgrounndThread : 복잡한 연산이나, 네트워크 작업, 데이터 작업 수행

    - chain : 뷰 사이의 여백을 수직 혹은 수평 방향으로 균등하게 분배할 수 있다.
    
<img src="https://github.com/Seoin-A/StopWatch/assets/129828463/142385af-8fca-42fa-8300-a88fc020255a" width="700" height="150"/>

</details>


## Development Environment
- Android Studio Giraffe

## Application Version
- minSdkVersion : API 26


## Wrap-up
1) Thread
- 한 프로세스 내에서 실행되는 흐름의 단위  
- 백그라운드 스레드에서는 시간이 걸리는 일을 처리  
- UI 관련 작업은 메인 스레드에서만 가능

2) Baseline
    <details>
      <summary></summary>
      
    ![image](https://github.com/Seoin-A/StopWatch/assets/129828463/db78b898-c663-48e9-a3a4-06cb3abc7bd9)      
    </details>   
<br>
     
3) Chain
    <details>
       <summary></summary>
       
    ![image](https://github.com/Seoin-A/StopWatch/assets/129828463/9513e4ef-66ed-48fd-a6dd-af10abfea632)
    
    </details>

4) Resource 파일
    - Color.xml, String.xml을 사용하면 색상과 문자열을 재활용할 수 있다.
  



