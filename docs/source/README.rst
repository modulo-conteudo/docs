========================================
Aplicativos Acessíveis - Módulo Conteúdo
========================================


O projeto *Aplicativos acessíveis* visa desenvolver um conjunto de aplicativos móveis (para Android) que se adaptam às necessidades dos estudantes com deficiência visual e auditiva, servindo de tecnologia assistiva no âmbito acadêmico. Inclui nesse conjunto: configurador/adaptador de acessibilidade, registro de aulas, assistente para provas e uso opcional de teclado tátil e o aplicativo conteúdo.

O *módulo conteúdo*, por sua vez, tem como principal motivação disponibilizar para o aluno, de forma acessível, o material didático que o professor cria ao longo do curso. Também é função do aplicativo trazer os horários das aulas e permitir que algumas funções de configuração de acessibilidade sejam editadas no próprio app; negrito, tamanho da fonte, alto contraste, cor de texto e fundo são algumas das opções possíveis.

Todo o conteúdo que o aluno consegue acessar por meio do app *Módulo Conteúdo* é sensível ao que o docente insere numa plataforma web chamada `ADD - Avaliador de documentos digitais <http://acessivel.ufabc.edu.br:8080/conteudo/>`_. Neste *web site* é verificado se o arquivo segue as diretrizes de acessibilidade e retorna os pontos a serem melhorados pelo professor. Além disso, o site mantém um índice para todos esses arquivos que podem ser descarregados automaticamente pelo *módulo conteúdo*.

Portanto, a plena funcionalidade do aplicativo depende de uma cadeia de eventos funcionando:

  #. O professor precisa disponibilizar o material no *Avaliador de documentos digitais (ADD)* (onde ele saberá se este está acessível ou não).

  #. O *ADD* mantém um endereço para todos os arquivos organizados de uma maneira que é possível saber quais são todos os documentos pesquisando pelo nome das aulas.

  #. O aplicativo *Módulo Conteúdo* conseguir descarregar do *ADD* os endereços de todos os arquivos referentes às disciplinas que o aluno utilizador está cursando.


O item 3 da lista é possível ser feito de forma automática, pois, o aluno efetua o login no app usando seu registro acadêmico da universidade. Com este registro, o aplicativo faz uma busca no banco de dados de matriculas e salva as disciplinas cursadas por aquele registro.


Todas as funcionalidades do aplicativo são descritas pelos seguintes tópicos:
