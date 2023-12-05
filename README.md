
Jogo de correspondência de memória
Este é um jogo simples de correspondência de memória desenvolvido com HTML, CSS e JavaScript. O jogo consiste em uma grade de cartas, cada uma exibindo um emoji de comida. O objetivo é encontrar todos os pares de cartas clicando neles.

Características
Cartas de Emoji Randomizadas: O jogo começa embaralhando uma série de emojis e, cada vez que você joga, as posições dos emojis nas cartas são aleatórias.

Interface interativa: Clique nos cartões para revelar os emojis. O jogo permite que você abra duas cartas por vez.

Lógica de correspondência: se os emojis nos cartões abertos corresponderem, eles permanecerão abertos e serão marcados como correspondentes. Caso contrário, os cartões são fechados novamente.

Alerta de vitória: quando todos os pares forem combinados com sucesso, um alerta notificará você sobre sua vitória.

Uso
Abra o index.htmlarquivo em um navegador da web.
Clique nos cartões para revelar os emojis.
Tente encontrar todos os pares correspondentes de memória.

Explicação do código

A emojismatriz contém o conjunto de emojis usados ​​no jogo.
A shuffleEmojismatriz é criada embaralhando aleatoriamente a emojismatriz para determinar as posições iniciais dos emojis nas cartas.
A grade do jogo é criada dinamicamente usando JavaScript, com cada cartão tendo um ouvinte de evento ( handleClick) anexado a ele.
A handleClickfunção permite abrir cartões e chamadas checkMatchquando dois cartões são abertos.
A checkMatchfunção verifica se os cartões abertos correspondem e atualiza suas classes de acordo.
O jogo continua até que todos os pares sejam combinados.
Como personalizar.

Sinta-se à vontade para personalizar o jogo:

Adicionando mais emojis ao emojisarray.
Modificando a aparência dos cartões através de CSS.
Ajustando a lógica do jogo em JavaScript.
Divirta-se jogando e personalizando o jogo!
