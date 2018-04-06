# Como popular os dados do ScrumDay 2018
Para popular os dados do site, procurar sempre por arquivos `.yml`, pois são eles que são responsáveis por conter os dados, e estão localizados na pasta `_data`, com exceção do arquivo `_config.yml`.

Arquivos:
  - agenda.yml - Possui o horário de início/fim (`startTime`/`endTime`), além da sessão correspondente (`sessionIds`). Para melhor apresentação, é viável colocar até 5 sessões.
  - sessions.yml - Possui o identificador da sessão (`id`) e o título da sessão (`title`).
  - speakers.yml - Arquivo que possui os dados de quem vai ministrar a palestra/workshop, possuindo o id (`id`) que é usado em sessions, o nome (`name`) e a imagem (`thumbnailUrl`).

Observações: 
* Os arquivos que possuem os dados, eles podem ser configurados com o que desejar (colocar um novo detalhe para um speaker, por exemplo).
* O arquivo `_config.yml` é responsável por possuir variáveis globais ao projeto (como por exemplo título do site, a url do site, e afins). Por tanto, é necessário cuidado ao mexer no projeto.
* As imagens, devem ser adicionadas ao diretório `\img`.

___

# Como executar em `localhost`
- Necessário instalar: `Ruby`, `Node` (a partir da versão 6 é ok) e o `Jekyll` (instalado com o ruby);
- Após instalado, é necessário pegar o projeto do github (`https://github.com/barbaromatrix/scrum-day-short.git`). Para que seja clonado, é necessário mandar um email/chamar no slack através do canal matheus.galdino@concrete.com.br / cs-matheus-galdino, pois o repositório está definido como privado.
- Após o download, acessar o projeto e no local do projeto, rodar o comando `jekyll serve`. :)

___

# Como subir no github pages?
- Necessário possuir a branch `gh-pages` (Que atuará como master para o GHP)
- Criar um repositório no github
- Acessar a área de configuração do projeto e procurar por `Github Pages`
- Definir a branch (realizado de maneira automática com a presença da branch gh-pages)


   [Repositório]: <https://github.com/barbaromatrix/scrum-day-short.git>
