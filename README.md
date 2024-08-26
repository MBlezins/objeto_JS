#Objetos
Prototype

#Prototype
A propriedade prototype é um objeto adicionado a uma função quando a mesma é criada.

![image](https://github.com/user-attachments/assets/fe99a2e5-72fb-40d5-ade2-f4766db35d74)



#Funcao.prototype
É possível adicionar novas propriedades e métodos ao objeto prototype.

![image](https://github.com/user-attachments/assets/419dcecb-dc59-465b-b6af-0e694c05670a)


#Acesso ao Protótipo
O objeto criado utilizando o construtor, possui acesso aos métodos e propriedades do protótipo deste construtor. Lembrando, prototype é uma propriedade de funções apenas.
![image](https://github.com/user-attachments/assets/7feb6312-e7e6-495e-9de0-54d117f07562)


#Proto
O novo objeto acessa os métodos e propriedades do protótipo através da propriedade __proto__. É papel da engine fazer essa busca, não devemos falar com __proto__ diretamente.
![image](https://github.com/user-attachments/assets/5b9e3160-95e9-46e1-8f82-b9d4159d0a11)

#Herança de Protótipo
O objeto possui acesso aos métodos e propriedades do protótipo do construtor responsável por criar este objeto. O objeto abaixo possui acesso a métodos que nunca definimos, mas são herdados do protótipo de Object.
![image](https://github.com/user-attachments/assets/fd53c094-bb7b-449d-9e53-0c603764d569)

#Construtores Nativos
Objetos, Funções, Números, Strings e outros tipos de dados são criados utilizando construtores. Esses construtores possuem um protótipo com propriedades e métodos, que poderão ser acessadas pelo tipo de dado.
![image](https://github.com/user-attachments/assets/a01dc72a-35ee-49b3-aff0-bea178555b83)

