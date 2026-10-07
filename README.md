# Radar de Passagens — Agente de Promoções Aéreas

> 🔒 Código privado. Esta página descreve o escopo.

## O que é
Agente de IA que monitora promoções de passagens aéreas e avisa quando aparece um preço muito abaixo da média.

## Regras
- Viagens com **1 mês ou mais** de antecedência: alerta a partir de **50% de desconto**
- **Ofertas relâmpago** (menos de 1 mês): alerta só a partir de **70% de desconto**
- Faixa **"quase lá"** para ofertas um pouco abaixo do mínimo
- Origens configuráveis, qualquer destino nacional ou internacional

## Funcionamento
Busca automática **2 vezes por dia** em sites de promoções, com **painel** dos resultados e **aviso** das melhores ofertas.

## Tecnologias
Claude (tarefas agendadas e navegação web) · HTML (painel)
