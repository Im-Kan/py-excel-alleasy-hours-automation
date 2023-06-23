# py-excel-alleasy-hours-automation
projeto para automatizar a criação do excel de horas para a AllEasy.
# Dependências
[Python](https://www.python.org/) <br>
[openpyxl](https://openpyxl.readthedocs.io/en/stable/)
```console
pip install openpyxl
```
# Como funciona?
Basicamente:<br>
  1.Baixar o excel do Times Explorer que é exportado no 7pacetimetracker (Plugin do devops) <br>
  ![image](https://github.com/Im-Kan/py-excel-alleasy-hours-automation/assets/90940106/25bac97a-87be-4f7f-9d5c-25df91d49d1f) ![image](https://github.com/Im-Kan/py-excel-alleasy-hours-automation/assets/90940106/f1ca4173-fbcd-4bc9-8620-08e3c3c65b47)
  2.Colocar na pasta time_explorer_excel <br>
  3.Atualizar as informações do model.xlsx(colocar o nome) <br>
  4.Executar no terminal com a data no formato m/yyyy (ex: 06/2023) <br>
```console
py main.py [mm/yyyy] [Nome Para o arquivo final]
```
