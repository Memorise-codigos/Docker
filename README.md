[⬅Voltar](https://memorise-codigos.github.io/)
# Introdução ao Docker
O Docker é uma plataforma que permite a criação, implantação e execução de aplicativos em contêineres. Os contêineres são ambientes isolados e leves que executam aplicativos com suas próprias bibliotecas e dependências, tornando-os portáteis e escaláveis.

## Conceitos Básicos
- Imagem: Um modelo somente-leitura usado para criar contêineres. As imagens contêm sistemas de arquivos com todas as dependências necessárias para executar um aplicativo.\

- Contêiner: Uma instância executável de uma imagem. É possível criar, iniciar, parar, mover ou excluir contêineres.

- Dockerfile: Um arquivo de texto usado para definir uma imagem. Ele contém todas as instruções necessárias para criar uma imagem.

- Registro: Um local onde as imagens do Docker são armazenadas. O Docker Hub é o registro público padrão, mas você também pode usar registros privados.

# Instalação do Docker
O Docker pode ser instalado em várias plataformas, como Linux, Windows e macOS. [Visite o site oficial do Docker](https://www.docker.com/get-started) para obter instruções detalhadas sobre a instalação para o seu sistema operacional específico.

# Comandos Essenciais do Docker
### Gerenciamento de Imagens
- `docker image ls`

Lista todas as imagens disponíveis no sistema.

- `docker image pull <nome_da_imagem>:<tag>`

Baixa uma imagem do registro.

- `docker image rm <nome_da_imagem>`

Remove uma imagem local.

- `docker image prune`

Remove todas as imagens não utilizadas.
