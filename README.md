# ✈️ Airline Flights Data Analysis

## 📌 Project Overview

Bu layihədə aviaşirkət uçuş məlumatları analiz edilmişdir. Məqsəd müxtəlif faktorların (aviaşirkət, uçuş sinfi, gün sayı, dayanacaqlar və s.) bilet qiymətlərinə təsirini araşdırmaqdır.

## 📊 Dataset

Layihədə istifadə olunan dataset aşağıdakı sütunlardan ibarətdir:

* `airline` — Aviaşirkətin adı
* `source_city` — Çıxış şəhəri
* `destination_city` — Təyinat şəhəri
* `departure_time` — Uçuş vaxtı
* `arrival_time` — Gəliş vaxtı
* `class` — Uçuş sinfi (Economy / Business)
* `duration` — Uçuş müddəti
* `stops` — Dayanacaq sayı
* `days_left` — Uçuşa qalan gün sayı
* `price` — Bilet qiyməti

## 🛠️ İstifadə olunan texnologiyalar

* Python 🐍
* Pandas 📊
* Jupyter Notebook 📓

## 🔍 Analysis Steps

Layihədə aşağıdakı analizlər aparılmışdır:

### 1. Aviaşirkət üzrə analiz

* Hər aviaşirkətin uçuş sayı
* Orta bilet qiymətləri
* Ən bahalı və ən ucuz şirkətlər

### 2. Sinif (Class) üzrə analiz

* Economy və Business siniflərinin qiymət fərqi
* Siniflər üzrə orta uçuş müddəti

### 3. Şəhərlər üzrə analiz

* Mənbə və təyinat şəhərlərinə görə orta qiymətlər
* Ən çox uçuş olan şəhər

### 4. Gün faktorunun təsiri

* `days_left` dəyişəninə görə qiymət dəyişimi
* Az qalan günlərdə qiymət artımı müşahidəsi

### 5. Dayanacaqların təsiri

* Stops sayına görə qiymət və müddət analizi

### 6. Qruplaşdırma

* Günlər intervala bölünərək (`0-10`, `11-20`, və s.) analiz edilmişdir

## 📈 Key Insights

* Uçuşa az gün qaldıqca qiymətlər artır 📈
* Business class biletlər Economy-dən xeyli bahadır 💸
* Daha çox dayanacaq olan uçuşlar adətən daha ucuzdur
* Aviaşirkətlər arasında ciddi qiymət fərqləri mövcuddur

## 📌 Nəticə

Bu layihə göstərir ki, uçuş qiymətləri bir çox faktordan asılıdır və düzgün analiz vasitəsilə bu faktorları aşkar etmək mümkündür.

---

## 👤 Author

Yaqub Rafiyev

