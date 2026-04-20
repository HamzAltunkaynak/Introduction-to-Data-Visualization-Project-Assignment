# 🤖 AI Destekli Metin Analiz ve Karar Sistemi

Bu proje, seçilen metinleri analiz ederek kullanıcıya hızlı ve anlamlı çıktılar sunan bir **AI destekli karar destek sistemidir**.

Sistem, özellikle ofis çalışanlarının metinleri yorumlamasını kolaylaştırmak ve zaman kazandırmak amacıyla geliştirilmiştir.

---

## 🚀 Özellikler

### 📊 İş Metni Analizi

- 📌 Durum Özeti  
- ⚠️ Riskler  
- 💡 Önerilen Aksiyonlar  
- 🔥 Öncelik Seviyesi  

---

### 🧠 Akıllı Analiz (Otomatik)

- Metin türünü otomatik algılar  
- Gereksiz bilgi vermez  
- Tek ve net çıktı üretir  
- Karar destek odaklıdır  

---

## ⚡ Kullanım

1. Metni seç  
2. `F8` tuşuna bas  
3. Menüden işlem seç  
4. Sonuç ekranda görüntülenir  

---

## 🧰 Kurulum ve Gereksinimler

### Gereksinimler

- Python 3.10+  
- Ollama  

---

### Kurulum

```bash
git clone https://github.com/HamzAltunkaynak/ai-text-analyzer.git
cd ai-text-analyzer

python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt

ollama run gemma3:1b

python main.pyw