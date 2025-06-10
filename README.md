# SevenScale-Prompts 🚀

Repositório para versionamento de prompts de agentes IA e JSONs de automações da **SevenScale** - Consultoria especializada em automação e inteligência artificial para PMEs.

## 📁 Estrutura do Repositório

```
SevenScale-Prompts/
├── agentes/                    # Prompts dos agentes IA
│   ├── whatsapp-sdr/          # Agente SDR para WhatsApp
│   ├── lead-qualifier/        # Qualificador de leads
│   ├── customer-support/      # Suporte ao cliente
│   ├── content-creator/       # Criador de conteúdo
│   └── sales-assistant/       # Assistente de vendas
├── automacoes/                # JSONs das automações
│   ├── zapier/               # Automações Zapier
│   ├── make/                 # Automações Make.com
│   ├── n8n/                  # Automações n8n
│   └── custom/               # Automações customizadas
├── clientes/                  # Prompts específicos por cliente
│   ├── template/             # Template padrão
│   └── README.md             # Instruções para novos clientes
├── templates/                 # Templates reutilizáveis
│   ├── base-prompts/         # Prompts base
│   └── automation-templates/ # Templates de automação
└── docs/                     # Documentação
    ├── guias/               # Guias de uso
    └── changelog/           # Log de mudanças
```

## 🎯 Propósito

Este repositório serve para:

- **Versionar prompts** de agentes IA desenvolvidos pela SevenScale
- **Armazenar JSONs** de automações para diferentes plataformas
- **Organizar por cliente** soluções personalizadas
- **Facilitar reutilização** através de templates
- **Documentar evolução** das soluções

## 🚀 Como Usar

### Para Novos Agentes
1. Crie uma pasta em `/agentes/[nome-do-agente]/`
2. Adicione o prompt principal em `prompt.md`
3. Inclua variações em `versoes/`
4. Documente em `README.md`

### Para Automações
1. Escolha a plataforma em `/automacoes/`
2. Crie arquivo JSON com nome descritivo
3. Adicione documentação explicativa
4. Inclua exemplos de uso

### Para Clientes
1. Crie pasta específica em `/clientes/[nome-cliente]/`
2. Organize prompts e automações personalizadas
3. Mantenha histórico de versões

## 📋 Padrões

### Nomenclatura
- **Pastas:** kebab-case (ex: `whatsapp-sdr`)
- **Arquivos:** descritivos e versionados
- **Branches:** feature/[funcionalidade]

### Versionamento
- Semantic Versioning (1.0.0)
- Tags para releases importantes
- Changelog detalhado

## 🤝 Contribuindo

Para adicionar novos prompts ou automações:
1. Crie branch específica
2. Siga a estrutura de pastas
3. Documente adequadamente
4. Faça pull request

---

**SevenScale** - Transformando PMEs através da automação inteligente

*Desenvolvido com ❤️ para revolucionar o growth marketing com IA*