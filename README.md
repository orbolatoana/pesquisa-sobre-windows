# Explorando o Windows: Resultados e Análises da Pesquisa

O Windows é um sistema operacional da Microsoft, que oferece uma interface gráfica e recursos como multitarefa e conectividade à internet, sendo amplamente utilizado em computadores e servidores. Dentre os diversos sistemas disponíveis, o Windows se destaca como um dos mais utilizados no mundo, com uma longa história de inovações e melhorias. Este documento busca apresentar a evolução do Windows, suas versões mais marcantes, sua arquitetura e aspectos interessantes que contribuem para seu sucesso e popularidade.
___

##### Evolução dos Sistemas Operacionais ao Longo das Décadas


> Anos 1950 - Início dos Sistemas Operacionais

Nos primeiros anos da computação, os sistemas operacionais eram simples e projetados para gerenciar _mainframes_. Eram sistemas de _processamento em lote_, onde tarefas eram executadas em sequência, sem interação direta com os usuários. Um dos primeiros a ter características de um sistema operacional foi o __UNIVAC__.


> Anos 1960 - A Revolução do UNIX

 O sistema __UNIX__ foi desenvolvido nos laboratórios da AT&T nos anos 60. Ele introduziu conceitos fundamentais, como _multitarefa_, _modularidade_ e _portabilidade_. Fazendo com que se torne a base para vários outros sistemas operacionais, incluindo o _Linux_ e os sistemas operacionais baseados em _BSD_.



> Anos 1970 - Surgimento dos Primeiros Sistemas de Rede

 O conceito de redes de computadores começou a ser desenvolvido, e os sistemas operacionais começaram a incorporar capacidades para _conexões de rede_ e _compartilhamento de recursos_. O __Multics__ (Multiplexed Information and Computing Service) foi um sistema grande que inspirou muitos conceitos de sistemas operacionais modernos.



> Anos 1980 - A Era dos PCs e Interfaces Gráficas

 O __MS-DOS__ (Microsoft Disk Operating System) foi o sistema operacional que dominou os _PCs_ durante os anos 80. Ele foi lançado pela Microsoft e se tornou o padrão para a maioria dos computadores pessoais. A Apple também começou a desenvolver o _Mac OS_ nos anos 80, focado em facilitar a interação com computadores através de uma interface gráfica mais intuitiva.



> Anos 1990 - Popularização e Integração com Internet

 Em 1995, a Microsoft lançou o __Windows 95__, uma versão que integrava o _MS-DOS_ com uma interface gráfica mais moderna e incluía recursos como _multitarefa_, _plug-and-play_ e _internet_ integrada, com suporte ao navegador _Internet Explorer_. O sistema operacional __Linux__, criado por Linus Torvalds em 1991, tornou-se uma alternativa popular, principalmente para _servidores_ e usuários que procuravam uma plataforma de _código aberto_. Durante os anos 90, o UNIX se remificou em várias versões, como __Linux__  e _BSD_, com forte presença em servidores e supercomputadores.



> Anos 2000 - Dispositivos Móveis e Conectividade com a Nuvem

Lançado em 2001, o __Windows XP__ tornou-se um dos sistemas operacionais mais populares da Microsoft, com uma interface gráfica mais amigável e maior estabilidade. _Dispositivos Móveis_: iOS (2007) Lançado pela Apple para o iPhone, trouxe uma nova era de sistemas operacionais, focados na interação por toque e integração com a app store; Android (2008): Desenvolvido pelo Google, se tornou o sistema operacional líder para smartphones, com uma plataforma aberta e enorme diversidade de dispositivos.Os sistemas operacionais passaram a ser mais integrados com serviços de _nuvem_, como o _Google Drive_ e o _OneDrive_, oferecendo maior flexibilidade e armazenamento online.



> Anos 2010 - Virtualização e Computação em Nuvem

O __Windows 7__ (2009) foi uma das versões mais bem-sucedidas da Microsoft, com foco em segurança e usabilidade. Já o __Windows 10__ (2015) trouxe inovações como a __assistente virtual Cortana_, integração com _nuvem_, _segurança aprimorada_ e a __Windows Store__. O __Mac OS X__ (mais tarde renomeado para macOS) continuou a evoluir, oferecendo _interface gráfica refinada_ e forte integração com outros produtos Apple, como iPhone e iPad.O __Linux__ continuou ganhando popularidade, principalmente em servidores e em _containers_, que permitiram uma nova forma de virtualização.



> Anos 2020 - Inteligência Artificial e Sistemas Operacionais para IoT

Lançado em 2021, o __Windows 11__ trouxe uma nova _interface gráfica_ mais moderna e a integração com as tecnologias mais recentes, como _inteligência artificial_, _maior segurança_ e suporte melhorado para _dispositivos móveis_. O crescimento da **Internet das Coisas (IoT)** resultou em sistemas operacionais especializados, como __Windows IoT__, _Google Fuchsia_ e _FreeRTOS_, projetados para dispositivos conectados. O papel da IA nos sistemas operacionais se tornou cada vez mais relevante, com assistentes virtuais como:
- Cortana;
- Siri;
- Google Assistante;
- Alexa se integrando aos sistemas operacionais de desktop e móveis;

---

 ##### Algumas das versões importantes do Windows

- __Windows 95__
Ano de lançamento: 1995
Principais inovações: Introdução do Menu Iniciar, interface gráfica aprimorada, suporte a multitarefa, suporte para plug-and-play (instalação automática de dispositivos) e a primeira integração significativa da Internet.

- __Windows XP__

Ano de lançamento: 2001
Principais inovações: Nova interface gráfica "Luna", maior estabilidade e segurança em relação às versões anteriores, introdução do "Fast User Switching" (troca rápida de usuários), e melhor suporte a redes sem fio e dispositivos externos.

- __Windows 7__

Ano de lançamento: 2009
Principais inovações: Desempenho melhorado, novo Aero Snap para organização de janelas, barras de tarefas personalizáveis, aprimoramento na segurança e maior compatibilidade com hardware moderno.

- __Windows 10__

Ano de lançamento: 2015
Principais inovações: Retorno do Menu Iniciar, Cortana (assistente virtual), Edge (novo navegador), recursos de múltiplas áreas de trabalho, integração com dispositivos móveis e a atualização contínua (Windows as a Service).

 - __Windows 11__

Ano de lançamento: 2021
Principais inovações: Novo design com cantos arredondados e centro de notificações, melhoria na integração com aplicativos Android, suporte aprimorado para jogos (como Auto HDR e DirectStorage), e novos recursos de produtividade como Snap Layouts.

> Exemplo de imagem do windows XP


![windows xp](https://upload.wikimedia.org/wikipedia/pt/8/8f/Windows_XP_SP3.png)

--- 

 ##### Arquitetura do Windows 

> _Kernel:_ 
   - Gerencia a comunicação entre hardware e software.
   - Controla processos, memória, dispositivos e segurança.

> _Gerenciador de Processos:_ 
   - Coordena execução de programas e multitarefa.
   - Gerencia alocação de tempo de CPU.

> _Gerenciador de Memória:_ 
   - Controla o uso da memória RAM e virtual.
   - Gerencia troca entre RAM e disco rígido.

> _Sistema de Arquivos:_
   - Organiza e armazena dados em dispositivos de armazenamento.
   - Exemplo: NTFS, que oferece segurança e compactação.

> _Interface Gráfica do Usuário (GUI):_ 
   - Permite interação visual via janelas, ícones e menus.
   - Exemplo: Windows Desktop, onde o usuário interage com o sistema.

> _Gerenciador de Dispositivos:_ 
   - Controla e monitora dispositivos de hardware.
   - Instala e gerencia drivers de dispositivos.

> _Drivers:_ 
   - Permitem comunicação entre o sistema operacional e o hardware.
   - Traduzem instruções do sistema para comandos de hardware.

> _API (Interface de Programação de Aplicações):_ 
   - Fornece funções para desenvolvedores criarem programas para o Windows.
   - Permite interação com o sistema operacional.

> _Gerenciador de Rede:_ 
   - Gerencia a conectividade com redes e a internet.
   - Controla protocolos e configurações de rede.

> _Segurança e Controle de Acesso:_ 
   - Gerencia autenticação e permissões de acesso.
   - Exemplo: Controle de Conta de Usuário (UAC).

> _Windows Services:_ 
   - Processos em segundo plano que executam funções essenciais.
   - Exemplo: Atualizações do sistema, serviços de rede e impressoras.

---

 ##### 5 comandos comuns no Windows e suas funções

```
dir
```

Função: Exibe a lista de arquivos e pastas em um diretório.
Exemplo de uso: dir C:\ — Mostra todos os arquivos e pastas na unidade C.

```
cd
```

Função: Altera o diretório de trabalho atual no prompt de comando.
Exemplo de uso: cd C:\Users\Nome — Muda para a pasta "Nome" dentro de "C:\Users".

```
copy
```

Função: Copia arquivos de um local para outro.
Exemplo de uso: copy arquivo.txt D:\Backup\ — Copia o arquivo "arquivo.txt" para a pasta "Backup" no disco D.

```
del
```

Função: Exclui arquivos do diretório atual.
Exemplo de uso: del arquivo.txt — Exclui o arquivo "arquivo.txt" no diretório atual.

```
ping
```

Função: Verifica a conectividade de rede com outro dispositivo ou servidor.
Exemplo de uso: ping www.google.com — Envia pacotes para o Google para testar a conexão de rede.

Esses comandos são úteis para navegação, gerenciamento de arquivos.

---

 ##### Curiosidades sobre o Windows


- _Origem do nome "Windows"_
  
O nome "Windows" vem da ideia de usar "janelas" (windows) para organizar e exibir informações na tela, o que era uma inovação em relação aos sistemas baseados em linha de comando.

- _O Windows 1.0 tinha apenas um "bloco de notas" e "calculadora"_
  
Lançado em 1985, o Windows 1.0 era basicamente uma interface gráfica para o MS-DOS, e sua funcionalidade era bem limitada, com apenas alguns aplicativos simples como Bloco de Notas e Calculadora.

- _A tecla "Windows" foi inspirada no "Super" de outros sistemas_

A famosa tecla com o logo do Windows no teclado foi inspirada na tecla "Super" dos sistemas Unix, usada para acessar funções especiais. Ela foi criada para facilitar o acesso a recursos do sistema no Windows.

- _O primeiro Windows não tinha minimização, maximização ou sobreposição de janelas_

No Windows 1.0, as janelas não podiam ser sobrepostas, apenas organizadas lado a lado. Isso só foi introduzido com versões posteriores, como o Windows 2.0 (1987).

- _O Windows XP teve um "sucesso imenso" e durou muito mais do que o esperado_

Apesar de ser lançado em 2001, o Windows XP foi tão popular que a Microsoft continuou oferecendo suporte e atualizações para ele até 2014, o que fez com que muitos usuários o utilizassem por mais de uma década.

- _O famoso "som de inicialização" do Windows tem um nome_

O som que você ouve ao iniciar um computador com Windows 95 e versões posteriores é chamado de "Microsoft Sound". Ele foi criado por Brian Eno, o famoso compositor de música ambiente.





 
