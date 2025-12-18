# sistem
gantt
    title Zaman Bankası Projesi - Geliştirme Takvimi
    dateFormat  YYYY-MM-DD
    axisFormat  %W. Hafta
    excludes    weekends

    section Ay 1: Temel & Kimlik
    Sprint 0 (Hazırlık & Tasarım)       :done,    s0, 2025-10-01, 2w
    Sprint 1 (Kimlik Yönetimi - 40SP)   :active,  s1, after s0, 2w

    section Ay 2: İlan & Arama
    Sprint 2-3 (İlan Modülü - 65SP)     :         s2, after s1, 4w
    Sprint 4 (Arama & Keşfet - 35SP)    :         s4, after s2, 2w
    
    section Vize Haftası
    Sınav Molası (Sprint Arası)         :crit,    h1, after s4, 1w

    section Ay 3: Çekirdek Fonksiyonlar
    Sprint 5-6 (Cüzdan & QR - 80SP)     :         s5, after h1, 4w
    Sprint 7 (Lokasyon/Güv. - 50SP)     :         s7, after s5, 2w

    section Ay 4: Etkileşim
    Sprint 8 (İletişim - 60SP)          :         s8, after s7, 2w
    Sprint 9 (Gamification - 40SP)      :         s9, after s8, 2w

    section Ay 5: Finalizasyon
    Sprint 10 (Stabilizasyon - 30SP)    :         s10, after s9, 2w
    Sprint 11 (Pilot / Beta Test)       :         s11, after s10, 2w
    
    section Ay 6: Lansman
    Sprint 12 (Lansman & Etkinlik)      :milestone, m1, after s11, 0d
    
