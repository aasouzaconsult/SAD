# UNIDADE V - Sistemas de Gestão da Produção

## 1. O que é Gestão da Produção?
   - **Definição:** A Gestão da Produção é uma disciplina que se concentra na coordenação eficiente dos recursos, processos e atividades envolvidos na fabricação de produtos ou na prestação de serviços. Ela visa otimizar a produção para atender às demandas dos clientes de forma eficaz e econômica.
   - **Conceitos Chave:** Variáveis de gestão da produção incluem planejamento da produção, controle de estoque, programação da produção, gerenciamento da qualidade e otimização de recursos.
   - **Exemplo:** Uma fábrica de automóveis utiliza a gestão da produção para coordenar a produção de veículos, desde a aquisição de matérias-primas até a montagem final, para atender às demandas de mercado com eficiência.

## 2. Formulações Matemáticas para Gestão de Produção:
   - **Definição:** Formulações matemáticas são modelos quantitativos que auxiliam na tomada de decisões relacionadas à gestão da produção. Eles envolvem equações e fórmulas que ajudam a otimizar variáveis como produção, estoque e distribuição.
   - **Exemplo:** Uma formulação matemática para a gestão de estoque pode ser o Modelo de Lote Econômico (EOQ), que calcula a quantidade ideal a ser encomendada para minimizar os custos totais de estoque.
   - **Variáveis de Gestão da Produção:** Variáveis comuns incluem demanda, custos de produção, custos de armazenamento, tempo de entrega e níveis de estoque.

## 3. O que é MRP (Material Requirements Planning)?
   - **Definição:** O MRP (Planejamento das Necessidades de Materiais) é um sistema de gestão da produção que utiliza cálculos matemáticos para planejar e controlar o estoque e a produção de materiais com base nas necessidades de produção.
   - **Composição do MRP:** O MRP usa listas de materiais (BOM), registros de estoque e programação mestra de produção (MPS) para calcular quando e quanto de cada material deve ser adquirido ou produzido.
   - **Exemplo:** Uma fábrica de eletrônicos utiliza o MRP para determinar quando deve encomendar componentes eletrônicos com base na demanda de produtos finais.

Mais informações: [MRP](https://www.nomus.com.br/blog-industrial/o-que-e-o-mrp-e-para-que-serve/) | [MPS](https://www.sankhya.com.br/blog/o-que-e-mps-e-como-fazer-um-plano-mestre-de-producao/) | [BOM](https://www.tecnicon.com.br/blog/534-O_que_e_Bill_of_Materials_BOM_para_que_serve_e_como_usar_na_manufatura)

## 4. O que é MRP II (Manufacturing Resource Planning)?
   - **Definição:** O MRP II (Planejamento dos Recursos de Manufatura) é uma extensão do MRP que inclui o planejamento de recursos humanos, capacidade de produção e programação de chão de fábrica para garantir que os recursos estejam disponíveis para atender às necessidades do MRP.
   - **Composição do MRP II:** Além dos componentes do MRP, o MRP II envolve o planejamento da capacidade de produção, alocação de mão de obra e cronograma de produção detalhado.
   - **Exemplo:** Uma empresa de alimentos usa o MRP II para planejar a produção de produtos alimentícios, considerando não apenas os ingredientes necessários, mas também a capacidade das máquinas e a disponibilidade da equipe de produção.

## 5. ERP (Enterprise Resource Planning):
   - **Definição:** Os sistemas ERP são soluções de software integradas que abrangem vários departamentos e funções dentro de uma organização, incluindo produção, finanças, vendas e recursos humanos.
   - **Como Funciona:** Os sistemas ERP centralizam dados e processos, permitindo que as informações sejam compartilhadas em toda a empresa. Eles automatizam tarefas, melhoram a visibilidade e agilizam a tomada de decisões.
   - **Papel no Processo Produtivo:** Os sistemas ERP desempenham um papel fundamental na otimização do processo produtivo, integrando as operações de fabricação com outras áreas. Por exemplo, eles podem ajudar a programar a produção com base nas vendas e no estoque disponível, garantindo uma produção eficiente.
### Exemplo de Uso de ERP:
Uma empresa de produtos eletrônicos utiliza um sistema ERP para gerenciar sua produção. Quando um cliente faz um pedido, o sistema ERP verifica automaticamente os níveis de estoque, disponibilidade de máquinas, programação de produção e custos associados. Isso ajuda a empresa a atender rapidamente aos pedidos dos clientes, minimizando o desperdício de recursos.

Mais informações: [SAP](https://www.sap.com/brazil/index.html?url_id=auto_hp_redirect_brazil) | [TOTVS](https://www.totvs.com/sistema-de-gestao/) | 

## 6. OEE
OEE (*Overall Equipment Effectiveness*), em português Eficiência Geral dos Equipamentos, é um indicador amplamente utilizado na gestão de produção e manufatura para avaliar o desempenho de equipamentos e processos de produção. Ele fornece uma medida abrangente da eficiência operacional e ajuda as empresas a identificar oportunidades de melhoria na produção.

O OEE é calculado com base em três principais componentes:
- **Disponibilidade:** Refere-se ao tempo em que o equipamento está disponível e pronto para produzir em relação ao tempo total disponível. Isso inclui paradas programadas, como manutenção, bem como paradas não programadas, como falhas e ajustes.
   - Fórmula de Disponibilidade: Disponibilidade (%) = (Tempo de Produção Real / Tempo Total Disponível) x 100
- **Desempenho:** Mede a eficiência real do equipamento durante o tempo de produção. Ele considera o desempenho em relação à velocidade ideal do equipamento, levando em consideração as taxas de produção e possíveis perdas de velocidade.
   - Fórmula de Desempenho: Desempenho (%) = (Taxa de Produção Real / Taxa de Produção Ideal) x 100
- **Qualidade:** Avalia a qualidade dos produtos fabricados. Isso leva em consideração produtos defeituosos, retrabalho e refugos em relação à produção total.
   - Fórmula de Qualidade: Qualidade (%) = (Unidades Boas / Unidades Produzidas) x 100

O OEE é calculado multiplicando-se esses três componentes:
- **OEE (%) = Disponibilidade (%) x Desempenho (%) x Qualidade (%)**

O resultado é um valor entre 0% (ineficiente) e 100% (máxima eficiência). Quanto mais próximo de 100%, melhor é o desempenho global dos equipamentos e processos de produção.

O indicador OEE é valioso para a identificação de ineficiências e áreas de melhoria na produção. Por exemplo, uma baixa disponibilidade pode indicar que o equipamento está frequentemente parado devido a falhas, enquanto um baixo desempenho pode apontar para problemas de velocidade ou ajustes frequentes. Uma baixa qualidade sugere que há muitos produtos defeituosos sendo produzidos.

### Exemplo
Suponha que você tenha uma tabela chamada "Producao" com as seguintes colunas:

- `DataProducao` (data e hora da produção)
- `TempoProducao` (tempo de produção real em minutos)
- `TempoIdeal` (tempo ideal de produção em minutos)
- `UnidadesBoas` (número de unidades de produtos de boa qualidade)
- `UnidadesProduzidas` (número total de unidades produzidas)

```sql
-- Criar tabela Producao
CREATE TABLE Producao (
    ID INT PRIMARY KEY IDENTITY(1,1),
    DataProducao DATETIME,
    TempoProducao INT, -- Tempo de produção real em minutos
    TempoIdeal INT, -- Tempo ideal de produção em minutos
    UnidadesBoas INT, -- Número de unidades de produtos de boa qualidade
    UnidadesProduzidas INT -- Número total de unidades produzidas
);

-- Inserir dados de exemplo
INSERT INTO Producao (DataProducao, TempoProducao, TempoIdeal, UnidadesBoas, UnidadesProduzidas)
VALUES
    ('2023-01-01 08:00:00', 240, 300, 250, 300),
    ('2023-01-02 08:15:00', 225, 240, 220, 240),
    ('2023-01-03 08:30:00', 260, 280, 270, 280),
    ('2023-01-04 08:45:00', 280, 320, 290, 320),
    ('2023-01-05 09:00:00', 210, 240, 200, 240),
    ('2023-01-06 09:15:00', 220, 240, 210, 240),
    ('2023-01-07 09:30:00', 300, 320, 310, 320),
    ('2023-01-08 09:45:00', 280, 300, 270, 300),
    ('2023-01-09 10:00:00', 260, 280, 250, 280),
    ('2023-01-10 10:15:00', 230, 240, 220, 240);
-- Você pode adicionar mais inserções de dados conforme necessário.
```

Você pode calcular o OEE com base nesses dados usando uma consulta SQL da seguinte forma:

```sql
SELECT 
    (SUM(CASE WHEN TempoProducao > 0 THEN 1 ELSE 0 END) / COUNT(*)) * 100 AS Disponibilidade,
    (SUM(UnidadesProduzidas) / SUM(TempoIdeal)) * 100 AS Desempenho,
    (SUM(UnidadesBoas) / SUM(UnidadesProduzidas)) * 100 AS Qualidade,
    ((SUM(CASE WHEN TempoProducao > 0 THEN 1 ELSE 0 END) / COUNT(*)) * 
     (SUM(UnidadesProduzidas) / SUM(TempoIdeal)) * 
     (SUM(UnidadesBoas) / SUM(UnidadesProduzidas))) AS OEE
FROM Producao;
```

Esta consulta calcula os três componentes do OEE (Disponibilidade, Desempenho e Qualidade) e depois multiplica-os para obter o OEE total.

Lembre-se de adaptar essa consulta ao seu esquema de banco de dados real e aos dados reais que você tem em sua tabela "Producao". Certifique-se de que os nomes das colunas correspondam ao seu esquema de banco de dados real.

![](https://blogdozouza.files.wordpress.com/2024/02/producao.png)
