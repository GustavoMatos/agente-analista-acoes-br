# Agente Analista de Ações BR

Prompt para agente de IA que analisa cartas mensais e relatórios das principais gestoras brasileiras, extraindo insights de investimento.

## Objetivo

Automatizar a coleta e síntese de visões de mercado das melhores gestoras do Brasil, gerando um resumo executivo mensal com:

- Teses de investimento em destaque
- Setores e ações recomendadas
- Visão macro (juros, câmbio, inflação)
- Riscos mapeados
- Oportunidades identificadas

## Gestoras Monitoradas

| Gestora | Especialidade | URL das Cartas |
|---------|---------------|----------------|
| Verde Asset | Macro/Multimercado | https://verdeasset.com.br/comunicados |
| SPX Capital | Macro/Multimercado | https://www.spxcapital.com.br/publicacoes |
| Dynamo | Ações/Value Investing | https://www.dynamo.com.br/cartas |
| Atmos Capital | Ações | https://www.atmoscapital.com.br/cartas |
| Brasil Capital | Ações | https://www.brasilcapital.com/cartas |
| Absoluto Partners | Ações | https://absolutopartners.com.br/cartas |
| Bogari Capital | Ações/Value | https://www.bogaricapital.com.br/cartas |
| Constellation | Ações | https://constellation.com.br/cartas |
| Indie Capital | Ações | https://www.indiecapital.com.br/cartas |
| Truxt | Macro/Ações | https://www.truxt.com.br/conteudos |
| Legacy Capital | Macro | https://legacycapital.com.br/cartas |
| Ibiuna | Macro | https://www.ibiuna.com/publicacoes |

## Como Usar

O arquivo `prompts/agente-analista.md` contém o prompt completo para ser usado com um agente de IA com capacidade de navegação web (como Claude com MCP, GPT com browsing, etc.).

## Estrutura do Repositório

```
├── README.md
├── prompts/
│   └── agente-analista.md    # Prompt principal
├── exemplos/
│   └── output-exemplo.md     # Exemplo de output esperado
└── config/
    └── gestoras.json         # Lista de gestoras e URLs
```

## Licença

MIT
