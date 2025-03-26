# Riot_img
롤/롤체 이미지 저장

03/26 
<h6>GPT의 힘으로 JSON파일 화면에 출력하도록 해둠</h6>
<img src="https://github.com/user-attachments/assets/a325c25f-3cf1-44af-b70e-86f21746a181" width="300" height="350"/>


<h6>pom.xml</h6>
<!-- 버전 살짝 변화 있긴한데 아직 뭐 별건 아닌거같음. 혹시 몰라서 올려봄 -->
<properties>
     <java.version>11</java.version>
    <org.springframework-version>5.1.8.RELEASE</org.springframework-version>
    <org.aspectj-version>1.6.10</org.aspectj-version>
    <org.slf4j-version>1.6.6</org.slf4j-version>
    <org.apache.tiles-version>3.0.8</org.apache.tiles-version>
</properties>
<!-- Jackson 라이브러리 -->
<dependency>
    <groupId>com.fasterxml.jackson.core</groupId>
    <artifactId>jackson-databind</artifactId>
    <version>2.15.0</version> <!-- 최신 버전으로 변경 가능 -->
</dependency>
<dependency>
    <groupId>com.fasterxml.jackson.core</groupId>
    <artifactId>jackson-core</artifactId>
    <version>2.15.0</version>
</dependency>
<dependency>
    <groupId>com.fasterxml.jackson.core</groupId>
    <artifactId>jackson-annotations</artifactId>
    <version>2.15.0</version>
</dependency>
<!-- 플러그인 바꿔줌 -->
<plugin>
    <groupId>org.apache.maven.plugins</groupId>
    <artifactId>maven-compiler-plugin</artifactId>
    <version>3.8.1</version> <!-- 최신 안정 버전으로 변경 -->
    <configuration>
        <source>11</source>
        <target>11</target>
        <compilerArgument>-Xlint:all</compilerArgument>
        <showWarnings>true</showWarnings>
        <showDeprecation>true</showDeprecation>
    </configuration>
</plugin>
