📚 Library Management System (C# WinForms)

C# WinForms ve SQL Server ile geliştirilmiş bir kütüphane yönetim sistemi.
Öğrenci, personel ve admin rolleri ile kitap yönetimi, ödünç alma ve raporlama işlemleri yapılabilir.

Özellikler:

Öğrenci: Kitap arama, ödünç alma, iade, geçmişi görüntüleme
Personel: Talepleri onaylama, kitap teslimi, günlük rapor
Admin: Kitap ekle/güncelle/sil, istatistik ve en çok ödünç alınan kitaplar

Tasarım Desenleri:

State Pattern: Ödünç alma durumu yönetimi (Pending → Approved → Delivered → Returned)
Strategy Pattern: Kitap arama/filterleme (kategori, yazar)
