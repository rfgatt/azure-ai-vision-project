# ✉️ Reconhecimento de Texto em Imagem (OCR)

Este projeto demonstra a extração de texto a partir de uma imagem contendo uma **carta de agradecimento**. Utilizamos um serviço de **OCR (Optical Character Recognition)** para converter o texto da imagem em um formato editável e estruturado.

---

## 📌 Tecnologias Utilizadas
- **Azure AI Vision - OCR**
- **Python para processamento de JSON (opcional)**
- **GitHub para versionamento e documentação**

---

## 📷 Imagem de Entrada
A imagem original utilizada no teste está na pasta [`inputs/`](inputs/).

Exemplo:
![Carta de Agradecimento](inputs/letter.jpg)

---

## 📄 Resultado da Extração de Texto (OCR)
O texto extraído da imagem foi salvo na pasta [`outputs/`](outputs/) nos seguintes formatos:
1. **`text_output.txt`** → Contém a transcrição do texto da carta.
2. **`ocr_results.json`** → Contém os detalhes do OCR, como posições de palavras e nível de confiança.

### 🔹 **Trecho da Transcrição extraída**
```txt
January 23rd 2020

For the attention of:
The manager
Northwind Traders
123 Any Street
Bellevue, WA

Dear Sir or Madam,

I am writing to thank you for the fantastic service I received at your store on January 20th.
...
Sincerely,  
A Customer

