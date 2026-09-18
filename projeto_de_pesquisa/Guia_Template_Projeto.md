# Guia e Template: Projeto Aplicado em Ciência e Inovação
Objetivo deste Documento: Orientar a elaboração do projeto de pesquisa da disciplina. Este
modelo adapta o formato clássico de Iniciação Científica (normas ABNT) para a realidade de
um Projeto Aplicado na Ciência da Computação, cujo resultado final será um protótipo,
prova de conceito ou sistema validado em laboratório (Nível de Maturidade Tecnológica -
TRL 3 a 5).

---


## Estrutura exigida para o documento do projeto
Seu projeto final deve contar com as seguintes seções. Abaixo detalhamos o que escrever em
cada uma delas sob a ótica da Computação Aplicada.

## 1. Resumo e palavras-chave
Deve ser o último item a ser escrito. É o "pitch de elevador" do seu documento.
* A Estrutura (Máx. 300 palavras): Uma frase de contexto geral -> O problema identificado
-> A solução algorítmica/arquitetural proposta -> O resultado esperado.
* Exemplo de Palavras-Chave: Busca em Grafos, Otimização de Rotas, Políticas Públicas,
Algoritmo de Dijkstra.

## 2. Introdução e contextualização
A Introdução fornece uma visão geral clara de onde o projeto aterrissa no mundo real.
* O Contexto: Qual é o ecossistema afetado? (Ex: A malha viária brasileira, o sistema de
ouvidorias do SUS, a base de clientes de uma rede de minimercados).
* O Problema (A Hipótese): Descreva a "dor" de forma objetiva. O que está ineficiente, caro
ou obscuro hoje devido à falta de uma modelagem computacional adequada? Qual a
pergunta que os dados ocultam?

## 3. Justificativa
Trata-se do "Por quê". Se a Introdução apontou a dor, a Justificativa prova que vale a pena
curá-la.
* Impacto Prático (Inovação): Refletindo o Manual de Oslo, como a solução desse problema
gera valor prático? Pode ser uma inovação de processo que reduz custo ou cria um melhor
serviço comercial. Porém, não pare nas métricas de negócio: justifique os impactos sociais,
ambientais ou éticos que também nascerão dali (Ex: O algoritmo garante equidade de
tratamento na saúde? A otimização viária reduz CO2 e afeta o meio-ambiente e a qualidade
de vida local?).
* Pertinência da Computação: Por que a Computação clássica é a ferramenta correta aqui?
(Dica: o volume de dados é grande demais para análise humana, as combinações são
complexas demais para o Excel, etc).

## 4. Objetivos
Corresponde ao norte do projeto. Evite verbos vagos. Use os verbos clássicos da modelagem
e engenharia (Analisar, Modelar, Construir, Implementar, Validar).

•   Objetivo Geral: O que será entregue?
    Ex: "Modelar e implementar um protótipo de otimização de rotas para a Prefeitura de X
    utilizando algoritmos de caminho mínimo sob dados de acidentes de trânsito".



•   Objetivos Específicos: O "Geral" quebrado nas etapas de desenvolvimento (o "Como").
    Ex 1: Realizar o tratamento, limpeza e indexação da base de dados XYZ.
    Ex 2: Mapear o problema de negócio para um problema clássico de Estruturas de
    Dados/Grafos.
    Ex 3: Implementar a algoritmia de busca em linguagem Python.
    Ex 4: Validar o sistema aferindo o tempo de resposta e a acurácia dos resultados.




## 5. Revisão de literatura e soluções de mercado
Em um projeto de Computação Aplicada, a "Revisão Bibliográfica" engloba dois mundos:
1. Fundamentação Teórica (Ciência): Referenciar os algoritmos ou arquiteturas que serão
usados (Ex: Livro do Skiena, artigos sobre grafos).
2. Estado da Técnica e Mercado (O Inédito e o Aplicado): Aqui espera-se uma visão mais
geral do mercado (quais ferramentas e práticas a indústria usa hoje para resolver isso), mas
com um aprofundamento robusto no estado da arte científico. Apresente uma revisão
detalhada dos artigos e trabalhos rigorosos mais recentes (Papers) para referenciar no seu
projeto a verdadeira "fronteira" do conhecimento, e contraste com aquilo que o mercado
efetivamente absorveu.

## 6. Metodologia (Design Science / Experimental)
Este é o coração do projeto na visão de Engenharia e Ciência. Como você vai construir e
testar o artefato?
* Fonte de Dados: Qual o dataset? (Ex: INEP, Kaggle, PRF). Como ocorrerá a extração e
carga?
* A Arquitetura / Algoritmia: Descreva a técnica central. Será processamento em lote
usando árvores B? Será streaming? Será uma classificação matemática?
* Ambiente de Desenvolvimento: Linguagens (ex: Python/Jupyter, C++), bibliotecas de
base ou infraestrutura em nuvem que serão dependências do artefato.
* Plano de Validação: Como você provará que o protótipo funciona? Será por validação
cruzada? Demonstração prática? Teste de mesa com casos extremos (Corner cases)? Análise
de complexidade temporal ($O(N \log N)$)?
## 7. Resultados esperados
Lembre-se do foco da disciplina (TRL 3 a 5). O resultado não precisa ser uma startup pronta
para comercialização, mas também não pode ser apenas papel.
* Ex de Resultado: Um script validado rodando em notebook comprovando o ganho de
eficiência (TRL 3/4) + um relatório técnico indicando os ganhos sociais numbres que a
aplicação desse sistema na íntegra geraria.

## 8. Cronograma
Uma tabela simples mapeando as atividades (dos Objetivos Específicos + Escrita do Texto)
nos meses do semestre letivo.

## 9. Referências bibliográficas
Seguir o modelo ABNT tradicional. Citar manuais on-line de bibliotecas/frameworks como
páginas "Web". Citar papers fundamentais e datasets governamentais com seus URLs de
acesso e a data da extração.
