# CDU 1: Propor Doação

---

## Atores envolvidos  
- **Doador:** Pessoa física ou jurídica.  
- **Coletadora:** Administrado por empresas coletoras que selecionam os itens.

---

## Fluxo principal de eventos  
1. O doador digita suas credenciais no sistema e entra.  
2. O doador clica na opção **"Doar"**.  
3. O doador seleciona o tipo da doação (dentre as opções do sistema, para facilitar a separação para reciclagem).  
4. O sistema exibe um formulário solicitando:  
   - CPF, nome completo e data de nascimento *(ou CNPJ se pessoa jurídica)*;  
   - Descrição do produto;  
   - Motivo da doação;  
   - Imagem do(s) produto(s);  
   - Assinatura do termo de comprometimento com a veracidade das informações.  
5. O doador clica em **"Enviar"** e envia o formulário.

---

## Fluxos alternativos  
**A1 - Erro nas credenciais**  
- Se o usuário tentar logar e houver erro, o sistema solicitará a correção das credenciais.

**A2 - Campo obrigatório não preenchido**
- Se o doador esquecer de preencher algum campo obrigatório, o sistema os solicitará.

---

## Pré-condições  
1. O usuário está cadastrado no sistema.  
2. O usuário é maior de idade.

---

## Pós-condições  
1. O sistema registra o formulário para análise e aprovação.

---

# CDU 2: Registrar Doação

---

## Atores envolvidos  
- **Doador:** Pessoa física ou jurídica, que confirma e registra a doação aprovada.  
- **Sistema:** Responsável pela gestão, validação, armazenamento e encaminhamento das doações aprovadas.  
- **Empresas coletoras e distribuidoras:** Responsáveis por coletar, reciclar e distribuir o material.  
- **Recebedor:** Pessoa ou entidade que recebe o material reciclado.

---

## Fluxo principal de eventos  
1. O doador acessa o sistema com suas credenciais.  
2. O doador registra a doação confirmando os detalhes (tipo e quantidade do material, local e data da entrega).  
3. O sistema armazena os dados da doação no banco de dados.  
4. O sistema encaminha a solicitação de coleta para as empresas coletoras.  
5. As empresas coletoras agendam a retirada ou informam pontos de entrega.  
6. O sistema atualiza o status da doação conforme o processamento (coletada, reciclada, entregue).  
7. O sistema notifica o recebedor sobre a disponibilidade do material reciclado.

---

## Fluxos alternativos  
**A1 - Erro nas credenciais**  
- Se o usuário tentar logar e houver erro, o sistema solicitará a correção das credenciais.

**A2 - Dados incompletos no registro**  
- Caso o doador não preencha todos os dados obrigatórios no registro, o sistema exibirá mensagem solicitando o preenchimento correto.

**A3 - Falha na comunicação com empresa coletora**  
- O sistema registra a falha e notifica a equipe responsável para intervenção.

---

## Pré-condições  
1. A doação foi aprovada após análise do requerimento.  
2. O doador está cadastrado e pode acessar o sistema para registrar a doação.  
3. O sistema está integrado com as empresas coletoras e recebedores.

---

## Pós-condições  
1. A doação está registrada e sendo processada.  
2. O ciclo da doação é monitorado até a entrega final ao recebedor.

---

# CDU 3: Visualizar Pontos

---

## Atores envolvidos  
- Doadores: Pessoas físicas ou jurídicas que desejam entregar doações.  
- Recebedores: Pessoas ou entidades que recebem as doações.  
- Coletadoras: Empresas cujo objetivo é coletar os itens doados para a reciclagem.
- Empresas distribuidoras: Responsáveis pela logística dos pontos de entrega.

---

## Fluxo principal de eventos  
1. O usuário (doador, recebedor ou empresa) acessa o sistema e faz login.  
2. O usuário seleciona a opção de visualizar pontos de entrega.  
3. O sistema exibe um mapa ou lista com os pontos de entrega disponíveis, com informações como endereço, horários de funcionamento; ou a empresa envia um e-mail ao doador ou recebedor.  
4. O usuário pode buscar pontos por localização, tipo de doação ou outros filtros e visualizar detalhes de cada ponto.

---

## Fluxos alternativos   
**A2 - Nenhum ponto disponível para o filtro escolhido**  
- O sistema informa que não há pontos correspondentes à busca e sugere remover ou alterar filtros.

---

## Pré-condições  
- O sistema deve ter cadastrados os pontos de entrega com suas informações atualizadas.  

---

## Pós-condições  
- O usuário visualiza informações atualizadas dos pontos de entrega e pode planejar a entrega ou retirada da doação.

---

