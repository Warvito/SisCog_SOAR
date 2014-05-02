#Sistemas Cognitivos Artificiais 

##Experiências com SOAR

o Soar é uma arquitetura cognitiva que facilita o desenvolvimento de sistemas cognitivos artificiais.
Aqui consta um projeto segundo a estrutura do VisualSoar(uma espécie de IDE p/ o SOAR), o propósito é a familiarização com o arquitetura, syntax da linguagem etc etc

###Tiro ao alvo

O ambiente é desenvolvido em python e se trata de um alvo se deslocando a velocidade constante.

 [Ambiente](http://nbviewer.ipython.org/github/ojon/SisCog_SOAR/blob/master/AmbCogSis.ipynb)
 

Um sistema cognitivo  implementado utilizando o SOAR. Este percebe o alvo se movendo, no entanto um ruido gaussiano interfere na percepção da posição. Ao perceber a posição o agente pode optar por atirar ou não, no entanto enquanto este toma a decisão o alvo continua a se mover de forma que este pode não estar na mesma posição quando ao final da decisão do agente. Após o agente decidir o que fazer este atua no ambiente e recebe um feedback, uma pontuação de acordo com a posição do alvo no instante em que o agente atirou, baseado neste feedback o agente aprende a atirar no alvo por meio de aprendizado por reforço.
