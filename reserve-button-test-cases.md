# Casos de Teste - Botão "Reservar"

## TC-01 - Reserva com todos os campos obrigatórios preenchidos
**Pré-condições:**
1. Acesse a mesa de teste
2. Insira "1917 Bay St" no campo "De"
3. Insira "615 S Broadway" no campo "Para"
4. Escolha o modo "Personal"
5. Escolha "Compartilhamento de carro" como tipo de transporte
6. Clique no botão "Reservar"

**Passos:**
1. Adicionar carteira de motorista
2. Adicionar um cartão bancário
3. Clicar no botão reservar

**Resultado esperado:**
O botão deve exibir o texto com distância e tempo estimado da rota.
Ao clicar, a janela "Carro reservado" deve ser aberta.

**Status executado:** Aprovado

---

## TC-02 - Reserva sem carteira de motorista
**Pré-condições:**
1. Acesse a mesa de teste
2. Insira "1917 Bay St" no campo "De"
3. Insira "615 S Broadway" no campo "Para"
4. Escolha o modo "Personal"
5. Escolha "Compartilhamento de carro" como tipo de transporte
6. Clique no botão "Reservar"

**Passos:**
1. Não adicionar carteira de motorista
2. Adicionar um cartão bancário

**Resultado esperado:**
O texto do botão deve mudar para "Adicionar a carteira de motorista e reservar", mantendo a informação da rota.

**Status executado:** Reprovado  
**Bug relacionado:** TRIP-10

---

## TC-03 - Reserva sem método de pagamento
**Pré-condições:**
1. Acesse a mesa de teste
2. Insira "1917 Bay St" no campo "De"
3. Insira "615 S Broadway" no campo "Para"
4. Escolha o modo "Personal"
5. Escolha "Compartilhamento de carro" como tipo de transporte
6. Clique no botão "Reservar"

**Passos:**
1. Adicionar carteira de motorista
2. Não adicionar um cartão bancário

**Resultado esperado:**
O texto do botão deve mudar para "Adicionar o método de pagamento e reservar", mantendo a informação da rota.

**Status executado:** Reprovado  
**Bug relacionado:** TRIP-11

---

## TC-04 - Reserva sem preencher os campos "De" e "Para"
**Pré-condições:**
1. Acesse a mesa de teste
2. Não inserir endereço nos campos "De" e "Para"

**Passos:**
1. Não inserir endereço nos campos "De" e "Para"

**Resultado esperado:**
Nada deve acontecer. O botão não deve aparecer sem os dados necessários.

**Status executado:** Aprovado
