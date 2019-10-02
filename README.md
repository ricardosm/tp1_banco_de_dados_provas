# tp1_banco_de_dados_provas

Esse repositório contém agumas provas e gabaritos de alguns anos do ENADE.

Além disso, também contém pastas de imagens referentes as provas que ocorream nesses anos.

As imagens contidas nessas pastas foram extraídas automaticamente por meio do parser criado para o trabalho.

Porém, o problema é:

O parser não consegue identificar certos tipos de imagens, gráficos e tabelas contidas nos pdfs das provas.

Diante disso, é necessário fazer o seguinte:

1. Para cada um dos anos (2012, 2013 e 2016) analisar prova por prova para verificar quais imagens, gráficos ou tabelas não foram devidamente exportados automaticamente pelo parser. 

2. Para aquelas imagens, gráficos ou tabelas que não foram exportadas, deve ser tirado um print (captura da "imagem") no formato .png e salvar a imagem gerada na pasta de imagens do devido ano da prova.

3. Além disso, para cada imagem, gráfico ou tabela que for salvo, deve ser utilizado o seguinte padrão de nomenclatura:

            Nome do curso_Enade_ANO_QUESTÂO XX_NUMERO DA IMAGEM NA QUESTAO.png

Exemplo: 

4. A segunda imagem da QUESTÂO 05 identificada na prova de Administração do ano 2012 deve ser salva na pasta "imagens_2012" com o seguinte nome:

            "Administração_Enade_2012_QUESTÃO 05_2.png" 
            
            
            
            
OBSERVAÇÂO:

Para todas as tabelas e gráficos das provas faz-se necessário gerar uma imagem no formato .png. 

É justamente esse tipo de objeto que o parser não consegue identificar no arquivo pdf.
