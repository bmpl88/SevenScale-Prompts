# 🤖 Agentes IA - SevenScale

Esta pasta contém todos os prompts dos agentes de inteligência artificial desenvolvidos pela SevenScale.

## 📋 Estrutura Padrão por Agente

Cada pasta de agente deve conter:

```
agente-exemplo/
├── README.md              # Documentação do agente
├── prompt.md              # Prompt principal atual
├── versoes/               # Histórico de versões
│   ├── v1.0.0.md
│   ├── v1.1.0.md
│   └── v2.0.0.md
├── exemplos/              # Exemplos de uso
│   ├── input-exemplo.md
│   └── output-exemplo.md
└── config/                # Configurações específicas
    ├── parametros.json
    └── instrucoes.md
```

## 🎯 Tipos de Agentes

### WhatsApp SDR
- **Função:** Prospecção e qualificação via WhatsApp
- **Foco:** Engajamento inicial e agendamento

### Lead Qualifier
- **Função:** Qualificação avançada de leads
- **Foco:** Scoring e segmentação

### Customer Support
- **Função:** Atendimento ao cliente
- **Foco:** Resolução de dúvidas e problemas

### Content Creator
- **Função:** Criação de conteúdo
- **Foco:** Posts, emails, materiais de marketing

### Sales Assistant
- **Função:** Assistência em vendas
- **Foco:** Follow-up e fechamento

## 📊 Métricas de Performance

Para cada agente, acompanhamos:
- Taxa de resposta
- Qualidade das interações
- Conversão para próximo estágio
- Satisfação do usuário

## 🔄 Processo de Atualização

1. **Teste** a nova versão em ambiente controlado
2. **Documente** as mudanças no changelog
3. **Versione** seguindo semantic versioning
4. **Implemente** gradualmente
5. **Monitore** performance pós-deploy

---

*Cada agente é uma peça fundamental no ecossistema de automação da SevenScale*