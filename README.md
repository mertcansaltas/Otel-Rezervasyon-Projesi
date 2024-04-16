Projem, kullanıcıların bir otel üzerinde online olarak rezervasyon yapabildiği, admin tarafında bu rezervasyonların karşılandığı, kullanıcının rezervasyonlarının onaylanması durumunda kendisine mail gönderildiği, kullanıcının arama kriterlerine göre rezervasyon yapabildiği bir akış üzerine kuruludur.
AspNet Core Api üzerinden Swagger ve Postman kullanarak testlerimi gerçekleştirdim.
Mimari olarak N Tier Architecture kullandım. Projede tek Solution altında 6 tane katman yer aldı. Entity Framework'ü kullandım.
Veri tabanı olarak MSSQL kullandım.
Proje güvenliği için Identity kullandım. Böylece yetkisiz rol erişimlerinin önüne geçmiş oldum.
Ek olarak projenin belli bir bölümünden sonra farklı api kaynaklarını tüketmeye başladım. Bunlar arasında en yoğun kullandığım Rapid Api oldu. 
Rapid Api üzerinden BookingCom apisini kullanarak kendi panelimiz üzerinden parametre girerek Booking'de otel verisi sonuçlarını kendi AspNet Core projeme taşıdım.
Yine Rapid Api üzerinden online otel rezervasyonlarında ihtiyaç olacağını düşündüğümüz "Uçuş, Döviz ve Hava Durumu" verilerini api olarak çekip consume ettim.
Finale gelirken Rapid Api üzerinden istediğim kullanıcıya ait Linkedin, Instagram, Twitter ve Facebook gibi platformlardan takipçi ve takip edilen kişi sayılarını çektim.

![otel1](https://github.com/mertcansaltas/Otel-Rezervasyon-Projesi/assets/150259943/2bb35107-3f2d-4c8c-a96c-4f82793b6328)

![otel2](https://github.com/mertcansaltas/Otel-Rezervasyon-Projesi/assets/150259943/f610f1b7-13be-4383-847a-2da5e7fc6aac)

![otel3](https://github.com/mertcansaltas/Otel-Rezervasyon-Projesi/assets/150259943/f431576e-17e8-4281-ac82-1994346c2310)

![otel4](https://github.com/mertcansaltas/Otel-Rezervasyon-Projesi/assets/150259943/9b0be74b-1fed-4f2a-8bb8-17417ec51eb3)

![otel5](https://github.com/mertcansaltas/Otel-Rezervasyon-Projesi/assets/150259943/f6f30e6d-641e-427d-b22f-6eef29013f9a)

![otel6](https://github.com/mertcansaltas/Otel-Rezervasyon-Projesi/assets/150259943/70e37ec1-8c37-43d3-b561-2de12d2f1d2f)

![otel7](https://github.com/mertcansaltas/Otel-Rezervasyon-Projesi/assets/150259943/b56d2b8d-6b7e-48c6-aeeb-876618e698f7)

![otel8](https://github.com/mertcansaltas/Otel-Rezervasyon-Projesi/assets/150259943/a786c138-a8b1-486f-9bb6-8aac45a04e6b)

![otel9](https://github.com/mertcansaltas/Otel-Rezervasyon-Projesi/assets/150259943/1f044c70-4beb-4d57-9fdd-c4c49e97435b)

![otel10](https://github.com/mertcansaltas/Otel-Rezervasyon-Projesi/assets/150259943/35858a23-4800-4a7d-960f-612d50f60672)

![otel12](https://github.com/mertcansaltas/Otel-Rezervasyon-Projesi/assets/150259943/567529f5-3445-4e57-a24a-f1bc6b7aeb8c)

![otel13](https://github.com/mertcansaltas/Otel-Rezervasyon-Projesi/assets/150259943/51a36f15-5e56-4743-95d0-3efade6a2c19)

![otel14](https://github.com/mertcansaltas/Otel-Rezervasyon-Projesi/assets/150259943/8484a604-ad76-405e-b375-1177b7e31d9b)

![otel15](https://github.com/mertcansaltas/Otel-Rezervasyon-Projesi/assets/150259943/67a90b1f-f467-4617-811b-a5c7c326a62f)

![otel16](https://github.com/mertcansaltas/Otel-Rezervasyon-Projesi/assets/150259943/67efad03-7ee5-4fda-8df5-88de427158ce)

![otel17](https://github.com/mertcansaltas/Otel-Rezervasyon-Projesi/assets/150259943/2a80144a-0d1f-4ba8-a211-eda3d8d81f27)

![otel18](https://github.com/mertcansaltas/Otel-Rezervasyon-Projesi/assets/150259943/218c4b52-0ce2-4820-acf6-1e94206e2f17)



