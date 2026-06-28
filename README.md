
Estrutura básica

1o lado 400px 2o lado 820
pading 20px ao redor e gap de 20px
total 1280px

20+400+10 = 430 33,6%
10+820+20 = 850 66,4%

ajustando margens e atribuindo altura para funcionar o grid

2o montando aside
bg-im no css
bg-size cover
bg repeat - no repeat

overflow hidden para aparecer raio de bordas

posição relativa para objetos ficarem dentro (mas parece que não fez efeito nenhum)
css completo do aside

3o começando o main
uso do ícone como svg direto no html para atribuir cor no desenho (strokes)

4o fazendo layout
fieldset
começando a parametrizar os forms e inputs no html e css

5o levei um baile para fazer os campos rádios que parecem botões. Altura de linha sempre estava diferente porque havia esquecido de delimitar a imagem interna do campo.

6o radio de cores... usei a mesma estrutura anterior, com uma mudança... variável de cor atribuída direto no atributo html label - type sugerida pela IA. código ficou mais limpo.

surgiu duvida de como acessar um campo específico
exemplos:
.color-options input[type="radio"] {
  display: none;
}
"[]" usado para chegar ao atributo html
___________________________________________________
input:checked  input:focus  a:hover li:first-child  
":" usado para posição ou estado
___________________________________________________
input::before  
input::after     
::-webkit-calendar-picker-indicator
"::" parte visual criada pelo css
___________________________________________________

.color-options:has(.radio-inner) 
var()
color: rgb ( , , )
width: minmax(1rem, 1fr);
width: calc(100% - 2rem);
"()" usado em função para atribuir um valor
___________________________________________________
outra atibuição apareceu aqui:
.color-options input[type="radio"]:checked + label

estrutura dentro do color-options
input
label 
"+" verifica o elemente seguinte e só aplica se for ele, se a estrutura fosse:
input
legend
label 
aqui falharia sem acusar erro, pois não aplicaria o css já que o proximo elemento ao input não é o label
para essa condição deveria ser utilizado o "~" - till (procura nos próximos elementos até que ache)



7o baile de novo Radio seleção do tipo de evento

ajuda de ia o tempo todo, não consegui colocar raio de bordas nas imagens dentro do cards, talvez teria que criar mais uma div.

8o Estilo e caixinha de envio de arquivo

9o Restante do projeto, IA se perdeu, tive que voltar e olhar as aulas e o projeto parecido já feito. 
Precisa melhorar a seção do estilo claro ou escuro e o botão do file.
