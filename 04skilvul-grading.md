START

SET Nilai Awal 

IF nilai <= 59 THEN
        Huruf = "E"
        komentar = "Nilai anda kurang! Maaf, anda gagal"
ELSE IF Nilai <=65 THEN
        huruf = "D"
        komentar = "Nilai anda kurang! Maaf, anda gagal"
ELSE IF Nilai <= 77
        Huruf ="C"
        komentar = "nilai anda cukup! anda lulus, tingkatkan lagi"
ELSE IF Nilai <85 THEN
        Huruf = "B"
        Komentar = "Nilai anda baik! anda lulus pertahakan nilai anda"
ELSE IF Nilai >85 THEN
        Huruf = "A"
        Komentar = "Nilai anda sangat memuaskan!"

END IF 
textHuruf.txt = Huruf
TextKomentar.txt = Komentar

END