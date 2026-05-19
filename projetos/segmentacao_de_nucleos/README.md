# Segmentação de núcleos em imagens histológicas com deep learning: comparação entre arquiteturas e datasets
# Nuclei segmentation in histological images using deep learning: A comparison between architectures and datasets

## Apresentação

O presente projeto foi originado no contexto das atividades da disciplina de pós-graduação *IA901 - Análise de Imagens e Reconhecimento de Padrões*, 
oferecida no primeiro semestre de 2026, na Unicamp, sob supervisão da Profa. Dra. Leticia Rittner, do Departamento de Engenharia de Computação e Automação (DCA) da Faculdade de Engenharia Elétrica e de Computação (FEEC).

|Nome  | RA | Curso|
|--|--|--|
| Alysson Matos de Souza  | 265057  | |
| Lucas Fiuza Garcia  | 300901  | Mestrado em Engenharia Elétrica |
| Vinicius Barbosa Bassete  | 248135  | Mestrado em Física Aplicada|


## Descrição do Projeto
> Descrição do objetivo principal do projeto, incluindo contexto gerador, motivação, etc. Qual problema você pretende solucionar? Qual a relevância do problema e o impacto da solução do mesmo?

## Metodologia
> Proposta de metodologia incluindo especificação de quais técnicas pretende-se explorar. Espera-se que nesta entrega você já seja capaz de descrever de maneira mais específica (do que na Entrega 1) quais as técnicas a serem empregadas em cada etapa do projeto.

## Bases de Dados e Evolução

Base de Dados | Endereço na Web | Resumo descritivo
----- | ----- | -----
PanNuke | https://warwick.ac.uk/fac/cross_fac/tia/data/pannuke/ | Grande dataset com 7904 amostras de imagens histológicas de diferentes tecidos, além de máscaras de segmentação e anotaçãoe sobre a histologia. Este dataset se destaca pela quantidade e diversidade nas amostras.
NuInsSeg | https://www.kaggle.com/datasets/ipateam/nuinsseg | Dataset com 665 amostras de imagens histológicas anotadas, desenvolvido com foco em treinar e avaliar modelos de segmentação de núcleos celulares em imagens de microscopia.
MoNuSeg | https://monuseg.grand-challenge.org/Data/ | Dataset com 44 imagens histopatológicas de diversos órgãos em alta resolução com anotações feitas manualmente por especialistas. Criado originalmente para uma competição, se tornou um benchmark frequentemente usado em pesquisas de patologia digital.

> Forneça também o link para o "datasheet" criado para os datasets (anexado na pasta `data`, como indicado nas [instruções E2](https://github.com/Disciplinas-FEEC/IA901-2026S1/blob/main/templates/ia901-E2-instructions.md)), contendo informações mais detalhadas e sistematizadas sobre as bases de dados.

## Ferramentas
> Ferramentas e/ou bibliotecas já utilizadas e/ou ainda a serem utilizadas (com base na visão atual do grupo sobre o projeto).

## Workflow
> Use uma ferramenta que permita desenhar o workflow e salvá-lo como uma imagem (Draw.io, por exemplo). Insira a imagem nesta seção.
> Você pode optar por usar um gerenciador de workflow (Sacred, Pachyderm, etc) e nesse caso use o gerenciador para gerar uma figura para você.
> Lembre-se que o objetivo de desenhar o workflow é ajudar a quem quiser reproduzir seus experimentos.
> Mais informações sobre o workflow podem ser encontradas nos materiais de apoio no Classroom (Reprodutibilidade em pesquisa computacional - workflow).

## Experimentos e Resultados preliminares
> Descreva de forma sucinta e organizada os experimentos realizados.
> Para cada experimento, apresente os principais resultados obtidos.
> Aponte os problemas encontrados nas soluções testadas até aqui.

## Próximos passos
> Liste as próximas etapas planejadas para conclusão do projeto, com uma estimativa de tempo para cada etapa.

## Uso de IA Generativa
> Adicione aqui em quais tarefas foi usada alguma ferramenta de IA Generativa. Para cada tarefa indicada detalhe qual a ferramenta e qual o prompt utilizado.
- Implementação de script para geração de samples: O Claude foi utilizado para gerar um script base de geração da pasta '*\data\samples'. Foram feitas diversas adaptações em cima desse script base, para que essa geração se adequasse ao projeto.
    - Prompt Utilizado: "baseado no notebook (00_installation.ipynb), implemente um script que gere samples para os dados dos datasets"

## Referências
> Seção obrigatória. Inclua aqui referências utilizadas no projeto.