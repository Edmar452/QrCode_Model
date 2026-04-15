# 🚀 SolvyrStudio - Gerador de QR Code

Aplicação web simples, rápida e eficiente para geração de QR Codes a partir de textos ou links.

Desenvolvido com foco em **usabilidade**, **compatibilidade com dispositivos móveis** e **funcionamento offline (sem dependência de bibliotecas locais)**.

---

## 📸 Preview

Gerador de QR Code com interface moderna (dark mode), otimizado para leitura por câmera de celular.

---

## ✨ Funcionalidades

* 🔗 Gerar QR Code a partir de texto ou URL
* 📱 Otimizado para leitura em celular
* 💾 Salvar QR Code no navegador (localStorage)
* 📥 Download do QR Code em PNG
* 🎨 Interface moderna (SolvyrStudio UI)
* ⚡ Funciona sem backend
* 🌐 Funciona abrindo direto no navegador

---

## 🛠️ Tecnologias utilizadas

* HTML5
* CSS3 (Custom Properties / Responsivo)
* JavaScript Vanilla
* API externa para geração de QR Code

---

## 📂 Estrutura do projeto

```bash
.
├── index.html
└── README.md
```

---

## 🚀 Como usar

### 🔹 1. Clonar o repositório

```bash
git clone https://github.com/Edmar452/QrCode_Model.git
```

---

### 🔹 2. Abrir o projeto

Você pode simplesmente abrir o arquivo:

```bash
index.html
```

Ou rodar localmente (recomendado):

```bash
npx serve
```

ou

```bash
python -m http.server
```

---

### 🔹 3. Gerar QR Code

1. Digite ou cole um link/texto
2. Clique em **"Gerar QR Code"**
3. Faça download ou salve

---

## 💡 Como funciona

O sistema utiliza uma API pública para gerar QR Codes dinamicamente:

```
https://api.qrserver.com/v1/create-qr-code/
```

Isso garante:

* Melhor compatibilidade
* Alta qualidade de leitura
* Menos dependência de bibliotecas locais

---

## ⚠️ Observações importantes

* O QR Code depende da validade do link inserido
* Se o link deixar de existir, o QR também perde função
* O salvamento é feito apenas no navegador (localStorage)

---

## 🔮 Melhorias futuras

* 📷 Leitura de QR Code via câmera
* ☁️ Armazenamento em nuvem
* 📊 Analytics de scans
* 🎯 QR Code dinâmico (editável)
* 🧩 Inserção de logo no QR

---

## 🏢 Sobre

Projeto desenvolvido por:

**SolvyrStudio**
Soluções digitais modernas e eficientes.

---

## 📄 Licença

Este projeto está sob a licença MIT.
Sinta-se livre para usar, modificar e distribuir.

---

## 🤝 Contribuição

Pull requests são bem-vindos!
Para mudanças maiores, abra uma issue primeiro.

---

## 📬 Contato

Se quiser evoluir esse projeto ou transformar em um produto real (SaaS):

👉 Entre em contato ou contribua no repositório

---

⭐ Se esse projeto te ajudou, deixe uma estrela!
