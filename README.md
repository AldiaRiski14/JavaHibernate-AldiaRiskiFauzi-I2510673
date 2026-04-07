# JavaHibernate_Aldia Riski Fauzi_I.2510673


Aplikasi desktop CRUD (Create, Read, Update, Delete) untuk manajemen data karyawan menggunakan **Java 21 LTS**, **Hibernate ORM**, dan **MySQL Database**.
## 🧮 hasil
<img width="1483" height="958" alt="Screenshot 2026-04-07 222308" src="https://github.com/user-attachments/assets/3bda0940-2746-40ea-9274-49662ca52fe4" />


## 🔧 Prerequisites

Sebelum menjalankan aplikasi, pastikan sudah install:

| Komponen | Versi | 
|----------|-------|
| Java JDK | 21 LTS |
| Maven | 3.9.x |
| MySQL Server | 8.0+ |

```bash
# Verifikasi instalasi
java -version
mvn -version
mysql --version


## 🚀 How to Run

```bash
# Build & Compile
mvn clean compile

# Run Application
mvn exec:java
```

Aplikasi akan launch dengan GUI window.

---

## 📱 Features & Usage

| Operasi | Langkah |
|---------|---------|
| **CREATE** | Isi form → Click ➕ INSERT |
| **READ** | Auto-load saat start, double-click tabel untuk load ke form |
| **SEARCH** | Ketik NIP → Press ENTER |
| **UPDATE** | Load data → Edit field → Click ✏️ UPDATE |
| **DELETE** | Load data → Click 🗑️ DELETE → Confirm |
| **REFRESH** | Click 🔄 REFRESH untuk reload semua data |
| **CLEAR** | Click ❌ CLEAR untuk clear form |

---

## 📁 Project Structure

```
JavaPersistence/
├── src/main/java/javapersistence/
│   ├── Main.java                 # Entry point
│   ├── FormKaryawan.java         # UI Form & Table
│   ├── ControllerKaryawan.java   # Database Access
│   └── Karyawan.java             # Entity Model
├── src/main/resources/META-INF/
│   └── persistence.xml           # Hibernate Config
├── src/test/java/javapersistence/
│   └── AppTest.java              # Unit Tests
├── pom.xml                       # Maven Dependencies
└── setup-database.sql            # Database Script
```

---


## 📝 Notes

- ✅ **Zero compiler warnings** - Clean build
- ✅ **All tests passing** - 100% test pass rate  
- ✅ **Modern UI** - Professional design dengan JSplitPane & status bar
- ✅ **Proper error handling** - User-friendly dialogs & console logging

**Status:** Educational/Learning Purpose (tidak untuk production)

---

**Aldia Riski Fauzi**
