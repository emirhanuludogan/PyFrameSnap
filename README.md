# PyFrameSnap

YouTube linklerinden video indirip belirlenen sayıda kareye (frame) bölen pratik bir Python aracıdır. OpenCV ve yt-dlp kütüphanelerini kullanır.

## Kullanım

1. `requirements.txt` dosyasını kullanarak gerekli bağımlılıkları yükleyin:
   ```bash
   pip install -r requirements.txtScripti çalıştırın:

Bash
python frame_extractor.py
YouTube linkini girin, program otomatik olarak extracted_frames klasörüne kareleri kaydedecektir.Özellikler
Otomatik Kare Ayıklama: 800 kare hedefine göre videoyu otomatik böler.

Düşük Depolama: İşlem sonrası video dosyasını otomatik siler.

Hata Yönetimi: Ağ sorunlarına karşı dayanıklıdır.
