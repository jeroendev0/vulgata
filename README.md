# VULGATA 

## Instalação pelo gestor de ficheiros

### 1. Habilitar fontes desconhecidas

1. Abra o Kodi e entre em **Configurações → Sistema → Add-ons**.
2. Ative **Fontes desconhecidas** e confirme.

### 2. Adicionar a fonte

1. Vá em **Configurações → Gestor de ficheiros** — pode aparecer como **Gestor de arquivos**.
2. Selecione **Adicionar fonte → Nenhum**.
3. Digite o endereço:

   ```text
   https://jeroendev0.github.io/vulgata/
   ```

4. Dê o nome **Vulgata** à fonte e confirme em **OK**.

### 3. Instalar o repositório

1. Volte à tela inicial e abra **Add-ons**.
2. Selecione o **ícone da caixa → Instalar a partir de um arquivo ZIP**.
3. Abra **Vulgata → repository.vulgata**.
4. Selecione o arquivo ZIP do repositório e aguarde a confirmação da instalação.

### 4. Instalar o addon

1. Abra **Instalar via repositório → VULGATA Repo**.
2. Entre em **Add-ons de vídeo → VULGATA → Instalar**.
3. Confirme as dependências solicitadas e aguarde.
4. Abra o addon em **Add-ons → Add-ons de vídeo → VULGATA**.

## Configuração do player

Para uma reprodução mais estável, recomendamos instalar e habilitar o **InputStream FFmpeg Direct**.

Nas **Configurações** do Vulgata, escolha o player desejado. Se o FFmpeg Direct estiver indisponível, o addon utilizará o player padrão do Kodi.

## Vídeos dando erro? Tente o 1.1.1.1 com WARP

Se os vídeos apresentarem erros de conexão, você pode experimentar o **Cloudflare WARP** no mesmo dispositivo em que usa o Kodi.

1. Instale o aplicativo oficial seguindo as instruções para [Windows](https://developers.cloudflare.com/warp-client/get-started/windows/) ou [Android](https://developers.cloudflare.com/warp-client/get-started/android/).
2. Abra o aplicativo e conclua a configuração inicial.
3. Selecione o modo **WARP** e ative a conexão.
4. No Android, autorize a criação da conexão VPN quando solicitado.
5. Aguarde aparecer **Conectado**, reabra o Kodi e tente reproduzir novamente.

> Use o modo **WARP** para esse teste. O modo **1.1.1.1 somente DNS** altera apenas o tratamento das consultas DNS. Veja a [explicação oficial dos modos](https://developers.cloudflare.com/warp-client/get-started/windows/#warp-modes).
>
> O WARP pode ajudar em problemas de acesso pela rede, mas não corrige links removidos ou servidores indisponíveis. Se a conexão piorar, desative-o e compare.

## Atualizações

Mantenha as **atualizações automáticas** habilitadas para o Vulgata. Você também pode usar **Verificar atualização**, no menu inicial do addon.

## Comunidade

Entre no Telegram para receber novidades, tirar dúvidas e enviar sugestões:

[**Entrar na comunidade VULGATA**](https://t.me/+uy5ZRY7Mqd1iZTA5)
