# SE2009 Lab 00: Exercism C Practice

## English

### Purpose

This is the first SE2009 lab assignment. There is no PreLab for this assignment.

You will practice the C programming language through the official Exercism C track. The current C track contains **85 practice exercises**. You are expected to complete all 85 exercises during this assignment period.

Exercism C track: https://exercism.org/tracks/c

### Deadline

The deadline is **Tuesday at 23:59**, before the next Wednesday lab period begins.

The instructor will check the submissions after the deadline. Work completed after the deadline may be recorded as late according to the course rules.

### What to do

1. Create or use your own Exercism account.
2. Join the C track.
3. Solve all **85 practice exercises** currently listed in the C track.
4. Make sure each exercise passes the Exercism tests.
5. Keep your solutions in your own Exercism account.
6. Prepare one Word document containing the required written evidence.
7. Submit both the Exercism profile/track link and the offline Word file.

### What to submit

Submit all of the following:

- Your Exercism profile or C-track progress link.
- A link that allows the instructor to view your progress and solutions, when Exercism permissions support it.
- One offline Word file (`.docx`) containing the written report.
- The same Word file in OneDrive, shared as: anyone with the link can view and download; editing is disabled.
- The final GitHub commit link if the course repository is used for the submission record.

Do not share passwords, tokens, recovery codes, or two-factor authentication codes.

### Word report format

The Word document must contain one section for each exercise. Use this structure:

1. Exercise number and name
2. Exercism exercise link
3. Short explanation of the problem
4. Your solution approach
5. Important C concepts used
6. Code block or a link to your solution
7. Test/result evidence
8. A short reflection: what was difficult and what you learned

Do not paste only screenshots. Text, code, and explanations must be selectable in the Word document.

### Example: Exercise 1 - Hello World

Exercism link: https://exercism.org/tracks/c/exercises/hello-world

#### Problem summary

Write a C function that copies the text `Hello, World!` into the provided output buffer.

#### Example solution approach

- Include the required header for string copying.
- Copy the exact expected text into the buffer.
- Return the buffer so the caller can use the result.
- Run the Exercism test suite and confirm that all tests pass.

#### Example code format

```c
#include <string.h>

char *hello(void) {
    static char message[] = "Hello, World!";
    return message;
}
```

The exact function signature and starter files provided by Exercism must be followed. The code above is only a formatting example; use the current exercise instructions and tests in your own workspace.

#### Example result

- Exercise: Hello World
- Result: All Exercism tests passed
- What I learned: how to return a string from a C function and how the test suite checks the required output.

### Completion table

| Range | Requirement | Evidence |
|---|---|---|
| 1-85 | All C practice exercises completed | Exercism progress link |
| 1-85 | Tests pass | Exercism test status / screenshots where needed |
| 1-85 | Written explanation included | Word report |

### Final checklist

- [ ] All 85 current Exercism C practice exercises are completed.
- [ ] The Exercism progress/profile link is included.
- [ ] Each exercise has a written explanation in the Word report.
- [ ] Code and test evidence are included.
- [ ] The OneDrive link allows viewing and downloading without an extra permission request.
- [ ] Editing is disabled on the OneDrive link.
- [ ] The offline `.docx` file matches the OneDrive version.
- [ ] The deadline is Tuesday 23:59.
- [ ] No password, token, recovery code, or two-factor authentication code is included.

---

# SE2009 Lab 00: Exercism C Calismalari

## Amac

Bu, SE2009 dersinin ilk lab odevdir. Bu odev icin PreLab yoktur.

C programlama dilini resmi Exercism C track'i uzerinden calisacaksiniz. Guncel C track'inde **85 practice exercise** bulunmaktadir. Bu odev doneminde 85 egzersizin tamaminin tamamlanmasi beklenmektedir.

Exercism C track: https://exercism.org/tracks/c

## Son teslim tarihi

Son teslim tarihi, bir sonraki Carsamba lab saati baslamadan onceki **Sali gunu saat 23:59**'dur.

Ders sorumlusu kontrolleri son teslim saatinden sonra yapacaktir. Son teslimden sonra tamamlanan calismalar ders kurallarina gore gec teslim olarak kaydedilebilir.

## Yapilacaklar

1. Kendi Exercism hesabinizi olusturun veya mevcut hesabinizi kullanin.
2. C track'ine katilin.
3. C track'inde bulunan guncel **85 practice exercise** egzersizinin tamamini cozun.
4. Her egzersizin Exercism testlerinden gectigini kontrol edin.
5. Cozumlerinizi kendi Exercism hesabinizda tutun.
6. Istenen yazili kanitlari iceren tek bir Word dosyasi hazirlayin.
7. Hem Exercism profil/track baglantisini hem de offline Word dosyasini teslim edin.

## Teslim edilecekler

- Exercism profiliniz veya C track ilerleme baglantiniz.
- Exercism izinleri destekliyorsa ilerlemenizi ve cozumlerinizi gosteren goruntulenebilir baglanti.
- Yazili raporu iceren offline Word dosyasi (`.docx`).
- Ayni Word dosyasinin OneDrive surumu: baglantiya sahip herkes goruntuleyebilir ve indirebilir; duzenleme kapali olmalidir.
- Ders deposu teslim kaydi kullaniliyorsa son GitHub commit baglantisi.

Parola, token, kurtarma kodu veya iki asamali dogrulama kodu paylasmayin.

## Word raporu bicimi

Word dosyasinda her egzersiz icin ayri bir bolum bulunmalidir:

1. Egzersiz numarasi ve adi
2. Exercism egzersiz baglantisi
3. Problemin kisa ozeti
4. Cozum yaklasiminiz
5. Kullanilan onemli C kavramlari
6. Kod blogu veya cozum baglantisi
7. Test/sonuc kaniti
8. Kisa degerlendirme: ne zordu ve ne ogrendiniz

Yalnizca ekran goruntusu yapistirmayin. Word dosyasindaki metin, kod ve aciklamalar secilebilir olmalidir.

## Ornek: 1. Egzersiz - Hello World

Exercism baglantisi: https://exercism.org/tracks/c/exercises/hello-world

### Problem ozeti

Verilen cikti tamponuna `Hello, World!` metnini kopyalayan bir C fonksiyonu yazin.

### Ornek cozum yaklasimi

- Metin kopyalama icin gerekli baslik dosyasini ekleyin.
- Beklenen metni tam olarak tampona kopyalayin.
- Cagrilan kodun sonucu kullanabilmesi icin tamponu dondurun.
- Exercism testlerini calistirin ve tum testlerin gectigini kontrol edin.

### Ornek kod bicimi

```c
#include <string.h>

char *hello(void) {
    static char message[] = "Hello, World!";
    return message;
}
```

Exercism tarafindan verilen guncel fonksiyon imzasi ve starter dosyalar kullanilmalidir. Yukaridaki kod yalnizca bicim ornegidir; kendi calisma alaninizdaki guncel egzersiz aciklamalarini ve testleri esas alin.

### Ornek sonuc

- Egzersiz: Hello World
- Sonuc: Tum Exercism testleri gecti
- Ne ogrendim: C fonksiyonundan string dondurme ve test suitinin beklenen ciktiyi kontrol etmesi.

## Tamamlama tablosu

| Aralik | Gereklilik | Kanit |
|---|---|---|
| 1-85 | Tum C practice exercise egzersizleri tamamlandi | Exercism ilerleme baglantisi |
| 1-85 | Testler gecti | Exercism test durumu / gerektiginde ekran goruntuleri |
| 1-85 | Yazili aciklama eklendi | Word raporu |

## Son kontrol listesi

- [ ] Guncel 85 Exercism C practice exercise egzersizinin tamami tamamlandi.
- [ ] Exercism ilerleme/profil baglantisi eklendi.
- [ ] Her egzersiz icin Word raporuna yazili aciklama eklendi.
- [ ] Kod ve test kanitlari eklendi.
- [ ] OneDrive baglantisi ek izin istemeden goruntuleniyor ve indirilebiliyor.
- [ ] OneDrive duzenleme izni kapali.
- [ ] Offline `.docx` dosyasi OneDrive surumuyle ayni.
- [ ] Son teslim tarihi Sali 23:59 olarak kontrol edildi.
- [ ] Parola, token, kurtarma kodu veya iki asamali dogrulama kodu eklenmedi.

Bu dosya onay taslagidir; onaydan sonra `se2009-26` organizasyonundaki ilgili private Lab 00 template deposuna yuklenecektir.
