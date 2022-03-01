> # ⛔ Error-handling
> ### Spring boot 설정 시 났던 오류들
>
> <br>
> 
> #### :warning: @어노테이션 import error
> - spring boot, gradle 설치 <br>
> - gradle-wrapper.properties 파일에 distributionUrl= 버전 부분 수정
> - 환경변수 설정 <br>
> ![gradle 환경변수 설정](https://user-images.githubusercontent.com/76691954/156149207-90433adf-944e-4e4b-956a-fa859865406e.PNG)
> ![gradle home 추가](https://user-images.githubusercontent.com/76691954/156149222-62417ac7-f576-4e67-93d6-d766fc8eb35c.PNG)
> - 프로젝트 우클릭 후 configure > convert as gradle project 
> -  프로젝트 우클릭 > gradle > refresh dependencies <br> <br>
> #### :warning: Could Not Find or Load Main Class Error
> - Run -> Run Configurations -> Main -> Main class Search -> Main Type 재매칭 
> ![Run Configurations](https://user-images.githubusercontent.com/76691954/156162447-e0197576-2863-476f-95aa-2d51defe3d23.png)
