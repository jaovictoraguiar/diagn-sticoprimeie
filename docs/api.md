# API (Exemplo de endpoints)

## CRM
- `POST /crm/pacientes` — cria paciente.
- `GET /crm/pacientes/{id}` — consulta paciente.
- `POST /crm/interacoes` — registra interação.

## Prontuário
- `POST /prontuarios` — cria prontuário.
- `GET /prontuarios/{id}` — consulta prontuário.
- `POST /prontuarios/{id}/evolucoes` — adiciona evolução.

## Financeiro
- `POST /financeiro/contas-receber` — cria cobrança.
- `POST /financeiro/contas-pagar` — cria despesa.
- `GET /financeiro/relatorios/fluxo-caixa` — relatório financeiro.
