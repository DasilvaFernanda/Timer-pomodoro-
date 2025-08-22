🕒 Pomodoro Timer

Um timer baseado na **Técnica Pomodoro**, desenvolvido em **HTML, CSS e JavaScript**, pensado para aumentar foco e produtividade no dia a dia.  

Ele permite controlar blocos de estudo ou trabalho, alternando automaticamente entre ciclos de **25 minutos de foco**, **5 minutos de pausa curta** e **15 a 20 minutos de pausa longa**, com direito a **alertas sonoros**, **notificações**, **atalhos de teclado** e um **tema escuro de alto contraste** ideal para acessibilidade.

como funciona?
Basta abrir o projeto no navegador e clicar em **Start** para iniciar o ciclo. Ao final do período, um alerta sonoro e/ou notificação será exibido, orientando a iniciar a pausa. A cada quatro ciclos completos, uma pausa longa é sugerida.  
Os principais atalhos de teclado são:  
- `Space`: iniciar/pausar o timer  
- `R`: resetar o ciclo atual  
- `N`: pular para o próximo estágio (foco/pausa)  

As durações dos ciclos podem ser ajustadas diretamente na interface (ex.: 25/5/15) e ficam salvas automaticamente no navegador através do `localStorage`.

🖥️ Rodando o projeto
Você pode rodar de duas formas:  
- **Abrindo direto**: baixe ou clone o repositório e abra o arquivo `index.html` em qualquer navegador moderno.  
- **Servidor local (recomendado)**:  
  ```bash
  python -m http.server 5500
  # depois acesse: http://localhost:5500
