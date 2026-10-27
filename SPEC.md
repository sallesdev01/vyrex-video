# VYREX — filme de apresentação

GOAL:    quem assiste entende que a VYREX faz sites que abrem rápido e viram venda, e lembra do V lima.
OUTPUT:  HyperFrames, 1920 x 1080, 30 fps.
TIME:    24 s x 30 = 720 frames. Sem música nesta versão (sem fonte de música disponível).
REFS:    dois reels de riki.bosso (Shopify e Amazon): fundo escuro, brilho na cor da marca, celular subindo
         com a interface real, cards flutuando ao redor, mundo 3D com rotas de luz, objeto 3D da marca,
         frase com sublinhado da marca, logo no fim. Seguimos essa estrutura.
LOOK:    chão #0A0A0A; tinta #F5F5F0; acento único lima #C6FF1A (lâmina direita, rastros, um trecho de texto
         por plano, botão final). Brilho lima radial só atrás do objeto principal, opacidade máx. 22%.
         Display Unbounded 700/800, -3% de tracking; corpo Inter; Unbounded do próprio site.
         3D: símbolo extrudado (profundidade 0,5, bisel 0,06), lâmina esquerda metal off-white
         (metalness 0.85, roughness 0.28), lâmina direita lima (emissive 0.25 a 1.0).
OBJECTS: o símbolo V de duas lâminas (geometria exata do logo); o celular com moldura escura, ilha e
         tela com o print real do site em 430 px; cards reais do site; conversa com a mensagem real que o
         botão do site envia ("Olá! Tenho interesse no plano Landing Page da VYREX.").
MOTION:  chegadas expo.out / power4.out; câmera power2.inOut; saídas e mergulhos power3.in / power4.in.
         Títulos por palavra: blur 6 px -> 0 em 4 frames, 2-3 frames entre palavras.
SHOTS:   0-78    abertura: lâminas 3D chegam de lados opostos e se encontram no vértice; VYREX entra à
                 direita; a câmera mergulha no vértice e um íris lima fecha o quadro.
         78-300  celular sobe no brilho lima com o site real; cards reais se abrem em profundidade; a tela
                 rola até o preço; zoom no botão; o cursor clica; a tela vira conversa a partir do clique;
                 a mensagem é enviada e lida; mergulho para dentro da tela.
         300-450 funil 3D: rastros de luz atravessam o chão e convergem no vértice do V, que acende.
                 Legenda: "Todo clique converge para a venda".
         450-588 frase: "Nós não fazemos sites" -> "Construímos máquinas de conversão" com sublinhado
                 em forma de lâmina.
         588-720 fim: V 3D gira de frente, VYREX entra, "Sites a partir de R$ 1.499" e botão vyrex.com.br,
                 seguram 2,5 s.
BANNED:  logo no canto; tudo entrando com fade e subida; anéis de clique; partículas soltas; interface de
         produto inclinada em 3D; números inventados; estatísticas que o site não afirma.
QA:      frames 0, 40, 120, 190, 240, 280, 330, 420, 500, 560, 650, 715.
