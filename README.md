### 문서 토픽 추출 소프트웨어
인터넷 뉴스 기사를 크롤링하여 연도 별로 IT의 <b>핵심 주제를 파악</b>할 수 있는 <b>LDA 알고리즘</b> 기반으로 구현된 문서의 토픽(키워드)를 추출하는 웹 소프트웨어입니다.<br/>
By CP-COP팀 : 안윤빈(산업기술대 17), 양현용(산업기술대 15), 한승훈(산업기술대 15)


### 시스템 구성도
![image](https://user-images.githubusercontent.com/50897259/92837698-dbaa8780-f418-11ea-8f86-d8040e8a8653.png)


### Demo Web Site
![image](https://user-images.githubusercontent.com/50897259/92837707-de0ce180-f418-11ea-8d4d-533816e03307.png)


### 참고 문헌
* [잠재 디리클레 할당(Latent Dirichlet Allocation, LDA)](https://wikidocs.net/30708) : LDA 알고리즘을 구현하기 위해 참고하였습니다.
![image](https://user-images.githubusercontent.com/50897259/92837640-ca617b00-f418-11ea-9ea8-14833ac7ebad.png)


### 설계 환경 및 구현 
```
● JSP 언어 사용
Apache Tomcat을 사용하여 웹 프로그램 구현

● Python3 언어 사용
BeautifulSoup 라이브러리를 사용하여 뉴스 기사 웹 크롤러 모듈 구현

● R Studio
LDA 알고리즘을 구현
```
