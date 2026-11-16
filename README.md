# Mapa Interativo Auto Atendimento - SBW

Projeto de apoio operacional para lojas Subway, com orientações organizadas em um mapa interativo.

## Estrutura do projeto

```text
/
├── index.html
├── README.md
└── assets/
    ├── fonts/
    │   ├── avant-garde-book.otf
    │   ├── avant-garde-medium.otf
    │   └── avant-garde-bold.otf
    ├── logos/
    │   └── logo-sw-institucional.png
    └── multimidia/
        ├── 02_Selecionar_Balcao.gif
        ├── 01_Botao_Faca_e_Colher.gif
        ├── 01_Selecionar_Dinheiro.gif
        ├── 02_Remover_Dinheiro.gif
        └── capa.jpg
```

## Como executar

1. Baixe ou clone o repositório.
2. Extraia os arquivos, se tiver baixado um ZIP.
3. Mantenha `index.html` e a pasta `assets` no mesmo diretório.
4. Abra `index.html` em um navegador atualizado.

O projeto utiliza HTML, CSS e JavaScript no próprio arquivo `index.html`. Não é necessário instalar dependências para a execução local.

## Conteúdo atualizado — pagamento em dinheiro no Totem

O tópico **“Pedido do TOTEM em DINHEIRO? Onde Achar.”** apresenta:

1. Chamar o cliente pela senha através do Balcão Pendente e acessar o Balcão Pendente.
2. Localizar o pedido correspondente e selecionar **Seguir para recebimento**.
3. Conferir se o troco está correto e alterar o valor lançado.
4. Concluir o recebimento e emitir o cupom fiscal. No KDS, o indicador **NÃO PAGO** desaparece e o pedido fica liberado para produção.

O alerta **“Confira se o troco está correto”** aparece entre as etapas 2 e 3.

## Recursos multimídia

- Demonstração animada da Etapa 2: `02_Selecionar_Balcao.gif` e `01_Botao_Faca_e_Colher.gif`, apresentados lado a lado.
- Imagem de capa do vídeo: `assets/multimidia/capa.jpg`.
- GIFs demonstrativos animados da etapa 3, apresentados lado a lado e alinhados: primeiro `01_Selecionar_Dinheiro.gif` (33 quadros; selecionar DINHEIRO), depois `02_Remover_Dinheiro.gif` (37 quadros; remover a forma de pagamento). Ambos preservam o looping infinito dos arquivos originais. O alerta **ATENÇÃO: Caso o troco esteja INCORRETO** aparece dentro da Etapa 3; a alteração do valor é indicada somente se o troco estiver incorreto.
- As duas animações da etapa 3 mantêm a ordem operacional: primeiro selecionar DINHEIRO e depois remover a forma de pagamento.

Mantenha os caminhos e nomes dos arquivos de mídia ao atualizar o projeto. Se algum arquivo for renomeado ou movido, atualize também a referência correspondente no `index.html`.

## Publicação no GitHub pelo VS Code

1. Abra a pasta do projeto no VS Code.
2. Confira se `index.html`, `README.md` e `assets/` estão presentes.
3. Na aba **Source Control / Controle do Código-Fonte**, revise os arquivos modificados.
4. Faça o commit com uma mensagem descritiva, por exemplo: `Atualiza orientação de pagamento em dinheiro e adiciona vídeo`.
5. Use **Push** ou **Sync Changes** para enviar as alterações ao GitHub.

## Observações

- Não remova a pasta `assets`: ela contém a identidade visual, as fontes e os arquivos multimídia utilizados pela página.
- Teste o projeto em computador e celular após cada atualização.
- O GIF da etapa 3 ainda será adicionado em uma atualização futura.


## Mapa expansível

- Clique no núcleo central **MAPA DE AJUDA** para recolher ou expandir todos os menus.
- Clique em uma categoria da legenda para destacar e expandir os menus daquele sistema.
- Clique novamente na categoria selecionada para voltar a exibir todos os menus.
- Ao abrir uma orientação, os menus mantêm o estado de expansão selecionado.

## Vídeo completo — pagamento em dinheiro

Ao final da Etapa 4 do tópico **Pedido do TOTEM em DINHEIRO? Onde Achar.**, o projeto incorpora o vídeo completo hospedado no YouTube:

- https://youtu.be/ZOQCg0hIqFY

O vídeo é carregado por incorporação responsiva (iframe), portanto o arquivo de vídeo não é armazenado no repositório GitHub. Para trocar o vídeo, atualize o ID do YouTube no `src` do iframe em `index.html`.
