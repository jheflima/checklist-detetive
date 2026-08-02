CHECKLIST DETETIVE — IMAGENS EXTERNAS

1. Mantenha o arquivo index.html ao lado da pasta "imagens".
2. Coloque as imagens dos personagens dentro da pasta "imagens".
3. Use exatamente estes nomes:

dancarina.jpg
medica.jpg
advogado.jpg
florista.jpg
mordomo.jpg
sargento.jpg
coveiro.jpg
chef-de-cozinha.jpg
musicista.jpg
camareira.jpg
catador.jpg
banqueira.jpg

Formatos recomendados:
- JPG ou PNG
- retrato vertical
- proporção aproximada de 4:5
- resolução sugerida: 600 × 750 px ou maior

Caso prefira PNG, altere ".jpg" para ".png" no bloco "const portraits"
perto do início do JavaScript, dentro do arquivo index.html.

IMPORTANTE:
Ao publicar, envie o index.html e a pasta imagens juntos, preservando essa estrutura.


MODOS DE JOGO

VERSÃO EXPANDIDA
- 8 suspeitos
- 8 armas
- 11 locais

VERSÃO COMPLETA
- 12 suspeitos
- 14 armas
- 12 locais
- Inclui Musicista, Camareira, Catador, Banqueira e Fim da Rua

VERSÃO JOGO RÁPIDO
- Remove Coveiro e Advogado
- Remove Praça Central
- Solicita a escolha de duas armas para retirar
- Resultado: 6 suspeitos, 6 armas e 10 locais
- Recomendado para até 6 jogadores


IMAGENS NA TELA DE CRIME SOLUCIONADO

Além dos retratos dos personagens, o site agora procura imagens de armas e locais:

imagens/armas/
imagens/locais/

Os nomes esperados estão definidos nos blocos:
const weaponImages
const placeImages

dentro do index.html. Você pode trocar qualquer caminho ou extensão.

COMPARTILHAMENTO NO INSTAGRAM

O botão gera uma imagem vertical 1080 × 1920 px.
Em celulares compatíveis, ele abre o menu de compartilhamento do sistema,
onde o Instagram pode ser selecionado. Navegadores não podem abrir diretamente
uma postagem específica do Instagram sem a escolha do usuário.

Quando o compartilhamento de arquivos não é suportado, a imagem é salva no
aparelho para ser publicada manualmente.


TELA FINAL V7

A tela de Crime Solucionado agora usa visual de ficha policial:
- foto principal do culpado;
- profissão e status;
- imagem da arma;
- imagem do local;
- vencedor;
- tempo total;
- conquista automática conforme o tempo da partida.

Conquistas:
- menos de 15 minutos: Detetive lendário;
- menos de 30 minutos: Investigador de elite;
- demais tempos: Caso solucionado.

A imagem compartilhada continua sendo gerada em 1080 × 1920 px.


CORREÇÕES DA V8

- Todas as opções da solução são recriadas conforme o modo escolhido.
- Todos os modos exigem o nome de quem solucionou.
- O vencedor também seleciona o personagem com que jogou.
- A imagem final mostra o nome do vencedor e seu personagem.
- A vítima foi identificada como Carlos Fortuna, também chamado de Sr. Fortuna.


CORREÇÃO DA V9

- O site não pergunta mais qual personagem o vencedor usou.
- O personagem já escolhido no início é usado automaticamente.
- A foto do culpado ganhou visual mais claro de arquivo policial, com linhas de altura.


CORREÇÃO DA V10 — NOMES DOS MODOS

VERSÃO EXPANDIDA DO JHEF
- 12 suspeitos
- 14 armas
- 12 locais
- Inclui os 4 suspeitos, 6 armas e Fim da Rua

VERSÃO COMPLETA
- Versão original do jogo
- 8 suspeitos
- 8 armas
- 11 locais

VERSÃO JOGO RÁPIDO
- Opção oficial reduzida
- 6 suspeitos
- 6 armas
- 10 locais


AJUSTES DA V11

- Tela de caso encerrado reorganizada para celulares estreitos.
- Foto e dados do culpado não ficam mais cortados.
- Botões finais ficaram menores.
- Arma e local usam object-fit: contain, sem cortar as imagens.
- A arte de Instagram também encaixa arma e local inteiros, com fundo claro.
- A tela final sempre abre no topo.
