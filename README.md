## opensource


-  **getopt 및 getopts 명령어**

    - shell script에서 명령어를 사용할 때 옵션을 파싱하고 옵션 지정을 할 수 있게 해주는 명령어

    - 차이점 : 옵션에는 '-'를 한개 붙히는 short옵션 두개 붙히는 long옵션이 있는데 getopts는 short옵션을 처리, getopt는 short, long옵션 모두 지원
    

    
****
-  **sed 및 awk 명령어**

    - sed : 비대화형 편집기이며 하나의 입력이 하나의 출력을 내보낸다.
    
        1)정규표현식을 사용하기 때문에 특수문자앞에 역 슬래시(\)를 붙여주어야 한다.
        
        2)다중 명령어를 사용할 때는 반드시 e를 사용해야한다.
        
        |옵션|실행|
        |----|----|
        |-p |출력|
        |-d |삭제|
        |-s|치환|
        |,|범위 지정|
        |-e|다중 편집|
        |-r|파일에서 읽기|
        |-w|파일에 쓰기|
        |-a|추가|
        |-i|삽입|
        |-c|변경|
        |-n|다음|
        |-y|변환|
        |-q|종료
        
        
    - awk : 대화형 편집기, 파일에서 패턴이 일치하는 행을 찾아서 지정한 조치를 수행해주는 명령어.

        1)패턴과 command로 이루어진다.
        
        2)패턴 부분에는 정규식이나 조건 표현식이 올 수 있다.
        
        3)awk 스크립트를 사용하려면 다음과 같이 작은 따옴표로 묶은 중괄호를 사용해야한다.
       
        (awk [option] 'pattern{action}'[input-file])
        
        |옵션|실행|
        |---|---|
        |-u|버퍼를 사용하지 않고 출력|
        |-F|확장된 정규 표현식으로 필드구분자를 지정|
        |-v|스크립트를 실행하기 전에 미리 변수를 지정|
        |-f|awk 명령 스크립트를 파일에서 읽어온다|
        
        
