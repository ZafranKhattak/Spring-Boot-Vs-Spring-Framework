# Spring-Boot-Vs-Spring-Framework

# Spring Se Pehle Kya Hota Tha?
* Problem 1 - Bahut Sara Boilerplate Code
* Problem 2 - Object Banana
* Engine engine = new Engine();
  Car car = new Car(engine);
* Problem 3 - Configuration (<bean id="car" class="Car"/>)
* Problem 4 - Database Setup
Database connect karna easy nahi tha.
                    * Driver
                    * URL
                    * Username
                    * Password
                    * Queries
                    * Connection Close
                    * Exception Handling
Sab manually Har project me.
* Problem 5 - Dependency Management
Project me agar 20 libraries use karni hon.
                   * Sab download karo.
                   * Version check karo.
                   * Conflict solve karo.
  
# To Spring Ne Kya Kiya?
* Spring ne kaha:
* Developer...
* Tum business logic likho.

Baaki boring kaam main karunga. 
# Spring Framework
* Socho tum ghar bana rahe ho.
Spring Framework mein tumhein har cheez khud setup karni parti hai.

* Cement khud lao
* Eent khud lao
* Wiring khud karo
* Plumbing khud karo

Yani configuration zyada hoti hai.
Java mein iska matlab:

* Dependencies khud add karni
* XML ya Java Config likhni
* Tomcat configure karna
* Bean configuration karni
  
Is liye Spring powerful hai, lekin setup mein time lagta hai.

# Spring Boot

Ab socho koi company tumhein Ready Made House Kit de.
Us mein:

* Wiring already
* Plumbing already
* Doors already
* Windows already

Tum sirf furniture rakho aur rehna shuru karo.
Yehi Spring Boot hai.
Spring Boot = Spring Framework + Automatic Configuration + Easy Setup

# Real Difference
Spring
Developer:
- Configuration
- Dependencies
- Server setup
- Bean setup
- Project setup

Developer ka bohat time setup mein chala jata hai.

# Spring Boot
Developer:
- Business Logic
- Controllers
- Services
- Repository

Baqi ka kaam Spring Boot khud kar deta hai

| Without Spring         | With Spring               |
| ---------------------- | --------------------------- |
| Manual Object Creation | Automatic Object Management |
| Zyada Configuration    | Easy Configuration          |
| Repeat Code            | Reusable Code               |
| Hard Maintenance       | Easy Maintenance            |
| Time Zyada             | Time Kam                    |
| Errors Zyada           | Errors Kam                  |

# Boilerplate Code
* Wohi code jo har project me baar baar likhna padta hai.

# Framework Kya Hota Hai?
Framework matlab:
Ready-made structure.
Example:
Tum ghar banana chahte ho.
Framework tumhe de deta hai:
* Design
* Rooms
* Foundation
Tum sirf apni zarurat ke hisab se changes karte ho.
Software me bhi framework ready structure provide karta hai.
Framework ke andar tum kaam karte ho.
Framework decide karta hai kab kya chalega.
Matlab:
👉 Control framework ke paas hota hai.

| Department | Kaam                      |
| ---------- | ------------------------- |
| Core       | Objects manage karta hai  |
| Security   | Login handle karta hai    |
| Data       | Database handle karta hai |
| Web        | Website banata hai        |
| Test       | Testing karta hai         |
