text

README.md

# Análise dos Valores de Aluguel no Rio de Janeiro

Este projeto realiza uma análise exploratória e o tratamento de dados de imóveis
para aluguel na cidade do Rio de Janeiro, com o objetivo de estruturar uma base
limpa e confiável para análises econômicas, financeiras e de mercado imobiliário.

---

## Objetivo
- Limpar e tratar uma base de dados de imóveis para aluguel
- Analisar a distribuição dos valores de aluguel
- Criar métricas de custo mensal e anual dos imóveis
- Gerar uma base final pronta para uso em análises futuras

---

## Base de Dados
A base contém informações sobre imóveis para aluguel no Rio de Janeiro, incluindo:
- Tipo do imóvel
- Bairro
- Número de quartos
- Área
- Valor do aluguel
- Condomínio
- IPTU

Após o tratamento, foram criadas duas novas variáveis:
- **Valor mensal total** (aluguel + condomínio)
- **Valor anual estimado** (valor mensal × 12 + IPTU)

---

## Metodologia
As principais etapas do projeto foram:
1. Leitura e inspeção inicial da base
2. Tratamento de valores ausentes e inconsistentes
3. Seleção da variável de interesse (valor do aluguel)
4. Criação de novas variáveis econômicas
5. Análise estatística descritiva
6. Visualização da distribuição dos preços
7. Exportação da base tratada

---

## Análises Realizadas
- Estatísticas descritivas (média, mediana e desvio padrão)

## Tecnologias Utilizadas
- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab

---

## Reprodução
1. Clone o repositório
2. Abra o notebook em 'Notebooks/'
3. Execute todas as células em sequência

---

## Observação
O notebook foi desenvolvido no Google Colab, mantendo a mesma estrutura de
diretórios do repositório para garantir reprodutibilidade.

