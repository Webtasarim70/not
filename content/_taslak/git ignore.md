
Benim önerim:

```
content/_drafts
```


Evet. Repo kökünde bir `.gitignore` dosyası varsa, içine şu satırı eklemen yeterli:

```
content/_drafts/
```

Sonrasında:

```
content/├── Blog Yazıları/├── Teknoloji/├── Günlük/└── _drafts/    ├── Taslak 1.md    └── Fikirler.md
```

şeklinde kullanabilirsin.

Kontrol etmek için terminalde:

```
git status
```

çalıştır. `_drafts` içindeki dosyalar listelenmiyorsa GitHub'a gönderilmeyecek demektir.

Eğer `.gitignore` dosyanın mevcut içeriğini paylaşırsan, Quartz/GitHub Pages yapına uygun şekilde tam halini hazırlayabilirim.