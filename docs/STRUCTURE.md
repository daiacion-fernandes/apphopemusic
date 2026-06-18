# Estrutura do Projeto - Hope Music App

## 📁 Organização de Pastas

```
apphopemusic/
├── upload/                          # Arquivos de instalação
│   ├── admin/
│   │   ├── controller/
│   │   │   └── extension/
│   │   │       └── hopemusicapp.php
│   │   ├── language/
│   │   │   └── en-gb/
│   │   │       └── hopemusicapp.php
│   │   └── view/
│   │       └── extension/
│   │           └── hopemusicapp.twig
│   ├── catalog/
│   │   ├── controller/
│   │   │   └── extension/
│   │   │       └── hopemusicapp.php
│   │   ├── model/
│   │   │   └── extension/
│   │   │       └── hopemusicapp.php
│   │   └── view/
│   │       └── extension/
│   │           └── hopemusicapp.twig
│   └── system/
│       └── library/
│           └── hopemusicapp.php
│
├── docs/                            # Documentação
│   ├── STRUCTURE.md
│   ├── API.md
│   └── CUSTOMIZATION.md
│
├── README.md                        # Documentação principal
├── LICENSE                          # Licença MIT
├── CHANGELOG.md                     # Histórico de versões
├── INSTALLATION.md                  # Guia de instalação
├── install.ocmod.xml               # Manifesto da extensão
└── .gitignore                       # Arquivo Git ignore
```

## 📄 Descrição dos Arquivos Principais

### `/upload/admin/`
Arquivos de administração da extensão:
- **controller**: Lógica de controle do admin
- **language**: Strings de tradução
- **view**: Templates Twig para interface

### `/upload/catalog/`
Arquivos do frontend:
- **controller**: Controladores da loja
- **model**: Modelos de dados
- **view**: Templates Twig para o cliente

### `/upload/system/`
Arquivos do sistema:
- **library**: Classes utilitárias e bibliotecas

## 🔗 Arquivos de Configuração

| Arquivo | Propósito |
|---------|-----------|
| `README.md` | Visão geral do projeto |
| `LICENSE` | Termos de licença (MIT) |
| `install.ocmod.xml` | Manifesto de modificação OpenCart |
| `INSTALLATION.md` | Guia passo a passo de instalação |
| `CHANGELOG.md` | Histórico de versões e atualizações |
| `.gitignore` | Arquivos ignorados pelo Git |

## 📦 Estrutura de Arquivos no Servidor

Quando instalado, o arquivo segue esta estrutura no servidor OpenCart:

```
opencart/
├── admin/
│   ├── controller/extension/hopemusicapp.php
│   ├── language/en-gb/extension/hopemusicapp.php
│   └── view/extension/hopemusicapp.twig
├── catalog/
│   ├── controller/extension/hopemusicapp.php
│   ├── model/extension/hopemusicapp.php
│   └── view/extension/hopemusicapp.twig
└── system/
    └── library/hopemusicapp.php
```

## 🎯 Nomenclatura

- **Prefixo de identificação**: `hopemusicapp`
- **Código da extensão**: `hopemusicapp`
- **Classes**: `ControllerExtensionHopemusicapp`, `ModelExtensionHopemusicapp`

## 🔄 Fluxo de Funcionamento

1. Usuário instala o `.ocmod.zip` pelo admin
2. OpenCart extrai e aplica o manifesto `install.ocmod.xml`
3. Arquivos são copiados para suas respectivas pastas
4. Cache é limpo
5. Extensão fica ativa e funcionando

---

Para mais detalhes, consulte a [INSTALLATION.md](../INSTALLATION.md)
