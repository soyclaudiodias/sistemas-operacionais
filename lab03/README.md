### Integrantes/Funções:
<ul>
  <li>Cláudio Dias Alves (10403569): Responsável pelo desenvolvimento do código
  <li>Guillermo Kuznietz (10410134): Responsável pela clonagem e salvamento do repositório 
  <li>Gabriel Nogueira (10409493): Responsável pela documentação
</ul>

# 1. Compilar o programa
``` git clone git@github.com:<url_do_seu_repositorio> ```

![Captura de tela 2024-03-16 182046](https://github.com/soyclaudiodias/sistemas_operacionais/assets/113221142/f4508790-1987-466e-be3e-e31d1dac6347)

# 2. Executar o programa
``` ./exercicio02.c ```

![Captura de tela 2024-03-16 184420](https://github.com/soyclaudiodias/sistemas_operacionais/assets/113221142/3347e7f0-c2a7-4d8e-9d74-cc1f9c832986)

# 3. Análise do resultado
<p align="justify">
No código modificado, a variável global shared_data é usada para facilitar a comunicação entre a thread pai e a thread filho. A thread filho altera o valor de shared_data para 10. Essa alteração é visível para a thread pai, que imprime o novo valor após a conclusão da thread filho. Isso demonstra a troca de informações de contexto entre as threads.

Quando rodar o programa, deve aparecer no terminal:
><br>Criando thread filho
<br>Thread filho está encerrando e modificando shared_data
<br>Thread filho retornou e pilha foi liberada. 
<br>shared_data = 10
</p>
