# Datathon Dermatite Atópica

## Introdução
A dermatite atópica (DA) é uma doença crônica que se manifesta em crianças, mas que pode persistir até a adolescência. A DA tem 3 formas de apresentação: leve, moderada e grave. Quando a DA está na forma grave, necessita de internação. Segundo o IBGE há  aproximadamente um universo de 27 milhões de crianças de até 9 anos no Brasil. Vários trabalhos mostram que a prevalência da doença pode chegar até 12%, assim, calcula-se que um número enorme de possíveis pacientes podem ter DA. Atualemte o sistema único de saúde (SUS) não disponibiliza o tratamento  ideal  aos pacientes com DA, tratamento este já disponível na assistência médica privada. A disponibilização do tratamento mais adequada aos pacientes do sistema público de saúde permitirá melhor controle da doença, evitando internações e diminuindo o impacto da DA na sociedade.

## Objetivo
Gerar dados sobre o impacto da dermatite atópica na saúde pública do Brasil e do brasileiro, com o objetivo de responder as seguintes perguntas:
1. Qual o custo anual médio dos pacientes com dermatite atópica grave para o sistema público de saúde?
2. Como se caracteriza a utilização de recursos do sistema público de saúde por pacientes com DA moderada a grave?
3. Qual a relação dos custos indiretos (licença médica, aposentadora precoce, DALY, etc) dos pacientes com dermatite atópica moderada a grave e seus cuidadores, comparando a outras doenças dermatológicas?

## Métodos
Através da bases de dados disponibilizadas pelo Datathon e utilizando a linguagem de dados Python inicialmente, classificamos os pacientes com DA em 2 grupos: forma grave e forma leve a moderada. Esta classificação foi realizada levando-se em consideração as informações contidas nos dataset como: tipo de medição em uso, atendimento ambulatorial, número de internações e registros em APAC.
Este novo dataset construído com os dados agrupados foi utilizado para responder as perguntas.

## Tecnologia
Para responder  as duas perguntas foi utilizado a linguagem de programação Python e os dados serão apresentados em um dashboard produzidos no Streamlit. 

## Resultados 

* Vídeo explicando o trabalho

* Bases utilizadas
  * As bases disponibilizadas pela equipe Eretz.bio
  * [pasta Google Drive](https://drive.google.com/drive/folders/1VYhhuypVbD0GPk32CZjPID9lzi4VHdhm?usp=sharing)
  

* Código fonte
  * [notebook 1](https://github.com/suebatista/hackathon/blob/main/dermatite.ipynb)
  * [notebook 2](https://github.com/suebatista/hackathon/blob/main/dermatite_inss.ipynb)

* Dashboard de visualização dos dados 
  * [dashboard](https://share.streamlit.io/suebatista/hackathon_dermatitis/main/hackathon/main.py)


## DataDES Membros
* Danilo Gouvea Silva – Cientista de Dados (danilo.gouveasilva@gmail.com)
* Eduardo Rogério Malaquias Chagas – Médico (eduardo.chagas@alumni.usp.br)
* Suelen Cristina Batista da Silva – Cientista de Dados (suelen.cristina.batista@gmail.com)

