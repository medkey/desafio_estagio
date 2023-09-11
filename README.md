# Sistema de Relacionamento com Cliente via WhatsApp
## Desafio de Desenvolvimento Web

Desenvolva um sistema para fortalecer o relacionamento de nossos contratantes com seus clientes através do WhatsApp.

### **Objetivo**

Avaliar habilidades técnicas, capacidade de pesquisa e design UI/UX do candidato.

### **Duração**

O desafio deve ser concluído em até 2 semanas.

## Especificações Técnicas

### **Parte 1: Configuração Inicial, Autenticação e API REST**

1. **Setup:** 
   - Configure um ambiente de desenvolvimento usando a stack de sua preferência. Preferencialmente (mas não obrigatoriamente) usando Node.js com Express para o backend.
   
2. **Autenticação:** 
   - Implemente um sistema básico de login para os contratantes.
   
3. **API REST:** 
   - CRUD de clientes (Nome, Telefones, E-mails).
   - CRUD de interações dos clientes (últimas interações, produtos adquiridos).
   - CRUD de mensagens padronizadas.

### **Parte 2: Integração com WhatsApp**

4. **Integração com Twilio/WhatsApp:** 
   - Permita o envio de mensagens de texto para o WhatsApp.
   - (Diferencial) Considere cenários em que o cliente não responde ou o número de telefone não é válido.

### **Parte 3: Painel de Gestão**

5. **Painel de Gestão:** 
   - Visualização e gestão da lista de clientes.
   - Definição do intervalo de tempo para relacionamento (dias, semanas, meses).
   - Visualização das conversas realizadas.
   - Visualização de métricas básicas (total de clientes, clientes ativos).

### **Parte 4: Integração com OpenAI**

6. **Integração com OpenAI:** 
   - Ao receber uma resposta do cliente via WhatsApp, gere uma resposta apropriada usando a API da OpenAI.
   - O prompt deve ser otimizado para que a resposta possa ser enviada diretamente ao cliente.
   - (Diferencial) Possibilidade de fine-tuning usando um arquivo CSV com interações prontas.

## Instruções para Submissão

1. Clone este repositório.
2. Crie uma branch com seu nome.
3. Realize commits de suas atualizações e implementações.
4. Ao finalizar o desafio, envie um email para `webmaster@medkey.com.br` com o link da sua branch para revisão.

## Notas

O candidato pode solicitar orientações se necessário. O foco é avaliar a capacidade do candidato de entender o problema, pesquisar soluções e implementar uma solução funcional. Não é esperado que todas as funcionalidades sejam perfeitamente implementadas, mas a organização do código, design da interface e a documentação serão avaliados.
