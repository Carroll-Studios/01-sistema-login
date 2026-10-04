<div align="center">

<img src="./resources/images/galaxy-header.svg" width="100%" alt="Céu de galáxia com planeta de anel e estrelas" />

<br/>

<img src="https://img.shields.io/badge/🌙_sistema--login-8B5CF6?style=for-the-badge&logoColor=white" alt="sistema-login" />

<sub>✦ Carroll Studios • Projeto Final de Programação Orientada a Objetos • IFCE Maranguape • 2026.2 ✦</sub>

<br/><br/>

<img src="https://readme-typing-svg.demolab.com?font=Poppins&weight=400&size=16&duration=2400&pause=1200&color=C4B5FD&center=true&vCenter=true&width=620&height=30&lines=Portal+de+entrada+da+constela%C3%A7%C3%A3o;Login+seguro%2C+acesso+estelar" alt="Frases sobre o sistema" />

</div>

<img src="./resources/images/star-divider-1.svg" width="100%" alt="" />

<div align="center"><img src="https://img.shields.io/badge/🪐_Sobre%20este%20reposit%C3%B3rio-8B5CF6?style=for-the-badge&logoColor=white" alt="Sobre este repositório" /></div>

<br/>

O **sistema-login** é um dos três repositórios obrigatórios da Organização **Carroll Studios**. É o portal de autenticação: valida o acesso do usuário e abre caminho para os outros aplicativos da equipe.

| Repositório | Descrição |
|---|---|
| **sistema-login** | 👈 você está aqui — porta de entrada dos apps |
| [agenda-contatos](../agenda-contatos) | organizador de contatos pessoais |
| [projeto-livre](../projeto-livre) | jogo educativo espacial |

<img src="./resources/images/star-divider-2.svg" width="100%" alt="" />

<div align="center"><img src="https://img.shields.io/badge/🎯_Objetivos-EC4899?style=for-the-badge&logoColor=white" alt="Objetivos" /></div>

<br/>

- Autenticar o usuário validando usuário e senha.
- Direcionar, após o login, para a Tela de Seleção dos demais módulos.
- Servir como portal de entrada único da Organização Carroll Studios.
- Permitir retorno (logout) à Tela de Login a qualquer momento.

<div align="center"><img src="https://img.shields.io/badge/🔑_Credenciais%20de%20Acesso-EC4899?style=for-the-badge&logoColor=white" alt="Credenciais de Acesso" /></div>

<br/>

> [!NOTE]
> Para fins didáticos, o sistema usa credenciais estáticas validadas por uma estrutura condicional (`if`).

<div align="center">

| Usuário | Senha | Nível de Acesso |
| :---: | :---: | :---: |
| `root` | `toor` | 🛡️ Administrador |

</div>

<img src="./resources/images/star-divider-3.svg" width="100%" alt="" />

<div align="center"><img src="https://img.shields.io/badge/🖥️_Fluxo%20de%20Telas-6D28D9?style=for-the-badge&logoColor=white" alt="Fluxo de Telas" /></div>

<br/>

```text
 ┌────────────────┐    🔑 Login válido    ┌─────────────────┐
 │  Tela de Login  ├──────────────────────►│ Tela de Seleção │
 └────────┬────────┘                       └────────┬────────┘
          ▲                                          │
          └──────────────── 🚪 Sair / Voltar ────────┘

🔐 Tela de Login
Coleta usuário e senha, valida as credenciais e libera o acesso ao painel principal.

🪐 Tela de Seleção
Painel central com acesso a:
📇 Agenda de Contatos · 🚀 Jogo Espacial · 🚪 Voltar (logout)



☕ Java  •  🪟 Java Swing  •  💾 Persistência local  •  🧱 NetBeans  •  🐙 Git & GitHub

Carregar imagem

Clone este repositório.
Abra a pasta do projeto no NetBeans (ou outra IDE Java de sua preferência).
Execute a classe principal TelaLogin.
Entre com o usuário root e a senha toor.
Após o login, a Tela de Seleção será aberta.
Carregar imagem
Carregar imagem

main 🌟
 ├── 🛰️ feature/tela-login
 └── 🛰️ feature/tela-selecao
[!IMPORTANT]
Implementações nas branches só entram na main via Pull Request revisado pela equipe. Commits pequenos, frequentes e com mensagens claras.
Carregar imagem
Carregar imagem

sistema-login/
├── README.md
├── LICENSE
├── .gitignore
├── src/
├── resources/
│   ├── icons/
│   └── images/
├── docs/
│   ├── uml/
│   ├── ui-ux/
│   ├── diagrams/
│   └── presentations/
└── support/

Giovanna Sampaio
Design & Front-end
Carregar imagem
Carregar imagem
Hadassa Micaele
Banco de Dados
Carregar imagem
Carregar imagem
Isabelly Gomes
Backend
Carregar imagem
Carregar imagem
Julia
Front-end
Carregar imagem
Carregar imagem
Yasmin
Backend
Carregar imagem

✦ Carroll Studios ✦
Carregar imagem
```

