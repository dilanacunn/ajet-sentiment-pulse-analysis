# Ajet Sentiment Pulse Analysis

Bu projede, Bilet.com'dan çekilen 50 adet Ajet müşteri yorumu kullanılarak Türkçe duygu analizi yapılmıştır. Yorumlar beş farklı kategoriye ayrılmış, her biri için sentiment skoru hesaplanmış ve pulse skoru ile analiz edilmiştir.

## Kullanılan Araçlar
- Python
- Pandas
- BeautifulSoup
- Transformers (BERT)
- Matplotlib

## Kategoriler
- Uçuş Arama Deneyimi
- Destinasyonlar
- Ödeme / Biletleme
- Ücret Politikası
- Uçuş Deneyimi

## Yöntem
1. Web scraping ile yorumlar çekildi
2. Anahtar kelimelerle kategori sınıflandırması yapıldı
3. BERT tabanlı Türkçe NLP modeli ile sentiment analizi uygulandı
4. Pulse skorları hesaplandı ve grafikle görselleştirildi
