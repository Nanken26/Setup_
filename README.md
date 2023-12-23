Gerekli kurulumlar için bir hızlandırılmış repo
Setup.sh çalıştırıldığında(px4 ve ros2 gereklli tüm kaynaklarla beraber yüklenmektedir)
Çalıştırmak için: 
1- Klasör oluşturulur(mkdir setup) ve bu klasör içine script.sh atılır 
2 -Terminal açılır
3- Klasör içine girlir(cd setup)
4 - chmod -R 777 . yazılıp çalıştırılır
5 - ./script.sh çalıştırılır ve gerekli kurulum için onay verilmesi gereken yerlerde onay verilir veya şifre girlir.
6- falcon_simulation , falcon_description , falcon_telemetry klasörleri indilirip bir klasör açılıp onun içerisinde src klasörü açıp oraya koyulmalıdır.
7- src'nin içinde olan klasöre colcon build yapılmalıdır 
8- src/falcon_simulation/scripts içerisinde terminal açılıp
9- chmod -R 777 . yazılıp çalıştırılır alt satırda ./setup.sh çalıştırılır
10- scripts içindeki env.sh dosyasında 6. ve son satırdaki Falcon ismi srcnin olduğu klasörün adı yapılmalıdır 
11-terminalde ./env.sh sonrasında ./build.sh çalıştırılmalıdır

