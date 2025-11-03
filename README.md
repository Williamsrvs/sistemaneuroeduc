# sistemaneuroeduc
Sistema de Cadastro de Avaliação Educacional - Funcae

# 🧠 NeuroEduc – Sistema de Avaliação e Gestão Educacional

O **NeuroEduc** é um sistema web desenvolvido em **Flask (Python)**, com banco de dados **MySQL**, voltado à aplicação e gestão de **questionários educacionais e neuropsicológicos** para alunos.  
O objetivo principal é apoiar escolas e profissionais na coleta, análise e visualização de dados pedagógicos e comportamentais de forma estruturada e automatizada.

---

## 🚀 Funcionalidades Principais

- 📋 **Aplicação de Questionários**  
  Três módulos de avaliação distintos, voltados para o mapeamento do perfil educacional do aluno.

- 👩‍🏫 **Controle de Usuários e Perfis**  
  Sistema de login com autenticação e controle de acesso para **Administrador** e **Moderador/Usuário**.

- 📊 **Relatórios Automatizados**  
  Geração de relatórios em **PDF** e **XLSX**, com consolidação de resultados e indicadores.

- 🧩 **Banco de Dados Estruturado (MySQL)**  
  Armazena informações de alunos, questionários, respostas e resultados de forma segura e organizada.

- 🎨 **Interface Responsiva e Moderna**  
  Desenvolvida com **Bootstrap 5**, garantindo uma navegação intuitiva e agradável em diferentes dispositivos.

---

## 🏗️ Estrutura do Projeto (MVC)


neuroeduc/
│
├── app/
│ ├── static/ # CSS, JS e imagens
│ ├── templates/ # Páginas HTML (Jinja2)
│ ├── routes.py # Rotas e controle de views
│ ├── models.py # Modelos e interações com o banco de dados
│ ├── init.py # Inicialização do app Flask
│
├── config.py # Configurações de conexão e ambiente
├── requirements.txt # Dependências do projeto
├── README.md # Documento de apresentação
└── run.py # Arquivo principal para executar o sistema


---

## ⚙️ Tecnologias Utilizadas

| Tecnologia | Descrição |
|-------------|------------|
| **Python 3.10+** | Linguagem principal do sistema |
| **Flask** | Framework web para backend |
| **MySQL** | Banco de dados relacional |
| **Bootstrap 5** | Framework CSS para design responsivo |
| **Jinja2** | Template engine usada pelo Flask |
| **ReportLab** | Geração de relatórios PDF |
| **OpenPyXL** | Exportação de planilhas Excel |

---

## 🧩 Instalação e Execução

### 1️⃣ Clone o repositório
```bash
git clone https://github.com/seuusuario/neuroeduc.git
cd neuroeduc

