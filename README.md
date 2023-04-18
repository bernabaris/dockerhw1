# dockerhw1


Doğru yapılandırılmış bir Maven dosyasıyla çalıştırılabilir bir jar dosyası oluşturulur.
<h2> $ mvn clean package </h2>

Spring Boot uygulaması çalıştırılır.
<h2> $ java -jar target/demo-0.0.1-SNAPSHOT.jar </h2>

Tarayıcıdan localhost:8080 adresinden Spring Boot uygulaması çalıştırılır. </h2>

Uygulamayı dockerize etmek için oluşturulan Dockerfile dosyasında 'docker build' komutu çalıştırılır. 
<h2> $ docker build -t dockerhw1 . </h2>

Oluşturulan container Docker kullanarak çalıştırılır.
<h2> $ docker run it -p 8080:8080 dockerhw1 </h2>

