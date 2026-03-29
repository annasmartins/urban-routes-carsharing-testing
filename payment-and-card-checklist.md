# Checklist Funcional - Método de Pagamento e Adicionar Cartão

## Objetivo
Validar o comportamento funcional da janela "Método de pagamento" e do formulário "Adicionar cartão".

## Ambiente
- Google Chrome — 800x600

## Checklist
- [x] Abrir a janela "Método de pagamento" sem cartões cadastrados
- [x] Exibir cartões salvos pelos últimos 4 dígitos
- [x] Selecionar um cartão já cadastrado
- [x] Impedir reserva sem método de pagamento
- [x] Abrir o formulário "Adicionar cartão"
- [x] Aceitar exatamente 12 dígitos válidos no número do cartão
- [ ] Impedir inserção acima de 12 dígitos no número do cartão
- [ ] Rejeitar letras ou caracteres especiais no número do cartão
- [x] Manter o botão inativo quando o campo estiver vazio
- [x] Aplicar formatação automática com espaços
- [x] Aceitar exatamente 2 dígitos válidos no campo "Código"
- [x] Manter o botão inativo com apenas 1 dígito
- [ ] Impedir inserção acima de 2 dígitos no campo "Código"
- [ ] Rejeitar letras ou caracteres especiais no campo "Código"
- [x] Manter o botão inativo quando o código estiver vazio
- [x] Ativar o botão "Adicionar" com número do cartão e código válidos
- [x] Salvar o cartão corretamente
- [x] Exibir múltiplos cartões cadastrados
- [ ] Exibir mensagem de erro ao inserir dados inválidos
- [x] Exibir a instrução correta ao tentar reservar sem cartão cadastrado

## Bugs relacionados
- TRIP-5 — número do cartão aceita mais de 12 dígitos
- TRIP-6 — número do cartão aceita caracteres inválidos
- TRIP-7 — campo "Código" aceita mais de 2 dígitos
- TRIP-8 — campo "Código" aceita caracteres inválidos
- TRIP-9 — tratamento incorreto para dados inválidos

## Técnicas aplicadas
- Classes de equivalência
- Valores-limite
- Testes positivos e negativos
