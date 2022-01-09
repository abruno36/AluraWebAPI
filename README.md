# Entity Framework Core parte 1: App MVC para API  

> ## Informações
>
> **Objetivo:**     
>
> Fizemos o relacionamento de filmes com atores, ou seja, um relacionamento de cardinalidade N:N (muitos para muitos). Um filme possui um elenco de vários atores e um ator pode atuar em vários filmes. Contudo, o Entity Framework Core não suporta esse tipo de cardinalidade onde criamos uma classe que será responsável pelo relacionamento entre outras duas classes.  
---
> **Classe Principal:** considerada a classe independente da relação.
>
> **Classe Dependente:** classe dependente da relação, ou "classe filha". É nela que reside a chave estrangeira.

<img src="https://github.com/abruno36/AluraWebAPI/blob/master/Alura.WebAPI.WebApp/wwwroot/images/fluxoBase.png" alt="Entidades"/>

> **Chaves Estrangeiras:** propriedades existentes na classe dependente que guardam o valor da classe principal, podem ser shadow properties.


> ## Nível Criticidade
> - [x] - Alto  
> - [ ] - Médio  
> - [ ] - Baixo  
>  
---

> ## Tecnologias
>
> **Frameworks:**  
> - **Entity Framework CORE 4.7 **  
>
> **Tipo de Banco de dados:**  
> - **SQL Server**

>

---







