# Cronograma de Horas de Estudo
🎯 Objetivo
Este é um sistema de gestão de tempo de estudo em linha de comando (CLI) desenvolvido em Python. Seu objetivo principal é acompanhar o progresso em múltiplas matérias, utilizando um sistema de Banco de Horas para incentivar a consistência e penalizar a falta de estudo.

✨ Funcionalidades Principais
Gestão de Múltiplas Matérias: Cadastro de metas totais (ex: 44h para Python).

Registro Diário: Entrada simples das horas estudadas por matéria.

Cálculo Dinâmico do Banco de Horas:

Crédito: Horas excedentes são acumuladas.

Débito/Penalidade: Em caso de falta (não estudar em um dia útil), é descontado 50% das horas estudadas no dia útil anterior do saldo acumulado.

Visualização Gráfica:

Gráficos diários de progresso.

Relatório Mensal: Gráfico de plotagem de dias, horas trabalhadas vs. linha da meta, com resumo final do cumprimento da meta.

⚙️ Tecnologias
Linguagem: Python

Bibliotecas: Pandas (para gestão de dados), Matplotlib (para visualização)

Ambiente: Google Colab

Versionamento: Git

📝 Estrutura do Projeto (Em Desenvolvimento)
main.py: Ponto de entrada e lógica principal.

data/: Pasta para armazenar os arquivos de dados (ex: registros.csv, metas.json).

plots.py: Módulo para a geração dos gráficos (matplotlib).

requirements.txt: Lista de dependências Python.

README.md: Documentação do projeto.
