# LusoFolio 0.2.0

LusoFolio é uma aplicação Windows para acompanhar compras, vendas, inventário e desempenho de um portefólio CS2 no CSFloat.

O repositório disponibiliza apenas o instalador público da aplicação e este README. O código-fonte e os dados locais dos utilizadores não fazem parte desta publicação.

## Instalação

1. Descarrega `LusoFolio_0.2.0_x64-setup.exe`.
2. Executa o instalador.
3. Se o Windows SmartScreen apresentar o aviso **Editor desconhecido**, selecciona **Mais informações** e depois **Executar mesmo assim**.
4. Abre o LusoFolio e conclui a configuração inicial.

## Configuração inicial

Cada utilizador deve configurar os seus próprios dados:

- **API key pessoal do CSFloat**: pode ser criada no perfil CSFloat, no separador **Developer**.
- **SteamID64**: identificador Steam composto por 17 algarismos.

A API key permite consultar informação privada da conta CSFloat. Não deve ser partilhada, publicada ou enviada a terceiros.

O SteamID64, por si só, pode identificar o perfil Steam e listings públicos, mas não permite aceder ao histórico privado de compras e vendas.

## Sincronização

- Ao iniciar, o LusoFolio procura actividade recente automaticamente.
- Enquanto estiver aberto, actualiza os dados recentes a cada 15 minutos.
- O botão **Actualizar** força uma actualização imediata.
- A opção **Sincronização completa**, disponível nas definições, volta a importar todo o histórico CSFloat.

## Privacidade

- A base de dados e a configuração ficam guardadas localmente no computador.
- Cada instalação mantém os seus próprios dados.
- O LusoFolio não tem servidor próprio e não envia a API key para terceiros.
- A API key é usada apenas para comunicar directamente com a API do CSFloat.

## Requisitos

- Windows 10 ou Windows 11, 64 bits.
- Ligação à Internet.
- Conta CSFloat.

## Verificação do instalador

SHA-256:

`79941E6702CCEB99DD89670BC9BD3D53068D367C03D97BD108E4C5D151EFBDB9`

## English

LusoFolio is a Windows application for tracking CS2 purchases, sales, inventory and portfolio performance on CSFloat.

Download `LusoFolio_0.2.0_x64-setup.exe`, run the installer and complete the initial setup with your own CSFloat API key and SteamID64.

The application stores its database and configuration locally. It does not operate its own server and does not send your API key to third parties.

## Contactos

- GitHub: https://github.com/Johnnyzao
- Instagram: https://www.instagram.com/j0hnny._.zao/
