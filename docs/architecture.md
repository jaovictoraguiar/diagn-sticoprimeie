# Arquitetura e Componentes

## Visão de alto nível

- **Frontend**: portal web para recepção, médicos e financeiro.
- **Backend**: serviços com API REST/GraphQL para integrar módulos.
- **Banco de dados**: dados clínicos e administrativos centralizados.

## Módulos principais

1. **Identidade e Acesso**
   - Autenticação e autorização com perfis.
   - Trilha de auditoria para ações críticas.

2. **CRM**
   - Cadastro de pacientes e canais de aquisição.
   - Histórico de interações e funil.

3. **Prontuário**
   - Evolução clínica, prescrições e anexos.
   - Versionamento de documentos.

4. **Financeiro**
   - Faturamento, repasses e conciliação.
   - Integração com meios de pagamento e convênios.

## Integrações recomendadas

- Mensageria (WhatsApp/SMS/e-mail).
- Meios de pagamento (Pix/cartão).
- Assinatura digital (certificados).
