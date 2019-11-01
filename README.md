# Carpool Confirmer (Teste de Seleção)
Aplicativo Android para confirmação de caronas realizadas.

> NOTA: O código desenvolvido nesse teste é de propriedade total do Desenvolvedor.
> Não será utilizado pela Nexa Digital em nenhuma hipótese.

# Especificação do Projeto:

## Tela de Confirmação - Motorista

Como motorista, ao finalizar uma carona, devo confirmar a viagem junto aos meus caroneiros.

Fluxo:
  1. Motorista clica na opção **Motorista**;
  2. O aplicativo gera um QR Code para ser lido pelos caroneiros;
  3. Motorista clica em **Compartilhar localização** para validar a localização.

![Motorista](https://user-images.githubusercontent.com/7469145/57823078-aa5e7080-776c-11e9-96f6-0a99fcf0bd83.png)

### Exibição do QRCODE: 

A imagem deve ser exibida no modo Motorista e deve conter informações do dia e do motorista. 

### Leitura do QRCODE: 

A leitura do QRcode deve aparecer no modo Caroneiro e deve capturar as informações de data e id do motorista. 
Após a leitura, deve aparecer a tela de compartilhamento de localização.

## Tela de Confirmação - Caroneiro

Como caroneiro, devo confirmar que peguei carona com o motorista.

Fluxo:
  1. Caroneiro clica na opção **Caroneiro**;
  2. O aplicativo exibe a câmera do celular;
  3. Caroneiro aproxima o celular do celular do motorista e lê o QR Code;
  4. Caroneiro clica em Compartilhar localização para validar a localização.
  5. O aplicativo confirma e registra a carona.

![caroneiro](https://user-images.githubusercontent.com/7469145/57823680-d7ac1e00-776e-11e9-9978-77a9852d496b.png)


## Requisitos:
  - Aplicativo Android React Native;
  - Backend serveless (AWS ou GCP).
  
## Confirmação de Carona:
  - Motorista deve ter ao menos 1 caroneiro
  - Caroneiro e motorista devem estar no mesmo raio de proximidade ao confirmar localização.
  
  
## Entregáveis
  - Link do repositório no github;
  - README.md com instruções de como rodar seu projeto e pré requisitos de instalação;
  - APK do aplicativo no repositório do github.

