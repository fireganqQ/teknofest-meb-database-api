# Login
## Giriş Yapmak
```url
 {url}/api/v1/<auth_token>/<school_code>/login/
```

# Read
## Sınıfın Verilerini Cekme
```url
 {url}/api/v1/<auth_token>/<school_code>/login/read/<_class>/
```

# Push
## Okulun Sınıflarını Oluşturma
```url
 {url}/api/v1/<auth_token>/<school_code>/login/push/classes/<classes>
```
 - ```classes```: Tüm Sınıflar

### Kullanım
 - ```<branch_number>=<branch_name>```: Sınıf Numarası İle Sınıf İsmi Arasında "=" Belirtin,
 - ```branch_number>=<branch_name>&<branch_number2>=<branch_name2>```: Sınıf Bilgileri Arasına "&" Ekleyin


## Sınıfın Ders Programını Girme
```url
 {url}/api/v1/<auth_token>/<school_code>/login/push/class_data/<class>/<lessonId>/<day1>/<day2>/<day3>/<day4>/<day5>/<day1Teacher>/<day2Teacher>/<day3Teacher>/<day4Teacher>/<day5Teacher>/
```
 - ```/class```: Sınıf Numarası İle Sınıf İsmi (Arasında Boşluk Olmadan)
 - ```/lessonId```: Kacıncı Ders Olduğu
 - ```/day1```: 1. Günki x. Ders
 - ```/day2```: 2. Günki x. Ders
 - ```/day3```: 3. Günki x. Ders
 - ```/day4```: 4. Günki x. Ders
 - ```/day5```: 5. Günki x. Ders
 - ```/day1Teacher```: 1. Günki x. Dersin Öğretmeni 
 - ```/day2Teacher```: 2. Günki x. Dersin Öğretmeni 
 - ```/day3Teacher```: 3. Günki x. Dersin Öğretmeni 
 - ```/day4Teacher```: 4. Günki x. Dersin Öğretmeni 
 - ```/day5Teacher```: 5. Günki x. Dersin Öğretmeni 


# Update
## Sınıfın Ders Programını Güncelleme
```url
 /api/v1/<auth_token>/<school_code>/login/update/class_data/<class>/<lessonId>/<day1>/<day2>/<day3>/<day4>/<day5>/<day1Teacher>/<day2Teacher>/<day3Teacher>/<day4Teacher>/<day5Teacher>/
```
 - ```/class```: Sınıf Numarası İle Sınıf İsmi (Arasında Boşluk Olmadan)
 - ```/lessonId```: Kacıncı Ders Olduğu
 - ```/day1```: 1. Günki x. Ders
 - ```/day2```: 2. Günki x. Ders
 - ```/day3```: 3. Günki x. Ders
 - ```/day4```: 4. Günki x. Ders
 - ```/day5```: 5. Günki x. Ders
 - ```/day1Teacher```: 1. Günki x. Dersin Öğretmeni 
 - ```/day2Teacher```: 2. Günki x. Dersin Öğretmeni 
 - ```/day3Teacher```: 3. Günki x. Dersin Öğretmeni 
 - ```/day4Teacher```: 4. Günki x. Dersin Öğretmeni 
 - ```/day5Teacher```: 5. Günki x. Dersin Öğretmeni



# Developer
 - [fireganqQ](https://github.com/fireganqQ) Geliştirmeler İçin Teşekkür Ederiz.
 - **Teknofest2022**
