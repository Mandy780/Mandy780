Olá

 Ferramenta de Controle de Investimentos com Excel para iniciantes
 
 O projeto consiste em construir uma planilha que ajude o investidor iniciante a realizar simulações, ajudando-o a tomar decisões mais conscientes sobre seus investimentos. O projeto tem como objetivo automatizar cálculos difíceis, como o valor total investido, o patrimônio acumulado e os dividendos mensais, e também com  sugestões de investimentos de acordo com o seu tipo de perfil, fornecendo ao usuário uma visão precisa de seu potencial retorno.

 Ferramenta de Controle de Investimentos no Excel para Iniciantes

 Descrição

Este projeto consiste em uma planilha desenvolvida no Microsoft Excel com o objetivo de ajudar investidores iniciantes a controlar seus investimentos de forma simples, organizada e visualmente clara.


 
Estrutura da Planilha

As planilhas contém as seguintes informações:

| Cabeçalho            | Descrição                                                       
        
| Configurações        | Salário mensal, rendimento carteira e sugestão de investimento(30% do salário)                  
| Investimento mensal  | Para ser preenchido pelo usuário: quanto investir por mês, por quantos anos, taxa de rendimento mensal. patrimônio acumulado e dividendos mensais(Resultados)
| Cenário pré-definido | Quanto em 2 anos, quanto em 5 anos,quanto em 10 anos, quanto em 20 anos, quanto em 30 anos, cenários pré-definidos para facilitar a visualização
| Dividendo            | Dividendos de acordo com o tempo do cenário pré-definido,valor investido e taxa.   
| Perfil               | Agressivo,conservador e moderado (sugestão de investimento de acordo com o perfil escolhido)              
| Tipo de FII          | PAPEL,TIJOLO, HÍBRIDO,FOFS,DESENVOLVIMENTO E HOTELARIAS(possíveis investistimentos de acordo com o perfil escolhido)
| percentual sugerido  | Percentual de investimento sugerido de acordo com o perfil escolhido                             
| Valores              | Valores a serem investidos de acordo com o percentual sugerido     
                            


  Fórmulas Utilizadas

Sugestão de investimento: Salário mensal*rendimento carteira
Patrimônio acumulado: VF(Taxa_mensal;qntd_anos*12;Aporte*-1)
Dividendo mensal: patrimônio acumulado*rendimento carteira
Cenários: VF(taxa;nper;pgto*-1)
Dividendo: Anos*rendimento_carteira
Conservador: Filtro
Percentual sugerido: Procv(conservador &"-"& tipo de FII;matriz tabela;coluna;0)
Valores:percentual sugerido*Aporte
Chave:Perfil&"-"& tipo de fII

 A criação desta ferramenta envolveu:

Simplicidade para fácil entendimento do usuário
Cuidado com layout e linguagem para tornar intuitivo
Criação de sugestões para facilitar a escolha do usuário de acordo com seu perfil e aposte.





