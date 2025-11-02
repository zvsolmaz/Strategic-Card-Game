
# 🃏 Strategic Card Battle Game – Java (OOP + Swing)
 
Developed by: **Rahime Uysal** & **Zeynep Vuslat Solmaz**  


---

## 🎮 Game Overview

Strategic Card Battle is a turn-based Java game simulating a battle between a player and the computer using vehicle cards categorized as land, air, and sea. Each card has distinct attributes such as:

- Health Points (HP)
- Attack Power
- Type Advantage

Victory is determined after 5 rounds based on accumulated score.

---

## 💡 Educational Purpose

This project demonstrates:
- Object-Oriented Programming (OOP) principles:
  - Inheritance
  - Polymorphism
  - Encapsulation
- Java GUI development with **Swing**
- Class-based game logic and modular structure

---

## 🛠️ Technologies

- **Language:** Java
- **GUI Library:** Swing
- **IDE:** IntelliJ IDEA / NetBeans
- **OOP Concepts Used:** ✔️

---

## 🧠 Classes Overview

| Class          | Description                                      |
|----------------|--------------------------------------------------|
| `savasarac`    | Abstract base class for vehicle cards            |
| `ucak`         | Air vehicle, strong against ground               |
| `karaarac`     | Ground vehicle, balanced stats                   |
| `denizarac`    | Sea vehicle, strong against air units            |
| `oyun`         | Main logic: game flow, round handling            |
| `swingArayuz`  | GUI components and visual feedback               |

---

## 🧩 Game Mechanics

1. Each player is dealt 6 random cards.
2. Players take turns choosing a card.
3. Type advantages are:
   - Air > Ground
   - Ground > Sea
   - Sea > Air
4. Damage and score are calculated.
5. Game ends in 5 rounds. Highest score wins.

---

## 🖼️ Screenshots

![Game Screen 1](https://github.com/user-attachments/assets/74d5e707-5573-470c-badf-7050ff6a119f)
![Game Screen 2](https://github.com/user-attachments/assets/8b2188c1-e335-4545-9e3a-4aeffdd9ca07)

---

## 🗂️ Project Folder Structure

```plaintext
card-game/
├── src/
│   ├── savasarac.java
│   ├── ucak.java
│   ├── karaarac.java
│   ├── denizarac.java
│   ├── oyun.java
│   └── swingArayuz.java
├── assets/              # Card images
├── oyun.txt             # Game logs
└── README.md
```

---

## 🏗️ How to Run

1. Open project in IntelliJ IDEA or NetBeans
2. Run `main()` in `oyun.java`
3. Choose cards and play 5 rounds

---

## 🇹🇷 Türkçe – Stratejik Kart Savaşı Oyunu

Java dili ve Swing arayüzüyle geliştirilen bu oyunda, oyuncu ve bilgisayar kara, hava ve deniz araçlarını temsil eden kartlarla 5 tur boyunca mücadele eder. Her kart farklı saldırı gücüne, cana ve avantaja sahiptir.

---

### Özellikler

- OOP prensiplerine dayalı sınıf yapısı
- Swing ile görsel kullanıcı arayüzü
- Kart türü karşılaştırması ve puan sistemi
- Her turun sonucu `oyun.txt` dosyasına kaydedilir
- Oyun sonunda en yüksek skora sahip oyuncu kazanır

---

### Sınıf Yapısı

- `savasarac`: Soyut ana sınıf
- `ucak`, `karaarac`, `denizarac`: Kart tipleri
- `oyun`: Oyun döngüsü ve karar mekanizması
- `swingArayuz`: Kullanıcı arayüzü yönetimi

---

### Nasıl Çalıştırılır?

1. Projeyi IntelliJ IDEA veya NetBeans ile açın
2. `oyun.java` içinden çalıştırın
3. Kart seçin ve 5 tur boyunca mücadele edin

---

### Geliştiriciler

- 👩‍💻 **Rahime Uysal** – Arayüz, sınıflar, test
- 👩‍💻 **Zeynep Vuslat Solmaz** – Algoritmalar, oyun akışı, rapor

---
