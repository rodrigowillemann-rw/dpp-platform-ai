# Metodologia

O diagnostico sintetico de prontidao DPP usa uma matriz simples de requisitos por criticidade e status de atendimento.

## Criterios

- Criticidade alta: peso 3
- Criticidade media: peso 2
- Criticidade baixa: peso 1
- Status pendente: 0
- Status parcial: 0,5
- Status atendido: 1

## Formula

```text
score = soma(peso_do_requisito * maturidade_do_status) / soma(pesos) * 100
```

## Interpretacao

O score nao representa conformidade regulatoria final. Ele serve como leitura inicial para priorizar coleta de dados, evidencias documentais e integracoes futuras com analise assistida por IA.
