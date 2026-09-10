# Minha Moto — V1 PWA

Primeira versão de teste local:
- odômetro inicial;
- próxima manutenção;
- GPS enquanto a página/app está aberto;
- cálculo da distância;
- confirmação se estava na moto;
- histórico local;
- alerta de manutenção.

## Importante no iPhone
Geolocalização no navegador exige contexto seguro (HTTPS). Para um teste no iPhone, publique estes arquivos em um host HTTPS simples ou use uma plataforma de hospedagem estática. Não é necessário backend: os dados ficam no localStorage do aparelho.

Esta V1 deliberadamente não tenta fazer rastreamento contínuo quando o PWA está suspenso pelo iOS. Essa é uma etapa posterior e requer abordagem nativa/mais específica.
