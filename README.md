
# 🃏 Strategic Card Battle Game – Java (OOP + Swing)

This is a Java-based strategic card battle simulation game developed as a Programming Lab II project. The game showcases object-oriented programming (OOP) concepts such as inheritance, encapsulation, and polymorphism in a practical and visual environment using Java Swing.

---

## 🎮 Game Concept

Two opponents — a human player and the computer — engage in a strategic battle using cards that represent land, air, and sea vehicles. Each card carries attributes such as health, attack power, and level score. After five rounds, the player with the highest score wins.

---

## 🛠️ Technologies Used

- **Language**: Java
- **OOP Principles**: Inheritance, Encapsulation, Polymorphism
- **GUI Library**: Java Swing
- **IDE**: IntelliJ IDEA

---

## 🚀 Game Features

- 🎴 Multiple unit types (Air, Land, Sea vehicles)
- 🔄 Randomized card distribution
- 🧠 AI logic for opponent moves
- 💥 Dynamic health and attack calculations
- 🖼️ Visual card interface using images
- 📊 Score tracking and result declaration
- 📃 Game log exported to `oyun.txt`

---

## 🧱 Object-Oriented Structure

| Class        | Description                                                   |
|--------------|---------------------------------------------------------------|
| `savasarac`  | Abstract base class for all vehicle types                     |
| `ucak`       | Air vehicle subclass with bonus against land units            |
| `karaarac`   | Ground unit with balanced attack/defense                      |
| `denizarac`  | Sea unit with high durability                                 |
| `oyun`       | Main game logic and turn flow                                 |
| `swingArayuz`| GUI interface using Java Swing                                |

---

## 🧩 Game Flow

1. Players are dealt 6 random cards
2. Each round: players select one card to battle
3. Cards are compared based on type and attributes
4. Damage and score are calculated
5. After 5 rounds or no cards left, the player with the highest score wins

---
![WhatsApp Image 2025-11-03 at 01 42 36](https://github.com/user-attachments/assets/74d5e707-5573-470c-badf-7050ff6a119f)
![WhatsApp Image 2025-11-03 at 01 42 36 (1)](https://github.com/user-attachments/assets/8b2188c1-e335-4545-9e3a-4aeffdd9ca07)
---



## 🇹🇷 Türkçe Açıklama – Java ile Stratejik Kart Oyunu

Bu proje, Java dili ile geliştirilen ve Nesneye Yönelik Programlama (NYP) ilkelerinin uygulandığı bir kart savaşı simülasyonudur. Oyunda kara, hava ve deniz araçlarını temsil eden kartlar, oyuncu ve bilgisayar arasında stratejik şekilde karşılaştırılır.

---

### Özellikler

- Farklı türde kartlar: Kara, Hava, Deniz araçları
- Kalıtım, kapsülleme ve çok biçimlilik (NYP) yapıları
- Java Swing ile görsel kullanıcı arayüzü
- Kart karşılaştırma, hasar hesaplama, skor takibi
- `oyun.txt` dosyasına oyun kaydı
- 5 tur sonunda en çok puanı alan kazanır

---

### Sınıf Yapısı

- `savasarac`: Soyut üst sınıf
- `ucak`, `karaarac`, `denizarac`: Alt sınıflar
- `swingArayuz`: Kullanıcı arayüz sınıfı
- `oyun`: Oyun başlangıcı ve akış kontrolü

---

### Nasıl Çalıştırılır?

1. IntelliJ IDEA veya başka bir Java IDE ile açın
2. Projeyi çalıştırın (`oyun.java` içinde `main()` metodu)
3. Kartları seçin ve savaşı başlatın!

---

### Ekip Üyeleri

- 👩‍💻 Rahime Uysal – Arayüz, sınıf yapıları, testler
- 👩‍💻 Zeynep Vuslat Solmaz – Oyun akışı, algoritmalar, raporlama

---

