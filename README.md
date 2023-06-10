# Java_Servlet_Mysql_Login_Page

Library >> mysql-connector-java-8.0.30.jar

Giriş sayfasında xpath login injection açığı bulunmaktadır.
Payload >> ' or '1'='1
Eğer açığı kapatmak istersek Main.java dosyasındaki 39. ve 40. satırlardaki "//" işaretlerini kaldırmalıyız.
Bu şekilde girilen username ve password değerlerine filtreleme işlemi uygulamış olacağız.
