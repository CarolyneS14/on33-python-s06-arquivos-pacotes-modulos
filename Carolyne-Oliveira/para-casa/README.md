# 🎥🎞️📽️ Filmes

# 📚 Descrição da Atividade
Exercicio para casa semana 06.\
Na planilha Filmes.csv temos alguns filmes e as notas que os usuário deram para cada um deles.

1. Crie uma nova tabela com a média de cada filme
2. Quantas pessoas assistiram aquele filme
3. Encontre o nome do filme com a maior média
4. Não esqueça de remover as duplicatas.


# 📋 Passo a Passo
1. Remover duplicadas:
   
        =UNIQUE($B$2:$B$15)

3. Média de cada filme:
   
        =ARRAYFORMULA(MÉDIASE($B$2:$B$15; $E$2:$E$4; $C$2:$C$15))

5. Quantidade de pessoas assistiram aquele filme:
   
        =ARRAYFORMULA(CONT.SE($B$2:$B$15; $E$2:$E$4))

7. Filme com a maior média:
   
        =ÍNDICE($E$2:$E$4; CORRESP(MÁXIMO($F$2:$F$4); $F$2:$F$4; 0))


# 👩🏻‍🏫 Profa. Eduarda Arduini
Professora [Eduarda Arduini](https://github.com/arduini-eduarda)
