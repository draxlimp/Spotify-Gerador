Um gerador de códigos Spotify moderno e minimalista, inspirado no design elegante da Tesla. Esta ferramenta permite gerar, verificar e gerenciar links de códigos Spotify de forma eficiente, com funcionalidades de webhook para Discord e geração em massa.

🚀 Funcionalidades
Gerador de Link Único:
Gera um link de código Spotify aleatório.
Simula a validade do código com uma taxa de acerto de 60%.
Exibe uma porcentagem de chance de validade e o status (Válido/Inválido) após a geração.
Botões para copiar o link gerado e aberto diretamente no Spotify.
Webhook Discord:
Envie links de códigos Spotify válidos diretamente para um webhook do Discord.
Configure a quantidade de links a serem enviados (até 100 por vez).
Feedback de status do envio.
Verificador de Link:
Cole qualquer link de código do Spotify para verificar sua validade (simulada).
Feedback visual claro sobre a validade do link.
Gerador em Massa:
Gere vários links de códigos Spotify de uma vez (até 500).
Exibe a quantidade de códigos válidos gerados, o tempo de geração e a taxa de acerto.
Opções para copiar todos os links gerados ou baixá-los em um arquivo TXT.
Alternador de tema:
Alterne facilmente entre o tema escuro (padrão) e o tema claro.
O tema preferido é salvo no armazenamento local do navegador.
Design Minimalista e Moderno:
Estilo visual inspirado no design limpo e sofisticado da Tesla, com foco em cores neutras, tipografia elegante e espaço generoso.
Animações de transição suaves para uma experiência de usuário fluida.
Ícones minimalistas e modernos.
✨ Tecnologias Utilizadas
HTML5: Estrutura da página.
CSS3: Estilização personalizada e responsividade.
Tailwind CSS: Framework CSS para importados e configuração de tema.
JavaScript (ES6+): Lógica de geração, verificação, interatividade e simulações.
Fonte incrível: Biblioteca de ícones.
Google Fonts (Poppins): Tipografia moderna e legível.
🛠️ Como Usar
Clone o Repositório:

festança

Correr
Copiar código
git clone https://github.com/seu-usuario/gerador-suit.git
(Substitua seu-usuario/gerador-suit.gitpelo link real do seu repositório, se você estiver no GitHub.)

Navegue até o Diretório:

festança

Correr
Copiar código
cd gerador-suit
Abra o Arquivo: Abra o arquivo MultipleFiles/spotify (1).htmlem seu navegador web preferido.

Alternativamente, você pode configurar um servidor web local (como Live Server para VS Code) para visualização.

💡 Como Funciona (Simulação)
É importante notar que este gerador não se conecta a uma API real do Spotify para gerar ou verificar códigos. A funcionalidade é baseada em simulações JavaScript:

Geração de Código: Códigos aleatórios de 10 caracteres (letras e números) são gerados.
Validade: A validade dos códigos é simulada com uma probabilidade de 60% de serem "válidos" ( Math.random() < 0.6). Isso significa que nem todos os códigos gerados ou selecionados serão "reais" ou "válidos" no contexto de uma promoção ou sistema real do Spotify.
Webhook: O envio para o Discord é uma simulação de como os dados seriam formatados e enviados, mas uma funcionalidade real dependente de um backend que processasse esses webhooks.
🤝 Contribuição
Contribuições são bem-vindas! Se você tiver ideias para melhorias, novas funcionalidades ou encontrar algum bug, sinta-se à vontade para:

Fazer um fork do repositório.
Crie uma nova branch ( git checkout -b feature/sua-featureou bugfix/seu-bug).
Fazer suas alterações e confirmar ( git commit -m 'feat: adiciona nova funcionalidade').
Envie suas alterações ( git push origin feature/sua-feature).
Abrir um Pull Request.