# 🚀 Gerador de QR Code Interativo

## ✨ Descrição

Este projeto é um gerador de QR Code interativo desenvolvido para demonstrar a criação e exibição de códigos QR de forma dinâmica. Ele permite aos usuários inserirem um texto ou URL e gerarem instantaneamente um QR Code correspondente. O objetivo principal é fornecer uma ferramenta simples e eficaz para a criação de QR Codes, ideal para compartilhamento de informações rápidas ou links.

**Principais tecnologias utilizadas:** HTML5, CSS3, JavaScript.

## 💡 Funcionalidades

* **Geração Dinâmica de QR Code:** Crie QR Codes em tempo real a partir de qualquer texto ou URL inserido pelo usuário.
* **Interface Intuitiva:** Design simples e fácil de usar, garantindo uma experiência de usuário agradável.
* **Download do QR Code:** (Adicione se for uma funcionalidade)
* **Responsividade:** (Adicione se for uma funcionalidade)

## 🏗️ Arquitetura

O projeto segue uma arquitetura **Front-end puro**, utilizando:

* **HTML:** Para a estruturação do conteúdo da página.
* **CSS:** Para a estilização e responsividade da interface.
* **JavaScript:** Para a lógica de geração do QR Code e interação com o usuário, utilizando a biblioteca `QRCode.js` para a manipulação do código QR.

A comunicação se dá diretamente no lado do cliente, sem a necessidade de um servidor backend.

## 🧩 Entidades

As principais "entidades" ou componentes lógicos deste projeto, do ponto de vista do domínio, são:

* **Entrada de Texto/URL:** O dado fornecido pelo usuário que será codificado no QR Code.
* **QR Code Gerado:** A imagem do código QR que é renderizada na tela.
* **Biblioteca `QRCode.js`:** A ferramenta central que processa a entrada e gera a representação visual do QR Code.

## 🛠️ Tecnologias Utilizadas

* **HTML5**
* **CSS3**
* **JavaScript**
* **[QRCode.js](https://davidshimjs.github.io/qrcodejs/)** - Biblioteca JavaScript para gerar QR Codes.

## ⚙️ Como Configurar e Executar o Projeto

Siga os passos abaixo para configurar e executar este projeto em sua máquina local:

### Pré-requisitos

Certifique-se de ter um navegador web moderno (como Chrome, Firefox, Edge, Safari) instalado.

### 1. Clonar o Repositório

```bash
git clone [https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git](https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git)
```

##
### 2. Navegar até o Diretório do Projeto

```bash
cd SEU_REPOSITORIO/QRCode - Exerc/
```

##
### 3. Abrir no Navegador

Basta abrir o arquivo `index.html` diretamente em seu navegador. Você pode fazer isso de duas maneiras:

* **Duplo Clique**: Localize o arquivo index.html na pasta QRCode - Exerc/ e dê um duplo clique nele.
* **Arrastar e Soltar**: Arraste o arquivo index.html para a janela aberta do seu navegador.
