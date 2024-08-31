<!-- introduce project repository -------------------------------------------------------------------------------------------------------------------------------------------->
<div align=center>

<br>

-<table>
  <tr><th width=881px>  
    
## Simple Board

[![gradle](https://img.shields.io/badge/Gradle-02303A.svg?style=badge&logo=Gradle&logoColor=white)](https://github.com/zhyun-project/simple-board-01)
[![junit5](https://img.shields.io/badge/JUnit_5-25A162?style=badge&logo=&logoColor=white)](https://github.com/zhyun-project/simple-board-01)
[![java](https://img.shields.io/badge/Java-ED8B00?style=badge&logo=openjdk&logoColor=white)](https://github.com/zhyun-project/simple-board-01)
[![spring boot 3](https://img.shields.io/badge/Spring_boot_3-6DB33F?style=badge&logo=spring&logoColor=white)](https://github.com/zhyun-project/simple-board-01)
[![h2](https://img.shields.io/badge/H2-224DCA?style=badge&logo=h2&logoColor=white)](https://github.com/zhyun-project/simple-board-01)  

</th></tr>
<tr><td align=center>
<br>

h2 db를 embedded 형태로 사용하여 제목과 내용을 관리하는 간단한 형태의 게시판 프로젝트입니다.

테스트 코드 작성을 익히기 위해 간단한 구조로 설계하였습니다.

<div align=right>
  <a href="https://github.com/zhyun-project/simple-board-01"><picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/badge/Repository%20🔗-100000?style=for-the-badge&logo=github&logoColor=white">
        <source media="(prefers-color-scheme: light)" srcset="https://img.shields.io/badge/Repository%20🔗-2f80ed?style=for-the-badge&logo=github&logoColor=white">
        <img alt="repository link" src="https://img.shields.io/badge/Repository%20🔗-100000?style=for-the-badge&logo=github&logoColor=white"/>
    </picture></a>
</div>

  </td></tr>
</table> 

<br>
<br>

-<table>
  <tr><th width=881>
    
## Board

[![gradle](https://img.shields.io/badge/Gradle-02303A.svg?style=badge&logo=Gradle&logoColor=white)](https://github.com/zhyun-project/simple-board-01)
[![junit5](https://img.shields.io/badge/JUnit_5-25A162?style=badge&logo=&logoColor=white)](https://github.com/zhyun-project/simple-board-01)
[![java](https://img.shields.io/badge/Java-ED8B00?style=badge&logo=openjdk&logoColor=white)](https://github.com/zhyun-project/simple-board-01)
[![spring boot 3](https://img.shields.io/badge/Spring_boot_3-6DB33F?style=badge&logo=spring&logoColor=white)](https://github.com/zhyun-project/simple-board-01)
[![spring security](https://img.shields.io/badge/Spring_Security-6DB33F?style=badge&logo=Spring-Security&logoColor=white)](https://github.com/zhyun-project/simple-board-01)
[![jwt](https://img.shields.io/badge/JWT-000?style=badge&logo=jsonwebtokens&logoColor=white)](https://github.com/zhyun-project/simple-board-01)
[![redis](https://img.shields.io/badge/redis-%23DD0031.svg?&style=badge&logo=redis&logoColor=white)](https://github.com/zhyun-project/simple-board-01)
[![h2](https://img.shields.io/badge/H2-224DCA?style=badge&logo=h2&logoColor=white)](https://github.com/zhyun-project/simple-board-01)  

  </th></tr>
  <tr><td align=center>
<br>

simple-board 프로젝트에 사용자 관리를 추가한 프로젝트입니다.

<br>  

JWT와 시큐리티를 적용하여 사용자 로그인 및 권한에 따른 접근 제한 구현과 멀티 모듈 프로젝트 구현이 목표입니다.

<br>

도메인이 2개(사용자, 게시글)라서 공부해보고 싶었던 멀티 모듈 구조를 적용해볼 수 있었으며  
사용자 관리 모듈과 게시글 관리 모듈, 그리고 gateway(discovery) 모듈 순서로 구현하였습니다.

<br>

시큐리티와 JWT가 어렵다고 생각되어 사용자 관리 모듈을 제일 먼저 개발하였고  
다음으로 사용자 관리 구현 후 토큰을 이용하는 서비스인 게시글 관리 모듈을 구현,    
마지막으로 gateway 모듈을 구현하여 하나의 "호스트:port"를 통해 모든 서비스에 접근할 수 있도록 구현하였습니다.

<br>

<div align=right>
  <a href="https://github.com/zhyun-project/simple-board-02"><picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/badge/Repository%20🔗-100000?style=for-the-badge&logo=github&logoColor=white">
        <source media="(prefers-color-scheme: light)" srcset="https://img.shields.io/badge/Repository%20🔗-2f80ed?style=for-the-badge&logo=github&logoColor=white">
        <img alt="repository link" src="https://img.shields.io/badge/Repository%20🔗-100000?style=for-the-badge&logo=github&logoColor=white"/>
    </picture></a>
</div>  

  </td></tr>
  <tr><td>
<br>
    
　🛠️ 리팩토링    
 
　　1\. *`24.04.24 ~ 24.05.18`* - [*프로젝트 구조 변경, 테스트 코드 전체 수정*](https://github.com/zhyun-project/simple-board-02/wiki/🛠%EF%B8%8F-리팩토링-1차-⚒%EF%B8%8F)  
　　2\. *`24.08.25 ~ 24.08.27`* - [*docker 적용, 실행 profile별로 사용하는 db를 다르게 적용 (local: h2, prod: mariadb)*](https://github.com/zhyun-project/simple-board-02/pull/92)  
　　3\. *`24.08.28`* - [*ci/cd 적용, 서버 배포*](https://github.com/zhyun-project/simple-board-02/issues/93)  
　　4\. *`24.08.29`* - [*cors 설정 추가*](https://github.com/zhyun-project/simple-board-02/commit/eeacc04e217caff2e2b76321ea0692ad04265517)  
　　5\. *`24.08.30`* - [*swagger 설정 추가*](https://github.com/zhyun-project/simple-board-02/issues/94) [ [1. swagger 설정파일 생성](https://github.com/zhyun-project/simple-board-02/commit/33a9900957a7bb94345cb86bf4b93c30b1b07984) , [2. security 관련 설정](https://github.com/zhyun-project/simple-board-02/commit/1b7de074781a117a3402fbb559fdab52c1f3b5fe) ]  
　　　　　　　 　 - [*게시글 관련 기능 수정*](https://github.com/zhyun-project/simple-board-02/issues/98)  
 
<br>
  </td></tr>
</table>


<!-- template ------------------------------------
<br>
<br>
<br>

-<table>
  <tr><th width=881px>
    
## Title

// spec
[![gradle](https://img.shields.io/badge/Gradle-02303A.svg?style=badge&logo=Gradle&logoColor=white)](https://github.com/zhyun-project/simple-board-01)
[![junit5](https://img.shields.io/badge/JUnit_5-25A162?style=badge&logo=&logoColor=white)](https://github.com/zhyun-project/simple-board-01)
[![java](https://img.shields.io/badge/Java-ED8B00?style=badge&logo=openjdk&logoColor=white)](https://github.com/zhyun-project/simple-board-01)
[![spring boot 3](https://img.shields.io/badge/Spring_boot_3-6DB33F?style=badge&logo=spring&logoColor=white)](https://github.com/zhyun-project/simple-board-01)
[![spring security](https://img.shields.io/badge/Spring_Security-6DB33F?style=badge&logo=Spring-Security&logoColor=white)](https://github.com/zhyun-project/simple-board-01)
[![jwt](https://img.shields.io/badge/JWT-000?style=badge&logo=jsonwebtokens&logoColor=white)](https://github.com/zhyun-project/simple-board-01)
[![redis](https://img.shields.io/badge/redis-%23DD0031.svg?&style=badge&logo=redis&logoColor=white)](https://github.com/zhyun-project/simple-board-01)
[![h2](https://img.shields.io/badge/H2-224DCA?style=badge&logo=h2&logoColor=white)](https://github.com/zhyun-project/simple-board-01)  

  </th></tr>
  <tr><td align=center>
<br>

// content

<br>

// repository
<div align=right>
    <a href="https://github.com/zhyun-project/simple-board-02"><picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/badge/Repository%20🔗-100000?style=for-the-badge&logo=github&logoColor=white">
        <source media="(prefers-color-scheme: light)" srcset="https://img.shields.io/badge/Repository%20🔗-2f80ed?style=for-the-badge&logo=github&logoColor=white">
        <img alt="repository link" src="https://img.shields.io/badge/Repository%20🔗-100000?style=for-the-badge&logo=github&logoColor=white"/>
    </picture></a>
</div>

  </td></tr>
</table>
-->


</div>
