# Casos de Teste - Locação de Carro

## TC-01 - Reserva concluída com sucesso
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
Uma janela com o título "O carro foi reservado" deve surgir no centro da tela, exibindo ícone e endereço do carro, custo da corrida e cronômetro de espera gratuita.

**Status executado:** Aprovado

---

## TC-02 - Seleção de carro disponível no mapa
**Pré-condições:**
1. Acesse a mesa de teste
2. Endereços "De" e "Para" preenchidos
3. Modo "Personal" selecionado
4. Tipo de transporte "Carsharing" selecionado

**Passos:**
1. Clicar em um ícone de carro disponível no mapa

**Resultado esperado:**
O ícone do carro deve aumentar de tamanho, a caixa preta com a marca deve surgir e o painel esquerdo deve ser atualizado com as informações do veículo.

**Status executado:** Aprovado

---

## TC-03 - Seleção de carro já reservado
**Pré-condições:**
1. Acesse a mesa de teste
2. Endereços "De" e "Para" preenchidos
3. Há carros já reservados no mapa

**Passos:**
1. Clicar em um ícone de carro já reservado

**Resultado esperado:**
O sistema não deve permitir a seleção do carro reservado e nenhuma alteração deve ocorrer no painel esquerdo.

**Status executado:** Aprovado

---

## TC-04 - Reserva com cartão adicionado
**Pré-condições:**
1. Endereços "De" e "Para" preenchidos
2. Carteira de motorista adicionada
3. Cartão bancário válido adicionado

**Passos:**
1. Selecionar carro no mapa
2. Clicar em "Reservar"

**Resultado esperado:**
A reserva deve ser concluída com sucesso e a janela "O carro foi reservado" deve ser exibida.

**Status executado:** Aprovado

---

## TC-05 - Reserva sem cartão vinculado
**Pré-condições:**
1. Endereços "De" e "Para" preenchidos
2. Carteira de motorista adicionada
3. Nenhum cartão bancário vinculado

**Passos:**
1. Selecionar carro no mapa
2. Clicar em "Reservar"

**Resultado esperado:**
O sistema deve exibir a opção "Adicionar método de pagamento". A reserva não deve ser concluída.

**Status executado:** Aprovado
