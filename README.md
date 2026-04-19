🎯 O Objetivo da Ferramenta
Transformar milhares de avaliações brutas em ações priorizadas. Ela não apenas mede se a nota é boa ou ruim, mas lê os comentários, entende o problema real, avalia a gravidade e cria um plano de trabalho automático para o seu time.

⚙️ Como ela funciona (O Fluxo)
Leitura: O script (via Colab) se conecta ao seu Google Sheets e puxa toda a base de reviews em segundos.

Filtro de Ruído: Descarta comentários inúteis (ex: "ok", "a") para focar no que importa, mas sem perder o peso da nota.

Classificação Inteligente: Lê o texto de cada avaliação e o encaixa em 7 motivos raiz (ex: qualidade ruim, defeito, diferente do anunciado, etc.).

Agrupamento: Junta tudo por Produto e por Seller.

Cálculo de Tendência (MoM): Compara a nota do mês atual com a do mês passado para ver se o problema está piorando ou melhorando.

Devolução Automática: Formata e pinta as células de acordo com a urgência e devolve os dados mastigados para o Sheets.

📊 O que ela entrega (As Abas)
📦 Visão Produto: Um ranking de todos os seus SKUs. Mostra o volume de notas, a média, o % de pessoas que recomendam, o problema mais citado e a variação da nota (MoM).

🏪 Visão Seller: A mesma inteligência, mas focada na performance dos lojistas. Ideal para gestão de parceiros.

📋 Tarefas (O Coração do Sistema): Onde seu time deve trabalhar todos os dias. Só lista os Produtos e Sellers que estão causando problemas reais.

🧠 As Regras de Negócio (O "Cérebro" do Sistema)
A ferramenta toma decisões sozinha com base em duas réguas que configuramos:

1. Régua de Status (Define quem entra no radar):
Aplica-se apenas a itens com 7 ou mais avaliações:

🟢 Bons: Nota acima de 3.

🟡 Atenção: Nota entre 2 e 3 (precisa de monitoramento).

🔴 Ruim: Nota abaixo de 2 (foco das tarefas).

2. Régua de Prioridade Dinâmica (Define o que fazer primeiro):
Cruza o volume de dor com a gravidade da nota para ordenar a aba de Tarefas:

🚨 1 - CRÍTICA: Mais de 25 avaliações e nota < 1.8 (Incêndio florestal).

🔥 2 - ALTA: Mais de 15 avaliações e nota < 2.2 (Fogo alto).

⚡ 3 - MÉDIA: Mais de 7 avaliações e nota < 2.5 (Fumaça).

🚀 O Grande Diferencial
A maioria das operações gasta horas por semana montando "dashboards de sentimento" que só dizem que o cenário está ruim. A sua ferramenta pula a fase do diagnóstico manual e já entrega o plano de execução.

O seu analista de CX agora chega na segunda-feira, abre a aba Tarefas, pega o ID do Produto/Loja classificado como "CRÍTICA", olha qual é o motivo resumido e já toma a ação imediata. Tempo de análise caiu de horas para zero.
