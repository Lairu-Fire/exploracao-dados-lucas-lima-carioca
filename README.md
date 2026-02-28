# exploracao-dados-lucas-lima-carioca
Atividade da matéria de ciencia de dados.

# Microdados do Exame Nacional de Avaliação da Formação Médica - Enamed (INEP)
[link de acesso](https://dados.gov.br/dados/conjuntos-dados/microdados-do-exame-nacional-de-avaliao-da-formao-mdica---enamed)

Microdados públicos do Exame Nacional de Avaliação da Formação Médica (Enamed), aplicado pelo Ministério da Educação pela primeira vez em outubro de 2025. São apresentados dados gerais do exame, incluindo notas, respostas aos itens e informações do questionário socioeconômico.


* Número de registros: 39794
* Colunas: 27


## Significado das variáveis

* NU_ANO: Ano de realização do exame (2025).

* CO_CURSO: Código de identificação do curso de graduação do participante.

* CO_CADERNO: Código do modelo de prova (1 ou 2) respondido pelo participante.

* DS_VT_ACE_OBJ: Vetor de 100 caracteres que representa o acerto (1) ou erro (0) do participante em cada uma das 90 questões válidas da prova. As outras posições podem conter '6' (anulada) ou '8' (desconsiderada pela TRI). Esta é a variável mais importante para análises de desempenho.

* TP_PR_GER: Tipo de presença na prova. Valores comuns: 555 (Presente com resultado válido), 222 (Ausente), 334 (Eliminado).

* PROFICIENCIA: A proficiência do participante na prova objetiva, calculada pela Teoria de Resposta ao Item (TRI). É uma nota padronizada (valor theta).

* NT_GER: A nota da prova objetiva, calculada a partir da TRI, em uma escala de 0 a 100.

* QT_ACERTO_AREA_1 a QT_ACERTO_AREA_5: Número de acertos em cada uma das cinco grandes áreas da medicina (Clínica Médica, Pediatria, Cirurgia Geral, Ginecologia e Obstetrícia, Medicina da Família e Comunidade/Saúde Coletiva).

* PER_ACERTO_ENARE: Percentual de acertos para fins do Enare, considerando questões anuladas e desconsideradas.

* CO_RS_I1 a CO_RS_I9: Respostas do Questionário de Percepção da Prova, com códigos de 'A' a 'E' para cada pergunta (ex: dificuldade da prova, tempo gasto, clareza dos enunciados).
