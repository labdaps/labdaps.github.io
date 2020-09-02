# LabPageFiles
Arquivos Jekyll para o Site do LABDAPS

# Como Instalar o Jekyll
- Instale o Ruby seguindo o site: https://jekyllrb.com/docs/installation/windows/
- Instale o Jekyll no prompt de comando (Iniciar -> cmd) digitando "gem install jekyll bundler"
- No prompt de comando digite "bundle install"

# Alterar Conteúdo do site
- Clonar os Repositórios LabPageFiles e labdaps.github.io
- Alterar o conteúdo nas pastas images, _pages e _data
  - images: Todas as imagens e fotos do site
  - _pages: Páginas estáticas do site
  - _data: conteúdo dinâmico em formato de banco de dados
- Rodar o arquivo jekylltest.bat alterando o caminho para representar o endereço local. Este arquivo irá criar uma versão de testes em um servidor local que pode ser acessada via no endereço http://localhost:4000/
- Quando todas as alterações estiverem prontas para ser implementadas, rodar o arquivo jekyllimplement.bat alterando o caminho para representar o endereço local. Este bat irá rodar o Jekyll e salvar a página em html no Clone local da pasta labdaps.github.io
- Fazer commit e push dos arquivos da pasta **labdaps.github.io** para o github

# Upload do conteúdo
O Upload de conteúdo para o site do Labdaps só pode ser feito por um computador na rede da FSP. Para isso utilizaremos um dos computadores físicos do LABDAPS.
- Utilizando o aplicativo AnyDesk (https://anydesk.com/pt/downloads/windows), acesse o computador remoto 615 170 746. A senha poderá ser obtida com Bruno, André ou Alexandre.
- Abra o aplicativo github desktop e faça um pull do repositório **labdaps.github.io**.
- Abra o aplicativo FileZilla
- Clique em na seta ao lado de "Conexão Rápida" e em seguida em sftp://labdaps@fsp.usp.br
- Copie o conteúdo de "C:\Users\T-Gamer\Documents\Site Labdaps\labdaps.github.io\" para a pasta do SFTP "/home/labdaps/public_html"
- O site está no ar!
