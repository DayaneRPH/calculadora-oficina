🔢 **Calculadora de entrada de caixa**


<img width="300" alt="Demonstração da calculadora" src="https://github.com/user-attachments/assets/9f395049-ce19-4c82-bf10-ee8098275b5a" />



**Overview**

Projeto realizado no primeiro período do curso de Ciência de Dados. O objetivo é ajudar no registro de entrada de caixa de um pequeno negócio, auxiliando no cálculo diário de valores recebidos por cada serviço.

**Produto final:**  link para uma calculadora personalizada para o negócio, em que o comerciante insere a quantidade de produtos afiados no dia e obtém o cálculo automaticamente. O intuito foi gerar uma calculadora o mais simples possível, considerando: baixo letramento digital, premissa *mobile firts*, pouco tempo entre os atendimentos para registro. 

---

**Apresentação do negócio**

A microempresa selecionada para este projeto é a Oficina do Galego, localizada em Recife, Pernambuco. O estabelecimento atua no segmento de afiação de objetos cortantes, como alicates de unha, tesouras de unha e de cabelo, facas e serrotes.O estabelecimento está situado em um mercado público, região que reúne supermercados, feira livre e açougues.

Na realidade atual do negócio, os serviços realizados e os pagamentos são controlados de memória, sem o auxílio de planilhas ou sistemas informatizados de registro.

---

**A solução**

A solução é uma calculadora personalizada para a Oficina do Galego, criada com a inteligência artificial *Claude*. A ferramenta permite inserir, pelo celular, a quantidade diária de serviços realizados e obter automaticamente o faturamento  por categoria e o total do dia. Os valores já estão previamente preenchidos, mas são editáveis.


A calculadora será usada ao fim do expediente, no qual o fluxo de atendimento é mínimo. Durante o dia, as anotações serão manuais, em prancheta ou caderno. Dessa forma, não prejudica a rotina de trabalho do estabelecimento.

O *Claude* disponibilizou o HTML, o publiquei no GitHub, para que o acesso necessitasse apenas do link, sem login no *Claude* ou download de qualquer app.


📲 Link da calculadora: https://dayanerph.github.io/calculadora-oficina/

---

**Prompt:** 

Crie uma calculadora online simples, com visual limpo e adaptado para celulares, para uma pequena oficina de afiação de ferramentas.

A tela deve permitir informar a quantidade de serviços realizados no dia nas seguintes categorias, com os respectivos preços unitários já preenchidos automaticamente:


Alicate de unha: R$ 5,00

Tesoura de unha: R$ 4,00

Tesoura de cabelo: R$ 5,00

Faca: R$ 6,00

Serra e serrote: R$ 10,00

Os preços devem aparecer preenchidos por padrão, mas precisam ser editáveis pelo usuário. Se o usuário alterar um preço, os cálculos devem ser atualizados automaticamente.

O sistema deve calcular automaticamente o faturamento de cada categoria e o faturamento total do dia, com base nas quantidades informadas e nos preços unitários.

Inclua um botão para limpar os campos de quantidade e começar um novo cálculo, mantendo os preços padrão originais.

Não preciso de cadastro, login, gráficos ou banco de dados. Os cálculos devem funcionar diretamente na página.

A interface deve ser intuitiva, com textos grandes, campos fáceis de tocar pelo celular e valores formatados em reais (R$). Crie a interface completa e funcional.

