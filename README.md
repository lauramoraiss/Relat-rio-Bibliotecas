### Relat-rio-Bibliotecas



# OpenCV

**O que é →**

O Open Source é uma biblioteca open-source para visão computacional e processamento de imagens. Ele possui uma licença na qual permite o usuário utilizar, modificar e distribuir o software.

**Criador do Opencv →**

O OpenCV foi criado pela intel, e eo seu principal desenvolvedor e líder inicial foi o Gary Bradsk, na qual atuava como engenheiro da intel e também como pesquisador de IA e visão computacional.

O mesmo criou visando fornecer uma biblioteca gratuita e otimizada, podendo tanto ser usada pela indústria e pesquisa acadêmica.

**História →**

Em 1999 a Intel lançou o projeto somente para uso interno.

↓

Em 2006 a primeira versão chegou para uso público.

↓

Em 2009 houve a implementação de APIs C++ entre outras coisas (OpenCV).

↓

Em 2023 traz a implementação do backend Vulkan e melhorias JS/Python (OpenCV 4.8.0).

↓

Em 2025 com a versão 4.12.0 foi liberada com suporte ao C++ 20.

**Linguagens e Plataformas →**

O OpenCV foi projetado para ser multiplataforma. Ele foi escrito nativamente na biblioteca C++, e a biblioteca do OpenCV suporta Windows, Linux, Android, IOS, MacOS, e possui interfaces C++, Python, Java, MATLAB.

**Como funciona →**

➤ Nível conceitual:

Pega imagens e vídeos e aplica nelas operações matemáticas e lógicas.

➤ Entrada de dados:

Carrega dados de várias fontes.

➤ Processamento de imagem/vídeo:

Após ler a imagem/vídeo ele possibilita aplicar operações 

➤ Exibição ou salvamento de resultado:

→ Mostrar em janelas

→ Salvar em disco

→ Exportar com vídeo

**Principais recursos→**

- Core

Funções básicas com imagens

- Imgprock:

Ajusta e transforma images

- Features2d

Encontra pontos importantes em imagens

- Calib3d:

Trabalha com visão e medidas em 3D

- Obidetect/Tracking:

Detecção de faces

- DNN:

Usa redes para reconhecer e identificar objetos em imagens e vídeos 

- ML interno:

Conjunto de métodos de aprendizado para analisar e classificar

- G-API:

Ferramenta para criar e acelerar o processamento de imagens 

**Pontos positivos →**

- Gratuito
- open source
- Grande comunidade
- Documentação boa
- Integração com outras tecnologias (python, c++, java, windows, linux, android, Maemo, IOS)
- Biblioteca rica e completa

**Concorrentes do mercado →**

- Pillow:

*→ Vantagens:* Simples de usar, ótima para manipulação básica de imagens (corte, redimensionamento, filtros), boa integração com Python puro.

*→ Desvantagens:* Pouco voltada para visão computacional avançada, não possui recursos nativos para detecção de objetos, faces, etc.

- Scikit image:

*→ Vantagens:* Baseada em NumPy/SciPy, fácil integração com bibliotecas científicas, boa para processamento e análise de imagens, código limpo.

*→ Desvantagens:* Mais lenta em operações pesadas, não é ideal para aplicações em tempo real, menos suporte para hardware acelerado.

- Dlib:

*→ Vantagens:* Excelente para detecção e reconhecimento facial, suporte a Machine Learning integrado, bem otimizada em C++.

*→ Desvantagens:* Pouco flexível fora de aplicações de faces, comunidade menor que a do OpenCV.



# Selenium e Pyautogui

### **➤ Selenium**

***O que é →***

O Selenium é um conjunto de ferramentas e bibliotecas utilizado para realizar a automatização de navegadores web.

***Para que usar →***

É usada principalmente para teste automatizados de aplicações web, porém também pode ser usada para automatizar tarefas em navegadores (Como, por exemplo, tarefas diárias).

***Suportes →***

O Selenium oferece suporte para diversos tipos de navegadores e sistemas operacionais, assim como também para diversas linguagens de programação (**Chrome, Firefox, Edge e outros. E para as linguagens de programação Java, Python, C#, Ruby e JavaScript**.)

***Componentes →***

- Selenium Webdriver:

→ Controla navegadores reais como Chrome e Firefox de forma programada.

- Selenium IDE:

→ Controla navegadores reais como Chrome e Firefox de forma programada.

- Selenium Grid:

→ Permite executar testes em paralelo em diferentes máquinas e navegadores.

***Pontos positivos →***

- Redução de erros de teste
- Melhor utilização de tempo para o desenvolvedor
- Melhor feedback para o desenvolvedor
- Muporte para metodologias ágeis
- Documentação disciplinada

***Pontos negativos →***

- Falta de suporte para aplicativos
- Recursos limitados para relatórios
- Problemas de desempenho
- Curva de aprendizado ingrime para iniciantes
- Suporte limitado para interações

### **➤ Pyautogui**

***O que é →***
PyAutoGUI é uma biblioteca Python desenvolvida para **automatizar tarefas na interface gráfica do sistema operacional (GUI)**. Ela possibilita o controle programático do mouse e teclado, captura de tela, execução de cliques, movimentos e outras interações, simulando ações que normalmente seriam realizadas manualmente, mas de forma automatizada, o que proporciona considerável ganho de eficiência.

***Como funciona →***

A biblioteca converte comandos escritos em Python em eventos que são enviados diretamente ao sistema operacional. Para isso, PyAutoGUI utiliza bibliotecas internas que acessam as APIs nativas de cada sistema operacional, replicando funções para controle do mouse e teclado. Dessa forma, o sistema interpreta essas instruções como interações reais do usuário, executando-as nos aplicativos ativos de maneira natural.

***Funcionalidades principais →***

- **Movimentação e cliques do mouse:** Permite controlar o cursor e realizar cliques simples ou múltiplos com precisão programática.
- **Digitação de texto:** Possibilita simular a entrada de texto em qualquer campo de texto ativo.
- **Pressionamento de teclas:** Simula pressionamentos e combinações de teclas para interagir com aplicativos.
- **Abertura e navegação:** Facilita a automação de tarefas como abrir programas, navegar em sites e interagir com interfaces por meio do teclado.

***Cuidados e limitações →***

- O PyAutoGUI depende de coordenadas fixas na tela, o que pode tornar scripts sensíveis a alterações na resolução ou layout.
- Não possui inteligência para reconhecer ou interpretar elementos da interface gráfica.
- Pode apresentar falhas em ambientes com aplicações complexas que utilizem tecnologias avançadas.
- É recomendada a realização de testes em diferentes configurações para garantir estabilidade.



# Bibliotecas de interface gráfica

### ➤ TKINTER

***O que é →***
Tkinter é a biblioteca padrão do Python para criação de interfaces gráficas (GUIs). Ela é um *wrapper* (interface) em Python para a toolkit GUI chamada **Tk**, que foi criada originalmente para a linguagem Tcl.

***Quem criou →***

Foi criado por John Ousterhout nos anos 1980.

***Pontos positivos →***

- Conhecido pelo fácil modo de aprendizagem.
- Compatível com a plataforma windows
- Possui uma comunidade bem rica com fóruns

***Pontos negativos →***

- Visual bem simples
- Opções são limitadas
- Organização da interface não possui tanta liberdade
- Ferramentas de design limitadas

***Funcionamento →***
O funcionamento do Tkinter baseia-se na criação de uma hierarquia de widgets, que são elementos visuais como botões, caixas de texto e rótulos. Esses widgets são organizados dentro de janelas, e a biblioteca mantém um loop de eventos, que fica constantemente escutando ações do usuário, como cliques e teclas pressionadas. Quando um evento ocorre, Tkinter aciona funções associadas (callbacks) para tratar a interação e atualizar a interface. A disposição dos widgets é gerenciada por gerenciadores de geometria, que controlam a posição e o tamanho dos elementos na janela.

### ➤ PYQT

***O que é →***
PyQt é um *binding* (ligação) Python para a **Qt Framework**, um poderoso framework C++ para desenvolvimento de GUIs modernas e multiplataforma

***Quem criou →***

Foi criado por Phil Thompson  em 1998, pela Riverbank Computing.

***Pontos positivos →***

- Interface moderna
- Compatível com windows, linux, micro OS
- Grande comunidade
- Linguagem C++

***Pontos negativos →***

- Linguagem mais complexa
- Possui muitos recursos
- Documentação em C++
- Não é recomendado para iniciantes por possuir recursos muito complexos.

***Funcionamento →***
Utiliza um sistema avançado conhecido como **sinais e slots** para o gerenciamento de eventos dentro da aplicação. Nesse modelo, quando uma determinada ação ocorre — como o clique de um botão, a alteração de um valor ou qualquer outra interação do usuário — um **sinal** é emitido. Esse sinal pode então ser conectado a um ou mais **slots**, que são funções ou métodos responsáveis por responder a esse evento de forma programada, permitindo que diferentes partes da interface ou do programa reajam de maneira coordenada e eficiente. Além disso, o PyQt oferece suporte a layouts automáticos e suporte de temas.



# Numpy

## 

***O que é →***

NumPy (Numerical Python) é uma biblioteca fundamental para a linguagem Python, voltada para o processamento e manipulação eficiente de dados numéricos por meio de arrays multidimensionais. Ela oferece suporte avançado para operações matemáticas, científicas e de engenharia, sendo considerada a base para diversas outras bibliotecas importantes do ecossistema Python

***Quem criou →***

Foi criada em 2005 por Travis Oliphant

***Características principais →***

- **Estruturas de dados eficientes:**

→ Possui o objeto `ndarray`, que representa arrays multidimensionais de tamanho fixo e tipos homogêneos, armazenados em blocos contínuos de memória, garantindo alta eficiência e rapidez no acesso e manipulação dos dados.

- **Operações vetoriais e matriciais:**

→ Permite a realização de operações aritméticas, estatísticas e algébricas em arrays inteiros, eliminando a necessidade de loops explícitos, o que acelera o processamento.

- **Suporte para álgebra linear:**

→ Inclui funções para multiplicação de matrizes, decomposições, autovalores, entre outras.

- **Transformadas de Fourier:**

→ Facilita a análise e manipulação de sinais por meio de transformadas rápidas (FFT).

- **Compatibilidade com outras bibliotecas científicas:**

→ NumPy serve como alicerce para muitas bibliotecas, integrando-se perfeitamente a ferramentas voltadas para ciência de dados, aprendizado de máquina e visualização.

- **Memória contígua e localidade de referência:**

 → A organização dos dados em blocos contíguos favorece a performance, explorando o cache do processador e otimizando o uso da memória.

***Pontos positivos →***

- Performance superior
- Operações vetorizadas
- Suporte para grandes conjuntos de dados
- Extensa biblioteca de funções
- Interoperabilidade

***Pontos negativos →***

- Tipos homogêneos (armazenam um único tipo de dado)
- Manipulação limitada de dados textuais
- Curva de aprendizado inicial ruim para iniciantes
- Gerenciamento de memória estático



# Pandas

***O que é →*** 
Pandas é uma biblioteca open source amplamente utilizada no ecossistema Python para ciência de dados, voltada para o processamento, limpeza, transformação e análise exploratória de dados estruturados e semiestruturados. Fornece estruturas de dados de alto desempenho e ferramentas intuitivas que facilitam a manipulação de dados tabulares e séries temporais, sendo um componente essencial para projetos de análise, estatística e machine learning.

***Quem criou →***
Foi desenvolvida inicialmente por Wes McKinney em 2008

***Pontos positivos →***

- Sintaxe intuitiva e expressiva
- Documentação extensa e rica
- Integração com outras bibliotecas
- Comunidade ativa e suporte

***Pontos negativos →***

- Consumo elevado de memória
- Não é ideal para Big Data

***Estruturas fundamentais →***

- **Series:**

 → Estrutura unidimensional que armazena uma sequência de dados junto com um índice para identificação de cada elemento. É análoga a um array rotulado, permitindo o acesso fácil e eficiente aos dados.

- **DataFrame:**

→ Estrutura bidimensional semelhante a uma tabela, composta por linhas e colunas rotuladas. É a estrutura central do Pandas, que suporta operações avançadas de manipulação, seleção e transformação de dados.



# Matplotlib e Seaborn

### **➤** MATPLOTLIB

***O que é →***

É a biblioteca fundamental para criação de visualizações gráficas em Python, amplamente utilizada em ciência de dados, engenharia e pesquisa científica. Ela oferece controle detalhado e granular sobre praticamente todos os aspectos dos gráficos, permitindo a criação desde gráficos simples, como linhas e barras e até visualizações complexas e altamente customizadas.

### **➤** SEABORN

***O que é →***

Desenvolvida como uma camada de abstração sobre o Matplotlib, o Seaborn simplifica a criação de visualizações estatísticas e esteticamente agradáveis. Ele oferece estilos visuais prontos e temas integrados que facilitam a criação de gráficos sofisticados com menos código. O Seaborn também inclui ferramentas específicas para análise exploratória de dados

***Integrações →***

Tanto Matplotlib quanto Seaborn são compatíveis com:

- **NumPy:** Para manipulação eficiente de arrays e cálculos matemáticos que alimentam as visualizações.
- **Pandas:** Para análise e manipulação de dados estruturados em DataFrames, permitindo a criação de gráficos diretamente a partir dessas estruturas.

***Curiosidades →***

**Matplotlib:**

→ Criada por John D. Hunter em 2003, a biblioteca foi desenvolvida inicialmente para suprir a necessidade de visualização científica no Python. Matplotlib teve um papel importante em projetos científicos de grande impacto, como a produção da primeira imagem de um buraco negro.

**Seaborn:**

→ Seu nome possivelmente foi inspirado em um personagem da série de TV

*The West Wing*
