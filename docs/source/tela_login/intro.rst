===============
Tela de login
===============

A tela de login (:numref:`figlogin`) é responsável por coletar o registro academico (R.A.) do usuário e validar essa informação no banco de dados.

.. _figlogin:
.. figure:: ./assets/login.png
    :align: center
    :scale: 30

    :Visão geral tela de login

O aplicativo apresenta um erro em uma *SnackBar* (:numref:`figloginerro`) caso o R.A. não tenha sido encontrado.

.. _figloginerro:
.. figure:: ./assets/login_erro.png
    :align: center
    :scale: 30

    :Tela de login com erro


Caso seja inserido um R.A. válido, o usuário é encaminhado para a tela principal, onde é possivel navegar para as seguintes telas:

1. Tela de aulas (primeira a ser aberta)
2. Tela de arquivos
3. Central de ajuda
4. Central de configuração

O que precisa ser feito
=======================

1. Implementar a funcionalidade do botão libras.

Problemas conhecidos
====================

1. Existe um erro durante a primeira execução do aplicativo na qual, mesmo inserindo um R.A. válido, o aplicativo retorna a informação que o R.A. não foi encontrado. O erro será corrigido assim que a tela de boas vindas for implementada.

