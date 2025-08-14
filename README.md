# EstagioLuis
Repositório para o teste-estágio do Luís

Dia 1 - Aprendi a mexer um pouco no Github. Aprendi um pouco de Python. E aprendi que de alguma forma o TravelBI tem acesso a mais dados vindos do INE do que aqueles que eu tenho acesso

Dia 2 - Apesar de ter um ficheiro CSV, precisa de um cleaning devido aos totais por regiões estarem incluidos com os valores individuais dos diferentes concelhos.
Concluí o que me faltava do dia 3, porque havia banstante overlap e organizei um bocadinho melhor, não que se note
Aprendi a instalar SQL no pc. Ainda não aprendi a importar ficheiros CSV para lá. Honestamente, só instalar já foi complicado que cheguei. Tentei originalmente usar o Colab, porque aquilo é python e dar para importar libraries de sql lá, mas aqui estava a dar-me erros de 'database is locked' que tornava impossivel. Então tentei instalar direto no pc que também demorou, mas já está. Até fiz o peqeuno tutorial que o sqlite tem para ver se estava a funcionar, e estava

Dia 4 - Ontem estive ocupado e por isso não há dia 3. Hoje estive a obter do INE. Separei por NUTS e depois por municipios. Fiz uma limpeza inicial a todos, mas ao do municipios fiz mais. Nesse há falta de dados, alguns municipios não tem informação de dormidas em certos meses, provavelmente devido ao pequeno número de dormaidas e possivel isolação do municipio. Mas isso deu trabalho. Porque o tratamento que eu fiz foi em Excel e o ficheiro é csv, e por alguma razão era impossivel fazer uma correta localização e substituição dos valores em falta, que eram simboloziados nas células como: ? ?. Infelizmente, as células com os nomes dos municipios, apesar de estar visivelmente corretos, eram conhecidos como conterem o '? ?' e ao 'substituir todos', os nomes eram alterados.
Portanto o que aprendi. Não fazer limpezas de CSV em Excel? Também aprendi, como mencionado algures neste documento, que o TravelBI tem mais informações do que eu tenho pelo INE, ou pelo menos, de mais anos atrás, porque a nivel de municipios só tenho até 2022. E os dados que o TravelBI tem não dão para ser extraidos ou exportados, pelo menos eu não sei
