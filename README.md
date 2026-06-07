# LusoFolio 0.2.0

Aplicacao Windows para acompanhar compras, vendas, inventario e desempenho de um portfolio CS2 no CSFloat.

## Portugues

### Instalar

1. Descarrega `LusoFolio_0.2.0_x64-setup.exe`.
2. Executa o instalador.
3. Se o Windows SmartScreen mostrar "Editor desconhecido", escolhe **Mais informacoes** e **Executar mesmo assim**.
4. Abre o LusoFolio e conclui a configuracao inicial.

### Configuracao inicial

Cada utilizador precisa dos seus proprios dados:

- **API key pessoal do CSFloat**: cria uma no perfil CSFloat, no separador **Developer**.
- **SteamID64**: identificador Steam com 17 algarismos.

A API key permite consultar os dados privados da conta CSFloat. Nunca deve ser partilhada ou publicada.

O SteamID64, isoladamente, pode identificar o perfil e listings publicos, mas nao permite consultar o historico privado de compras e vendas.

### Sincronizacao

- Ao abrir, o LusoFolio procura atividade recente automaticamente.
- Enquanto estiver aberto, atualiza os registos recentes a cada 15 minutos.
- O botao **Atualizar** executa uma atualizacao recente imediata.
- A **Sincronizacao completa**, disponivel nas definicoes, importa novamente todo o historico CSFloat.

### Privacidade

- A base de dados e configuracao ficam guardadas localmente no computador.
- Cada instalacao possui os seus proprios dados.
- O LusoFolio nao inclui servidor proprio nem envia a API key para terceiros. A chave e usada para comunicar diretamente com a API do CSFloat.

### Requisitos

- Windows 10 ou Windows 11, 64 bits.
- Ligacao a Internet.
- Conta CSFloat.

## English

Windows application for tracking purchases, sales, inventory, and the performance of a CS2 portfolio on CSFloat.

### Installation

1. Download `LusoFolio_0.2.0_x64-setup.exe`.
2. Run the installer.
3. If Windows SmartScreen displays "Unknown publisher", select **More info** and **Run anyway**.
4. Open LusoFolio and complete the initial setup.

### Initial setup

Each user needs their own credentials:

- **Personal CSFloat API key**: create one from the **Developer** tab on your CSFloat profile.
- **SteamID64**: your 17-digit Steam identifier.

The API key allows access to private CSFloat account data. Never share or publish it.

The SteamID64 alone may identify a profile and public listings, but it does not provide access to private purchase and sales history.

### Synchronization

- LusoFolio automatically checks for recent activity after opening.
- While running, it checks for recent activity every 15 minutes.
- The **Update** button immediately checks recent activity.
- **Full synchronization**, available in settings, imports the complete CSFloat history again.

### Privacy

- The database and configuration are stored locally on the computer.
- Each installation has its own separate data.
- LusoFolio does not use its own server or send the API key to third parties. The key is used to communicate directly with the CSFloat API.

### Requirements

- 64-bit Windows 10 or Windows 11.
- Internet connection.
- CSFloat account.

## Installer verification

SHA-256:

`79941E6702CCEB99DD89670BC9BD3D53068D367C03D97BD108E4C5D151EFBDB9`

## Contactos

- GitHub: https://github.com/Johnnyzao
- Instagram: https://www.instagram.com/j0hnny._.zao/
