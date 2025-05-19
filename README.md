# 🎵 MusicGen Transformer

Bu projede, bir Transformer modeli kullanarak müzik üretimi gerçekleştirdim. Modelin eğitimi ve üretim süreci Google Colab ortamında gerçekleştirilmiştir.  
Veri olarak [Lakh MIDI Dataset (Clean)](https://www.kaggle.com/datasets/imsparsh/lakh-midi-clean) kullanılmış ve bu veri setinden rastgele seçilen 1988 adet `.mid` dosyasından oluşan bir alt küme oluşturulmuştur.

## 📁 Dosya Yapısı

- `midi_files/` — Rastgele seçilen 1988 adet `.mid` dosyasını içerir (veri seti)
- `musicgen_notebook.ipynb` — Eğitim ve üretim sürecini içeren Google Colab not defteri
- `outputWAV/` — Modelin ürettiği müziklerin `.wav` formatındaki çıktıları
- `sampleoutputJPG/` — MIDI dosyalarının nota görselleri

## 🚀 Kullanım

1. `musicgen_notebook.ipynb` dosyasını Google Colab ortamında aç
2. `midi_files/` klasörünü yükleyerek veriyi içe aktar
3. Gerekli Python kütüphanelerini kur (örnek: `torch`, `pretty_midi`, `music21`)
4. Not defterindeki hücreleri sırayla çalıştırarak modeli eğit ve müzik üret

## 🎧 Örnek Çıktılar

- `outputWAV/output1.wav`
- `outputWAV/output2.wav`
- Görseller: `sampleoutputJPG/`

---

## 📌 Not

- `midi_files/` klasörü içerisinde toplam 1988 adet `.mid` dosyası bulunmaktadır.
- Bu dosyaların içerisinden 600 tanesi modelin eğitimi için kullanılmıştır.

---

