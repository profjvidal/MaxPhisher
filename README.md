<h1 align="center">MaxPhisher</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Versão-1.2.3-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Linguagem-Python-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Código-Aberto-cyan?style=for-the-badge">
  <img src="https://img.shields.io/badge/Finalidade-Educacional-orange?style=for-the-badge">
</p>

<p align="center">
  <b>Ferramenta para estudos de Segurança da Informação,
  Engenharia Social e Conscientização sobre Phishing.</b>
</p>

---

## 📖 Descrição

O **MaxPhisher** é uma ferramenta desenvolvida em Python que permite estudar e compreender técnicas relacionadas ao phishing, à engenharia social e aos riscos associados à segurança digital.

O projeto apresenta recursos para simulação de páginas de autenticação, manipulação de URLs, análise de conexões e demonstração de técnicas utilizadas em ataques de engenharia social.

### 🎓 Finalidade educacional

**Este código é disponibilizado exclusivamente para fins estudantis, acadêmicos e de pesquisa em Segurança da Informação.**

Seu objetivo é contribuir para o aprendizado de estudantes, professores e pesquisadores nas áreas de:

- Segurança da Informação;
- Redes de Computadores;
- Segurança de aplicações web;
- Engenharia Social;
- Testes de segurança autorizados;
- Identificação e prevenção de phishing;
- Conscientização sobre ameaças digitais.

**IMPORTANTE:** A utilização deve ocorrer exclusivamente em ambientes controlados, laboratórios educacionais ou sistemas para os quais exista autorização expressa.

O projeto não incentiva a coleta não autorizada de credenciais, a invasão de contas ou qualquer atividade ilegal.

---

## ⚙️ Instalação

### 1. Instalar as dependências principais

#### Debian, Ubuntu, Kali Linux e Parrot OS

```bash
sudo apt install git python3 python3-pip php openssh-client -y
```

#### Arch Linux e Manjaro

```bash
sudo pacman -S git python python-pip php openssh --noconfirm
```

#### Fedora

```bash
sudo dnf install git python3 python3-pip php openssh -y
```

#### Termux (Android)

```bash
pkg install git python3 python-pip php openssh -y
```

### 2. Clonar o repositório

```bash
git clone https://github.com/profjvidal/MaxPhisher.git
```

### 3. Acessar o diretório

```bash
cd MaxPhisher
```

### 4. Instalar os módulos Python

Recomenda-se utilizar um ambiente virtual:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r files/requirements.txt
```

### 5. Executar a ferramenta

```bash
python3 maxphisher.py
```

**Atenção:** Antes de executar scripts de terceiros, recomenda-se verificar suas dependências, arquivos PHP, modelos de páginas e executáveis externos.

---

## 🐳 Docker

A imagem original pode ser obtida por meio do comando:

```bash
sudo docker pull kasroudra/maxphisher
```

Execução em um ambiente de laboratório isolado:

```bash
sudo docker run --rm -it kasroudra/maxphisher
```

A imagem Docker pertence ao projeto original e deve ser analisada antes da utilização.

---

## 💻 Compatibilidade

| Sistema operacional | Nível de suporte |
|---|---|
| Linux | Excelente |
| Android (Termux) | Excelente |
| iPhone (iOS) | Experimental |
| macOS | Experimental |
| Windows | Via Docker ou máquina virtual |
| BSD | Não testado |

---

## 🚀 Recursos

A ferramenta original apresenta os seguintes recursos:

- Compatibilidade com diferentes distribuições Linux;
- Mais de 100 modelos de páginas;
- Simulação de páginas de autenticação;
- Suporte a diferentes serviços de tunelamento;
- Recursos relacionados a autenticação OTP;
- Análise de URLs e redirecionamentos;
- Simulação de técnicas de engenharia social;
- Identificação de informações de conexão;
- Diagnóstico de possíveis erros;
- Execução por meio de Python;
- Suporte a ambientes virtuais e Docker.

Alguns desses recursos podem envolver dados sensíveis e devem ser utilizados somente com autorização, em ambientes de teste.

---

## 📦 Requisitos

### Software

- Python 3;
- PHP;
- SSH;
- Git.

### Bibliotecas Python

- requests;
- rich;
- beautifulsoup4.

### Armazenamento

- Aproximadamente 900 MB de espaço disponível.

**Observação:** A ferramenta original pode tentar instalar dependências automaticamente durante a primeira execução.

---

## 🧪 Ambientes testados pelo projeto original

- Termux;
- Ubuntu;
- Kali Linux;
- Arch Linux;
- Fedora;
- Manjaro.

---

## 📚 Utilização em laboratório educacional

Para atividades acadêmicas, recomenda-se seguir estas etapas:

1. Preparar uma máquina virtual ou ambiente isolado.
2. Analisar o código-fonte e suas dependências.
3. Identificar os mecanismos de simulação de páginas.
4. Estudar as técnicas de engenharia social utilizadas.
5. Realizar testes somente com contas fictícias e dados simulados.
6. Examinar as requisições HTTP e os registros de conexão.
7. Discutir métodos de identificação e prevenção de phishing.
8. Elaborar um relatório técnico com os resultados obtidos.

### Objetivos de aprendizagem

Ao final da atividade, os estudantes deverão compreender:

- Como funcionam ataques de phishing;
- Como identificar páginas fraudulentas;
- Quais riscos existem no compartilhamento de credenciais;
- Como reconhecer URLs suspeitas;
- Como proteger contas e informações pessoais;
- Qual a importância da ética profissional em Segurança da Informação.

---

## 🔧 Solução de problemas comuns

### Problemas com dependências

Verifique a instalação do Python e PHP:

```bash
python3 --version
php --version
```

### Problemas com bibliotecas Python

Confira as dependências instaladas:

```bash
pip list
```

### Problemas com ambientes virtuais

Ative o ambiente virtual antes de executar:

```bash
source .venv/bin/activate
```

### Problemas no Termux

Recomenda-se utilizar uma versão atualizada do Termux, obtida por fontes oficiais, como F-Droid ou GitHub.

### Problemas de conectividade

Verifique a configuração da rede, do firewall e das permissões do ambiente de laboratório.

---

## ⚠️ Aviso legal e responsabilidade

**O MaxPhisher é apresentado neste repositório exclusivamente para fins educacionais, estudantis, acadêmicos e de pesquisa em Segurança da Informação.**

O código tem como finalidade demonstrar o funcionamento de técnicas relacionadas ao phishing e contribuir para a formação de profissionais capazes de identificar, compreender e prevenir ameaças cibernéticas.

É expressamente desaconselhada sua utilização para:

- Obter credenciais sem autorização;
- Acessar contas ou sistemas de terceiros;
- Capturar informações pessoais sem consentimento;
- Realizar fraudes ou atividades ilegais;
- Distribuir links fraudulentos a pessoas não participantes de testes autorizados.

**O usuário é integralmente responsável pela utilização da ferramenta e pelo cumprimento da legislação aplicável, incluindo a Lei Geral de Proteção de Dados (LGPD) e as normas brasileiras relacionadas a crimes cibernéticos.**

Os responsáveis pela disponibilização deste material não apoiam nem incentivam a utilização indevida do projeto.

---

## 👨‍💻 Créditos

### Desenvolvedor original

**KasRoudra**

- GitHub: https://github.com/KasRoudra
- GitLab: https://gitlab.com/KasRoudra

### Projeto original

https://gitlab.com/KasRoudra/MaxPhisher

### Repositório de estudo

https://github.com/profjvidal/MaxPhisher

### Projetos relacionados

- [PyPhisher](https://gitlab.com/KasRoudra/PyPhisher)
- [CamHacker](https://gitlab.com/KasRoudra/CamHacker)
- [VidPhisher](https://gitlab.com/KasRoudra/VidPhisher)
- [IP-Tracker](https://github.com/KasRoudra/IP-Tracker)
- [Storm-Breaker](https://github.com/ultrasecurity/Storm-Breaker)
- [Seeker](https://github.com/thewhiteh4t/seeker)

---

## 📄 Licença

Consulte o arquivo de licença do projeto original para conhecer as condições de utilização, modificação e redistribuição.

---

<p align="center">
  <b>Segurança da Informação começa com conhecimento, ética e responsabilidade.</b>
</p>

<p align="center">
  Material destinado exclusivamente a estudos e testes autorizados.
</p>
