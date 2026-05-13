<div align="center">

  <h1>Indicador de Teor de Avaliações</h1>
  <p><b>Uma solução para resumir e facilitar o controle e ciência em categoria de satisfação.</b></p>

  <img src="https://img.shields.io/badge/Status-Planejamento-lightgrey?style=for-the-badge&logo=blueprint" alt="Planejamento">
  <!-- <img src="https://img.shields.io/badge/Status-Em%20Desenvolvimento-orange?style=for-the-badge&logo=visualstudiocode" alt="Em Desenvolvimento"> -->
  <!-- <img src="https://img.shields.io/badge/Status-Concluído-brightgreen?style=for-the-badge&logo=checkmarx" alt="Concluído"> -->
  <!-- <img src="https://img.shields.io/badge/Status-Manutenção-blue?style=for-the-badge&logo=wrench" alt="Manutenção"> -->

  <br>

  <p>
    <a href="#sobre">Sobre</a> •
    <a href="#funcionalidades">Funcionalidades</a> •
    <a href="#tecnologias">Tecnologias</a> •
    <a href="#pré-requisitos">Pré-requisitos</a> •
    <a href="#configuração">Configuração</a> •
    <a href="#instalação">Instalação</a> •
    <a href="#uso">Uso</a> •
    <a href="#licença">Licença</a> •
    <a href="#contato">Contato</a>
  </p>
</div>

---

## Sobre

O **Indicador de Teor de Avaliações** foi desenvolvido com a finalidade de otimizar a coleta e organização de informações de empresas referente a avaliação de usuários. Com o auxilio de IA, o sistema categoriza avaliações em níveis de satisfação e temas de mensagens, fornecendo insights rápidos e acionáveis que ajudam equipes a tomarem decisões orientadas por dados.
>**Por que este projeto?**  
>A análise manual de avaliações é lenta e inconsistente, esta ferramenta automatiza o processo, garantindo que cada avaliação seja classificada com precisão e estruturada.

---

## Funcionalidades

- [ ] **Análise de Avaliações** - Organização e opção de filtros para facilitar a gestão e tratamento dos dados.
- [ ] **Relatórios de Categorias** - Gera relatórios baseado nos filtros selecionados.
- [ ] **Integração com IA** - Um agente de IA coleta, categoriza e encaminha dados de avaliações de forma autônoma, sem intervenção manual.
- [ ] **Multiplataforma** - Funciona em diferentes sistemas operacionais e ambientes.

---

## Tecnologias

<p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JAVASCRIPT">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="PYTHON">
  <img src="https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logoColor=white" alt="GROQ">
</p>

---

## Pré-requisitos
Antes de começar, certifique-se de ter os seguintes requisitos:
*   Python 3.8 ou superior instalado.
*   `pip` (gerenciador de pacotes Python) atualizado.

---

## Configuração

Este projeto utiliza variáveis de ambiente para gerenciar credenciais sensíveis.

1. Crie um arquivo `.env` na raiz do projeto:

  ```bash
  cp .env.example .env
  ```

2. Preencha suas credenciais de ia:

  ```env
  # Provedor de IA
  AI_API_KEY=sua_chave_aqui

  # Configurações da Aplicação
  APP_ENV=development
  DEBUG=True
  ```

3. Certifique-se de que `.env` está no `.gitignore`- **nunca commite chaves de API**
>Consulte `.env.example` para ver todas as variáveis disponíveis e suas descrições.

---

## Instalação

```bash
# 1. Clone o repositório
git clone https://github.com/15LUCASARAUJO/Rating-content-indicator.git
cd Rating-content-indicator

# 2. Crie um ambiente virtual
python -m venv venv

# 3. Ative o ambiente virtual
#    Windows:
.\venv\Scripts\activate
#    macOS/Linux:
source venv/bin/activate

# 4. Instale as dependências
pip install -r requirements.txt
```

---

## Uso

```bash
# Inicie a aplicação
python app.py
```
>As instruções específicas de uso podem variar dependendo da sua configuração. Consulte a documentação interna ou as flags de CLI disponíveis.

---

## Licença

Este projeto está licenciado sob a **Licença MIT** — veja o arquivo [LICENSE.md](LICENSE.md) para mais detalhes.

---

## Contato

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lucas-araujo-de-paula-8463b9271)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/15LUCASARAUJO)
</div>

---

<div align="center">
  <sub>Feito por <a href="https://github.com/15LUCASARAUJO">Lucas Araujo</a></sub>
</div>
