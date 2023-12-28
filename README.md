# Lista_5
# Case 5

1- Defina uma tupla com 3 strings e use o print para ver como ela se apresenta.

2- Agora defina outra tupla com valores numéricos.

3- Agora defina uma tupla com vários tipos de dados dentro da mesma tupla.

4- Cada valor dentro da tupla fica salvo como um índice que começa em 0 e vai aumentando de 1 em 1 até o último termo da tupla.
      
      Então para a tupla abaixo:
       
       [0] [1] [2] [3]
       
       t2 = ( 1,  3,  5,  7 )
       
    Para a tupla acima tente imprimir cada um dos seus valores.
    
5- Imprima a soma de cada valor desta tupla.

6- Também é possível acessar mais de 1 valor ao mesmo tempo colocando entre os colchetes de onde até onde você quer acessar.

            t2[0:2] : são os 2 primeiros valor desta tupla : 1, 3
            
            t2[2:4] : são o 3º e o 4º valor desta tupla : 5, 7
            
            t2[:3] : são os 3 primeiros valor desta tupla : 1, 3, 5
            
            t2[2:] : é do 3º ao último termo desta tupla : 5, 7
            
            t2[-1] : é último termo desta tupla : 7
            
      Lembre-se que assim como no range o último valor dentro do colchete não é acessado.
      Vamos testar os itens acima?
      
7- Verifique o tipo das variáveis:

            t3
            
            t3[0]
            
            t3[1]
            
            t3[2]
            
            t3[0:2]
            
            t3[1:]

8- Utilizando as tuplas abaixo:

      t1 = ('Lanche', 'Batata', 'Refri')
      
      t2 = (0, 6, 4, 2, 8, 6, 4)
      
      t3 = (1, 3, 3, 5, 3, 5, 7)
      
      Faça:
      
      - Calcule o tamanho das tuplas: t1 e t2
      
      - Imprima as tuplas ordenadas: t1 e t2 e depois reimprima-as
      
      - Conte quantas vezes aparecem o valor 3 na t3
      
      - Procure onde aparece o valor 'Refri' na t1
      
      - Procure o valor 5 na t3 após o 4º termo
      
      - Concatene as tuplas t2 e t3    

9- Dada a tupla:

      t1 = ('Lanche','Refri','Batata')
      
      Imprima seus valores

10- Dado a tupla t2 some todos os seus valores.

11- Plote os itens da tupla t1, mostrando os seus índices, como se fosse um cardápio.

12- Dada a tupla abaixo:

      t1 = ('Doce', 'Churrasco', 'Bala ', 'Tapioca', 'Pizza ', 'Feijão ',
            'Arroz ', 'Açaí ', 'Paçoca ', 'Acarajé', 'Pamonha', 'Dobradinha', 'Rapadura')
            
      Faça um programa que:
      
      O usuário digita uma comida e seu programa diz em qual posição do cardápio esse item está.
      
      Printe os itens em ordem alfabética para o usuário

13- Dado a tupla abaixo:

      t1 = ('Doce', 2.3, 'Bala ', 0.15, 'Pizza ', 28.9, 'Arroz ', 4.5, 'Paçoca ', 0.5, 'Pamonha', 5.4)

      Os dados estão organizados de forma que tem o valor do produto e logo após o seu preço. 
      
      Faça um programa que:
      
      Mostre o cardápio de forma organizada.

14- Dado a mesma tupla do exercício anterior faça um programa que:

      O usuário visualiza o cardápio e digita qual item ele quer comprar. 
      
      A seguir pergunta se ele quer algo a mais. Caso ele queira vai somando todos os valores do pedido numa variável soma.
      
      No final printe para o usuário o valor total da conta dele.
