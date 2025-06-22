#  Betting Coupon Test Automation (iddaa-case)

Bu proje, bir bahis sağlayıcısına ait kiosk sistemi üzerinden spor müsabakalarına yapılan bahis işlemlerini test etmek amacıyla geliştirilmiş bir **Selenium + Cucumber** tabanlı otomasyon frameworküdür.

##  Proje Yapısı

```
iddaa-case/
├── .github/
│   └── workflows/
├── src/
│   ├── test/
│   │   ├── java/
│   │   │   ├── pages/
│   │   │   ├── runner/
│   │   │   ├── stepdefinitions/
│   │   │   └── utils/
│   │   └── resources/
│   │       └── features/
├── target/
├── pom.xml
└── README.md
```

##  Kullanılan Teknolojiler

- Java 11
- Selenium WebDriver
- Cucumber (BDD)
- JUnit 4
- Maven
- Allure Report
- GitHub Actions (CI/CD)

##  Kurulum & Çalıştırma

1. Bu projeyi klonlayın:
   ```bash
   git clone https://github.com/ismailcemrek/iddaa-case.git
   cd iddaa-case
   ```

2. Maven bağımlılıklarını yükleyin:
   ```bash
   mvn clean install
   ```

3. Testleri çalıştırın:
   ```bash
   mvn test
   ```

4. Allure raporunu görüntüleyin:
   ```bash
   allure serve target/allure-results
   ```

##  Notlar

- `DriverManager` sınıfı, testlerin **headless modda** çalışmasını CI/CD süreçleri için destekler.
- IntelliJ'de testleri `TestRunner.java` dosyası üzerinden başlatabilirsiniz.

##  Geliştirici

**İsmail Cemrek**  
[GitHub Profilim](https://github.com/ismailcemrek)
