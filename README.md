# TECHPLUS

* Nome: Leonel Pereira de Almeida
* Turno: manhã
* E-mail: leonelalmeida.10.la@gmail.com
* Caso: 4 - Setor: Comercial local

---
Neste presente documento, apresento uma análise detalhada dos desafios enfrentados atualmente pela empresa TechPlus e as abordagens que serão utilizadas para solucionar suas dores.

---
## Contexto - TechPlus
**Ambiente**: Um comércio local de eletrônicos e acessórios, com atendimento presencial e dinâmico.

**Pessoas envolvidas**:
* Atendentes
* Clientes com diferentes perfis:
  * Os que já sabem o que querem
  * Os que precisam de ajuda para decidir entre um produto
  * Clientes frequentes
  * Clientes ocasionais
  * Clientes que retornam, seja para realizar uma troca, seja fazer uma reclamação

---
## Identificação dos problemas
- **Ausência de registro estruturado dos atendimentos**: verifica-se isso por não haver um sistema interno que guarde os dados referentes ao atendimento dos clientes, em especial nos casos em que não há vendas e, tendo uma base de dados com estes registros, poderia ser usado para analisar o motivo da não venda, por exemplo, se é algum produto em específico que alguns/vários clientes desejam, mas não encontram;
- **Falta de padronização nos atendimentos**: clientes relatam que receberam orientações diferentes em momentos distintos e dúvidas que se repetem costantemente, sem identificação clara do momento em que isso ocorre;
- **Achismo ao invés de dados**: alguns atendentes acham que o problema está na abordagem inicial, outros acham que seria importante registrar o que foi orientado ao cliente, mas não há dados que possam avaliar onde está a causa principal do problema e, assim, gerar um plano para solucioná-lo;
- **Falta de entendimento do problema**: a equipe não sabe quais são as dúvidas mais frequentes, quais os produtos que geram mais indecisão, qual o percentual de conversão em vendas, quais situações geram mais retrabalho e/ou retorno do cliente e quais os motivos de alguns atendimentos nao se converterem em vendas.

---
## Recorte do problema
Apresentei esta análise à gerência da loja, identificando os problemas a serem solucionados a fim de gerar mais confiabilidade ao negócio. Em primeira instância, sugeri priorizar o desenvolvimento de um CRM para armazenamento estruturado do atendimento ao cliente e visibilidade do funil de atendimento até a venda.

**Motivo**:
Se conseguirmos resolver estes problemas priorizados:
- conseguimos medir a conversão
- traçamos as dúvidas recorrentes dos clientes
- criamos base para padronização
- geramos dados para decisões

---
## Objetivo da solução
Desenvolvimento de um sistema simples e prático que:
- Registre atendimentos em tempo real
- Classifique o tipo de atendimento
- Registre dúvidas e produtos envolvidos
- Registre se houve conversão ou não no atendimento
- Permita visualizar:
  - Taxa de conversão
  - Produtos com maior indecisão
  - Dúvidas mais frequentes
  - Motivos de não venda
 
A solução será desenvolvida no ambiente Microsoft (Power Apps).

 ---
 ## Melhorias Fututras (Adicional)
 Nas próximas versões do Sistema, visando deixá-lo o mais completo possível para que a experiência seja a melhor, podemos incluir:
 - Mecânica para verificar a Recorrência de um cliente para possibilitar atendimentos mais personalizados
 - Taxa de conversão de clientes novos vs recorrentes
 - Criar campo específico para data na tabela de atendimentos (atualmente estamos utilizando a coluna padrão do SharePoint Created At), para poder cadastrar atendimentos retroativos (caso o funcionário tenha esquecido de cadastrar), implementando um visual de calendário no Power Apps
 - Criar coluna de preços na tabela de produtos. Isso permitiria visualizar faturamento, quais produtos dão mais lucro, etc., o que daria uma visão mais ampla e estratégica do negócio
 - Implementar coluna de estoque na tabela de produtos. Isso permitiria que os funcionários tivessem maior controle sobre os itens a serem repostos e a urgência (utilizando, em conjunto, a métrica de vendas de produtos, para verificar a prioridade de necessidade dos produtos)
