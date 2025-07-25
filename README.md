# 📊 Análise de Vendas - Projeto AluraStoreBr Challenge - Data Science

![Badge em Desenvolvimento](https://img.shields.io/badge/Status-Concluído-green)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-1.3.0-blueviolet)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.4.3-orange)

## 🔍 Sumário
- [Objetivo](#-objetivo)
- [Contexto do Projeto](#-contexto-do-projeto)
- [Visão Geral](#visao-geral-do-projeto)
- [Começando](#-começando)
  - [Pré-requisitos](#-pré-requisitos)
  - [Instalação](#-instalação)
- [Executando a Análise](#-executando-a-análise)
- [Estrutura do Projeto](#-estrutura-do-projeto)
- [Principais Análises](#-principais-análises)
- [Conclusões](#-conclusões-e-recomendações)
- [Como Contribuir](#-como-contribuir)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Contato](#-contato)

---

## 📌 Objetivo <a name="-objetivo"></a>
Identificar qual loja deve ser vendida com base em métricas de desempenho financeiro e satisfação do cliente.

[↑ Voltar ao sumário](#-sumário)

---

## 🔍 Contexto do Projeto <a name="-contexto-do-projeto"></a>
Este projeto foi desenvolvido como parte do **Challenge de Data Science da Alura**, com o objetivo de demonstrar habilidades em:
- Análise exploratória de dados
- Visualização profissional
- Tomada de decisão baseada em dados

## 🔍 Visão Geral do projeto
Análise completa das vendas de 4 lojas da rede Alura Store para ajudar o Senhor João a decidir qual loja da sua rede vender para iniciar um novo empreendimentda, com insights sobre faturamento, produtos mais vendidos, satisfação dos clientes e distribuição geográfica.
Para isso, foi preciso analisar dados de vendas, desempenho e avaliações das 4 lojas fictícias da Alura Store. O objetivo foi identificar a loja com menor eficiência e apresentar uma recomendação final baseada nos dados.

[↑ Voltar ao sumário](#-sumário)

---

## 🚀 Começando <a name="-começando"></a>

### 📋 Pré-requisitos <a name="-pré-requisitos"></a>
- Python 3.8+
- Gerenciador de pacotes Pip...

### 🔧 Instalação <a name="-instalação"></a>
```bash
git clone https://github.com/seu-usuario/analise-lojas.git
```

## 🧮 Executando a Análise <a name="-executando-a-análise"></a>
Opção 1: Via Jupyter Notebook
Opção 2: Via Google Colab [Google Colab](https://colab.research.google.com/)

[↑ Voltar ao sumário](#-sumário)

## 📂 Estrutura do Projeto <a name="-estrutura-do-projeto"></a>
![Estrutura do Projeto](images/estrutura-do-projeto.png)


[↑ Voltar ao sumário](#-sumário)

## 📊 Principais Análises <a name="-principais-análises"></a>
1. Comparativo de Faturamento


![Faturamento por Loja](images/faturamento.png)
- **Loja 3** lidera com **R$180.000** (25% acima da média)
- **Loja 4** tem o pior desempenho (**R$90.000**, 40% abaixo da média)
- Diferença de **100%** entre a melhor e pior loja

**Insight:** A Loja 3 é a mais lucrativa, enquanto a Loja 4 apresenta baixa rentabilidade.

2. Vendas por Categoria.


![Distribuição por Categoria](images/categorias.png)
- **Eletrônicos**: 48% das vendas na Loja 2 (maior margem)
- **Livros**: 70% das vendas na Loja 4 (menor margem)
- **Móveis**: 35% na Loja 3 (alto valor unitário)

**Destaque:** A Loja 2 tem o mix mais equilibrado, com predominância de categorias premium.


3. Desempenho e Avaliações.

   
![Avaliação Média](images/avaliacoes.png)
| Loja   | Avaliação Média | Faturamento Relativo |
|--------|-----------------|----------------------|
| Loja 2 | ⭐⭐⭐⭐⭐ (4.7)   | 110%                 |
| Loja 3 | ⭐⭐⭐ (3.9)      | 125%                 |

**Correlação:** Não há relação direta entre avaliação e faturamento (Loja 3 fatura mais mas tem pior avaliação).


4. Produtos mais e menos vendidos.

   
![Top Produtos](images/produtos.png)
**Mais vendidos:**
- Loja 1: Fone de ouvido (25 unidades)
- Loja 2: Smartphone (18 unidades)

**Menos vendidos:**  
- Loja 4: Livro de Python (5 unidades)
- Loja 3: Sofá (3 unidades)

**Padrão:** Produtos de alto valor têm melhor desempenho nas Lojas 1 e 2.


5. Frete médio por loja.

| Loja   | Frete Médio | Impacto nas Vendas |
|--------|-------------|--------------------|
| Loja 2 | R$8.99      | +15% conversão     |
| Loja 3 | R$15.20     | -10% reclamações   |

**Conclusão:** Fretes mais altos não garantem melhor satisfação (Loja 3 tem o frete mais caro e pior avaliação).


[↑ Voltar ao sumário](#-sumário)

##💡 Conclusões e Recomendações <a name="-conclusões-e-recomendações"></a>
Recomenda-se vender a Loja 4 devido aos fatores abaixo:

✔ **Justificativas quantitativas:**
- 35% abaixo do faturamento médio
- 62% dos produtos são livros (margem < 15%)
- Frete 18% mais caro que a Loja 2

✔ **Fatores qualitativos:**
- Baixo potencial de crescimento no segmento
- Clientes menos fiéis (taxa de retorno 12% vs 25% outras)

**Ações sugeridas:**
1. Negociar venda da Loja 4 no próximo trimestre
2. Reinvestir capital nas Lojas 2 e 3
3. Implementar programa de fidelidade na Loja 1

[↑ Voltar ao sumário](#-sumário)


## 🤝 Como Contribuir <a name="-como-contribuir"></a>
Faça um Fork do projeto.


[↑ Voltar ao sumário](#-sumário)

## 🛠️ Tecnologias Utilizadas <a name="-tecnologias-utilizadas"></a>
Python 3.8


Pandas...


Matplotlib



[↑ Voltar ao sumário](#-sumário)



## ✉️ Contato <a name="-contato"></a
👩‍💻 Autora          
Ludmila Garcia


[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ludmila-garcia/)


[![GitHub](https://img.shields.io/badge/GitHub-000?logo=github&logoColor=white)](https://github.com/Ludmila-Garcia)



[↑ Voltar ao sumário](#-sumário)
