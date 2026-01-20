# Modelo de Dados (Resumo)

## Entidades principais

- **Paciente**: dados pessoais, contato, consentimentos LGPD.
- **Profissional**: médicos e equipe, especialidades e permissões.
- **Atendimento**: vínculo entre paciente e profissional, data, status.
- **Prontuário**: anamnese, evoluções, diagnósticos e prescrições.
- **Documento Clínico**: anexos e laudos vinculados ao prontuário.
- **Conta a Receber**: cobranças, convênios e meios de pagamento.
- **Conta a Pagar**: despesas operacionais.
- **Repasse**: distribuição de receita por atendimento.

## Relacionamentos essenciais

- Paciente 1:N Atendimento
- Atendimento 1:1 Prontuário
- Prontuário 1:N Documento Clínico
- Atendimento 1:N Conta a Receber
- Atendimento 1:N Repasse
