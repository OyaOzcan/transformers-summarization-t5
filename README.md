# Transformer ile Metin Özetleme

Bu proje, **T5 Transformer modeli** kullanarak haber metinlerini özetlemek için geliştirilmiştir. PyTorch ve Hugging Face Transformers kütüphaneleri kullanılarak model eğitilmiş ve test edilmiştir.

## Özellikler

- **T5 Modeli Kullanımı:** Metinleri özetlemek için **T5-small** modeli kullanılmıştır.
- **Veri Seti:** Haber metinlerinden oluşan bir veri kümesi üzerinde çalışılmıştır.
- **Model Eğitimi ve İnferansı:** Model, PyTorch kullanılarak eğitilmiş ve test edilmiştir.
- **Sonuçların Karşılaştırılması:** Modelin ürettiği özetler, gerçek özetlerle karşılaştırılmıştır.

## Kullanılan Teknolojiler

- **Python**
- **PyTorch**
- **Hugging Face Transformers**
- **Pandas, NumPy**
- **Matplotlib, Seaborn** (Görselleştirme için)

## Kurulum ve Kullanım

### Gerekli kütüphaneleri yükleyin:
```bash
pip install transformers torch pandas numpy matplotlib seaborn

### Jupyter Notebook’u çalıştırarak modeli test edin:

```bash
jupyter notebook transformers-summarization-t5.ipynb
