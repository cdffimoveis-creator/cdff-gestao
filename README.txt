# CDFF Gestão — protótipo inicial

## Como abrir
1. Extraia o ZIP em uma pasta.
2. Dê dois cliques em `index.html` para abrir no navegador.
3. Teste os dados de demonstração.

## O que funciona
- Painel de pagamentos e atrasos.
- Cadastro local de contratos/inquilinos.
- Geração manual de pagamento mensal.
- Confirmação manual de pagamento e opção de desfazer.
- Mensagem de cobrança preparada para revisão.
- Dados salvos no `localStorage` do navegador.

## Limitações importantes
- Os dados ficam apenas no navegador e não são compartilhados entre dispositivos.
- Os dados demonstrativos são fictícios.
- Não há login, banco de dados em nuvem, backup, boleto/Pix, webhook bancário ou envio automático de WhatsApp.
- Não coloque dados reais de clientes nesta versão.
- A regra de atraso mostra “Cobrar” após dois dias completos desde a data de vencimento.

## Próximas etapas
1. Confirmar regras reais de vencimento e cobrança da CDFF.
2. Migrar para banco de dados com autenticação e permissões.
3. Integrar provedor de pagamentos e processar webhooks de forma segura.
4. Adicionar logs, backups e proteção de dados.
5. Só então habilitar mensagens automáticas.
