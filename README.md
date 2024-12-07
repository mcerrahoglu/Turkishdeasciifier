## Turkishdeasciifier
**Deasciifier**, eksik Türkçe aksanlı karakterleri ekleyerek ASCII formatındaki Türkçe metinleri doğru şekilde Türkçeleştirir.

## Deasciifier - Python 3 Uyumu ve Jupyter Lab Desteği

Bu proje, **[Deasciifier](https://deasciifier.com)** projesinin Python 3 uyumlu versiyonudur ve Jupyter Lab gibi ortamlarda kullanılabilir hale getirilmiştir. 

Bu repo, Python 3 uyumlu bir versiyonu içermektedir.

## Proje Sahipleri

- Deniz Yuret, Türkçe aksan düzeltme için orijinal Deasciifier'ı geliştirmiştir.
- Bu sürümde, Python 3 uyumlu hale getirilmiş ve Jupyter Lab ile çalışacak şekilde optimize edilmiştir.

## Kurulum ve Kullanım

### Gereksinimler

- **Python 3.x** (Python 3.6 ve üzeri)
- **Jupyter Lab** (Jupyter Notebook da kullanılabilir)

### Kurulum Adımları

1. Repository'yi klonlayın:

```bash
git clone https://github.com/mcerrahoglu/Turkishdeasciifier.git
cd Turkishdeasciifier 
```
2. Deasciifier'ı kullanmak için Python kodu şu şekilde olabilir:
```bash
from deasciifier import Deasciifier

ascii_text = "bü kod entegre hale getirılmıştır"
deasciifier = Deasciifier()
turkish_text = deasciifier.deasciify(ascii_text)
print("Türkçe Metin:", turkish_text)
```
## Çalışma Prensibi

- Deasciifier sınıfı, ASCII metinlerindeki Türkçe karakter eksikliklerini tamamlar.
- Bu sürüm, Python 3 ve Jupyter Lab ortamlarıyla uyumludur.

## Farklı Dillerde Derleme

- Farklı dillerde kullanım için bu repository incelenebilir [Original Repository](https://github.com/meacer/deasciifier)

## Web Sitesi ve Eklentiler

Orijinal projenin web sitesi ve eklentilerine aşağıdaki bağlantılardan ulaşabilirsiniz:

- [Web Sitesi](deasciifier.com) 
- [Chrome Eklentisi](https://chromewebstore.google.com/detail/turkish-deasciifier/nhfdmlgglfmcdheoabgklabmgjklgofk) 
- [Firefox Eklentisi](https://addons.mozilla.org/en-US/firefox/addon/deasciifier/) 
