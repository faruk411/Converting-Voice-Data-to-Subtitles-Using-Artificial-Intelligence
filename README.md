# Converting-Voice-Data-to-Subtitles-Using-Artificial-Intelligence

 Elimde olan Yaklaşık 195.000 ses dosyasından oluşan bir İngilizce veri setinin 50.000 'ni kullanarak eğittiğim Speech-to-Text (ASR) projemde nihayet hedeflediğim seviyeye ulaştım.

Kendi bilgisayarımda, RTX 3050 Ti (4GB VRAM) ekran kartımı kullanarak gerçekleştirdiğim bu süreçte, OpenAI’ın Whisper-Base modelini LoRA (Low-Rank Adaptation) tekniğiyle optimize ettim.

50.000 veri kullanabilmemim sebebi kısıtlı donanım imkanlarıydı.

##Proje Detayları ve Teknik Metrikler:

Model: OpenAI Whisper-Base

Teknik: LoRA Fine-Tuning (Hafıza verimliliği için)

Veri Seti: ~195,000 İngilizce ses kaydı

Donanım: NVIDIA RTX 3050 Ti Laptop GPU

Hata Oranı (WER): Başlangıçtaki yüksek hata oranlarını aşarak %9.97 seviyesine indim. (Bu değer, modelin neredeyse %90 oranında hatasız transkripsiyon yapabildiği anlamına geliyor!)

## Modelin çıktıları 

<img width="806" height="220" alt="Ekran görüntüsü 2026-02-16 231555" src="https://github.com/user-attachments/assets/4a4bc71c-dcb2-40cb-a05e-e0e175028265" />





<img width="631" height="188" alt="Ekran görüntüsü 2026-02-16 112404" src="https://github.com/user-attachments/assets/953a8356-ab0a-409d-bdd0-bb7de01b86b7" />

