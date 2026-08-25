# Google Colab + CMPL — Programação Inteira

Repositório com exemplos, tutoriais e arquivos para modelagem e resolução de **Problemas de Programação Inteira e Programação Linear Inteira Mista (MILP)** utilizando **CMPL** em conjunto com **Google Colab**.

O objetivo deste projeto é facilitar o estudo e a prática de **Pesquisa Operacional**, permitindo que modelos matemáticos sejam executados diretamente em notebooks do Google Colab, sem a necessidade de configurar um ambiente local complexo.

---

## 📚 Sobre o projeto

Este repositório reúne materiais didáticos e exemplos práticos de modelagem matemática utilizando a linguagem **CMPL (Coliop)**.

Os exemplos foram organizados para ajudar tanto quem está tendo o primeiro contato com programação matemática quanto quem deseja utilizar modelos prontos como referência para desenvolver seus próprios problemas de otimização.

Entre os problemas disponíveis estão:

* 🚚 Problemas de transporte;
* ✂️ Problemas de corte e estoque;
* 🎒 Problemas da mochila;
* 🎯 Problemas de designação;
* 🏭 Problemas de dimensionamento de lotes;
* 📍 Problemas de localização com custo fixo;
* 💰 Seleção de investimentos;
* 📅 Sequenciamento de tarefas;
* 🔢 Problemas com conjuntos discretos de opções;
* 📊 Outros modelos de Programação Inteira.

---

## 🚀 Por que utilizar o Google Colab?

O **Google Colab** permite executar notebooks Jupyter diretamente no navegador, sem exigir uma instalação completa do ambiente de programação no computador.

Neste projeto, ele é utilizado como uma forma prática de executar os modelos e acompanhar os exemplos passo a passo.

Isso torna o material especialmente útil para:

* estudantes de Pesquisa Operacional;
* disciplinas de Otimização;
* cursos de Engenharia de Produção;
* cursos de Engenharia de Sistemas;
* estudantes de Ciência da Computação;
* pesquisadores;
* pessoas que desejam aprender modelagem matemática.

---

## 📂 Organização do repositório

O projeto está organizado principalmente em duas pastas:

```text
GoogleColab-Coliop-CMPL/
│
├── exemplos/
│   ├── arquivos .cmpl
│   └── notebooks .ipynb
│
├── tutorial/
│   ├── arquivos .cmpl
│   ├── notebooks .ipynb
│   ├── arquivos .cdat
│   ├── arquivos .xdat
│   └── arquivos .xlsx
│
└── LICENSE
```

### 📖 `tutorial/`

Contém materiais destinados ao aprendizado e à compreensão da utilização do CMPL.

Entre os arquivos disponíveis estão exemplos relacionados ao **Problema de Transporte**, incluindo modelos gerais, modelos com dados externos e notebooks para execução no Google Colab.

Também estão disponíveis arquivos utilizados em exemplos de videoaula.

### 🧪 `exemplos/`

Contém uma coleção de problemas de otimização já modelados em CMPL.

Entre eles:

| Exemplo    | Problema                            |
| ---------- | ----------------------------------- |
| Exemplo 3  | Cutting Stock Problem               |
| Exemplo 4  | Cutting Stock Problem               |
| Exemplo 5  | Problema da Mochila                 |
| Exemplo 6  | Problema da Mochila Binária         |
| Exemplo 7  | Problema de Designação              |
| Exemplo 8  | Problema de Designação Generalizada |
| Exemplo 9  | Dimensionamento de Lotes Capacitado |
| Exemplo 10 | Localização com Custo Fixo          |
| Exemplo 11 | Seleção de Investimentos            |
| Exemplo 12 | Sequenciamento de Tarefas           |
| Exemplo 13 | Conjunto Discreto de Opções         |

Cada problema possui, quando disponível, tanto o **modelo CMPL (`.cmpl`)** quanto um **notebook Jupyter (`.ipynb`)** para facilitar a execução e o estudo.

---

# 🧑‍💻 Como começar

## 1. Acesse o repositório

Clone ou faça o download deste repositório:

```bash
git clone https://github.com/brenoassis32/GoogleColab-Coliop-CMPL.git
```

Ou simplesmente faça o download dos arquivos pelo GitHub.

---

## 2. Escolha um exemplo

Para começar, recomenda-se utilizar um dos exemplos mais simples, como:

* Problema da Mochila;
* Problema da Mochila Binária;
* Problema de Transporte;
* Problema de Designação.

Os exemplos estão disponíveis na pasta:

```text
exemplos/
```

---

## 3. Abra o notebook no Google Colab

Os arquivos `.ipynb` podem ser executados no **Google Colab**.

Uma forma prática é abrir o notebook desejado no GitHub e utilizar a opção **Open in Colab**, quando disponível.

Também é possível acessar diretamente o notebook pelo endereço do arquivo no repositório e abri-lo através do Colab.

---

# 🧮 O que é CMPL?

**CMPL (Coliop Mathematical Programming Language)** é uma linguagem utilizada para descrever modelos de **Programação Matemática**.

A ideia é separar a formulação matemática do problema da forma como o modelo será resolvido.

De maneira simplificada, um modelo de otimização normalmente possui:

### Variáveis de decisão

Representam as decisões que precisam ser tomadas.

### Função objetivo

Representa aquilo que desejamos maximizar ou minimizar.

### Restrições

Representam as regras e limitações do problema.

### Domínio das variáveis

Define se as variáveis podem assumir valores contínuos, inteiros ou binários.

---

# 🔎 Como estudar os exemplos

Uma boa estratégia para utilizar este repositório é seguir os seguintes passos:

### 1. Entenda o problema

Antes de olhar o código, tente identificar:

* Qual é o objetivo?
* Quais decisões precisam ser tomadas?
* Quais são os recursos disponíveis?
* Quais são as restrições?

### 2. Identifique as variáveis

Procure no modelo CMPL quais variáveis representam as decisões do problema.

### 3. Analise a função objetivo

Verifique se o modelo está tentando:

* maximizar alguma medida; ou
* minimizar alguma medida.

### 4. Analise as restrições

Observe como as regras do problema foram transformadas em expressões matemáticas.

### 5. Execute o notebook

Depois de entender o modelo, execute o notebook no Google Colab e observe os resultados.

### 6. Modifique os dados

Uma ótima forma de aprender é alterar os valores de entrada e observar como a solução ótima muda.

---

# 📓 Tutorial

A pasta `tutorial/` contém materiais que podem ser utilizados como ponto de partida para aprender a trabalhar com CMPL e Google Colab.

Entre os materiais estão exemplos do **Problema de Transporte**, incluindo:

* modelo geral;
* modelo utilizando dados externos;
* dados em arquivos;
* planilha Excel;
* notebooks Jupyter;
* exemplo utilizado em videoaula.

Confira:

📁 [`tutorial/`](https://github.com/brenoassis32/GoogleColab-Coliop-CMPL/tree/main/tutorial)

---

# 🧪 Exemplos

Depois de compreender o funcionamento básico, explore a pasta de exemplos:

📁 [`exemplos/`](https://github.com/brenoassis32/GoogleColab-Coliop-CMPL/tree/main/exemplos)

Ela contém diferentes modelos clássicos de Pesquisa Operacional que podem ser utilizados tanto para estudo quanto como referência para a construção de novos modelos.

---

# 💡 Dica para novos usuários

Se você está começando agora, **não tente entender todos os exemplos de uma vez**.

Comece com um problema simples, entenda a formulação matemática e depois compare essa formulação com o modelo escrito em CMPL.

Uma sequência interessante de estudo é:

```text
Problema da Mochila
        ↓
Problema da Mochila Binária
        ↓
Problema de Designação
        ↓
Problema de Transporte
        ↓
Problemas de Corte e Estoque
        ↓
Modelos de Planejamento e Localização
```

Depois disso, tente modificar um dos modelos existentes para criar uma nova versão do problema.

---

# 🤝 Contribuições

Sugestões, correções, novos exemplos e melhorias são bem-vindos.

Se você encontrar algum problema ou tiver uma sugestão para melhorar o material, utilize as ferramentas de colaboração disponíveis no GitHub.

---

# 📄 Licença

Este projeto está disponibilizado sob a licença **GNU General Public License v2.0 (GPL-2.0)**.

Consulte o arquivo [`LICENSE`](https://github.com/brenoassis32/GoogleColab-Coliop-CMPL/blob/main/LICENSE) para conhecer os termos completos da licença.

---

# 👤 Autor

Projeto mantido por **Breno Assis**.

🔗 [GitHub — brenoassis32](https://github.com/brenoassis32)

---

## ⭐ Gostou do projeto?

Se este material foi útil para seus estudos, considere deixar uma ⭐ no repositório.

Isso ajuda a tornar o projeto mais fácil de encontrar e incentiva a continuidade da organização e disponibilização dos exemplos.

**Bons estudos e boa modelagem! 🚀**
