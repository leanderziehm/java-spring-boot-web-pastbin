```
curl https://start.spring.io/starter.zip \
  -d type=maven-project \
  -d language=java \
  -d platformVersion=4.1.2 \
  -d packaging=jar \
  -d configurationFileFormat=properties \
  -d javaVersion=17 \
  -d groupId=com.leanderziehm \
  -d artifactId=pastebin \
  -d packageName=com.leanderziehm.pastebin \
  -d dependencies=data-jpa,postgresql,web \
  -o pastebin.zip
```
