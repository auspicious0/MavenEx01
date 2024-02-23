# MavenEx01

## 0.	cmd - Maven

Maven을 설치 후 repository 를 생성한 후 생성한 repository 위치에서 cmd를 켠 뒤
아래와 같이 입력하면

```cmd
mvn archetype:generate -DgroupId=com.example -DartifactId=hello-world -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false

cd hello-world

mvn package
java –cp target/hello-world-1.0.0-SNAPSHOT.jar com.example.App 
```

 ![image](https://github.com/auspicious0/MavenEx01/assets/108572025/3b2a1246-179f-4e97-bc21-392b3c29e385)

Hello World가 출력된다. 이를 eclipse를 통해 적용해보자.

## 1.	eclipse - maven

-	우선 maven을 자신의 os에 맞게 설치한 후 압축을 해제한다. 
-	압축 해제된 maven파일의 bin 폴더를 환경 변수로 설정한다. 
-	ecipse marketplace를 확인하여 maven m2e – maven support in eclipse IDE latest, maven intergration for ecipse가 설치되어 있는지 확인한다. (설치 되지 않았다면 직접 설치한다.)
-	windown -> preference _> Maven -> User Settings에서 setting.xml에 원하는 maven path를 추가한 후 저장하고 maven project를 생성한다.
-	생성된 maven 파일의 index.jsp에서 cntl f11을 클릭하면 tomcat 서버를 통해 web 배포가 되며 내용 확인이 가능한다.
## 2.	실행결과
 
![image](https://github.com/auspicious0/MavenEx01/assets/108572025/a8f0edae-5609-4744-b318-4dadb186479f)
![image](https://github.com/auspicious0/MavenEx01/assets/108572025/c1fb0cfe-ec3c-459a-8ea8-46a87431f96e)

 
