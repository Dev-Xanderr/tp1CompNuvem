# Sistema de Informação para Serviço de Ementas de Apoio ao Bar

Este projeto é um sistema de informação que fornece suporte funcional e de gestão para o serviço de Ementas de apoio ao bar. Ele consiste em duas partes principais: Front-end e Back-end, cada uma executada em um contêiner Docker separado.

## Instruções de Instalação e Uso

### Pré-requisitos
- Docker instalado na sua máquina.

### Instalação
1. Clone este repositório para sua máquina local.
2. Certifique-se de estar no diretório raiz do projeto.

### Imagem Docker
Além dos arquivos de código-fonte, uma imagem Docker pré-construída está disponível no arquivo ZIP `computaoemnuvem-cpia-web.zip`. Siga as instruções abaixo para carregar a imagem Docker a partir do arquivo ZIP.

...

### Funcionalidades

O sistema oferece as seguintes funcionalidades:

1. **Gerenciamento de Pratos, Usuários e Alergênicos:**
   - Os usuários podem criar, editar e excluir pratos, usuários e alergênicos conforme necessário.

2. **Edição da Ementa Semanal:**
   - Os usuários têm a capacidade de editar a ementa semanal, adicionando, removendo ou modificando os pratos disponíveis.

3. **Visualização da Ementa Semanal:**
   - Para visualizar a ementa semanal, os usuários devem criar uma conta com um nível de acesso inferior ao do administrador. Isso permite que eles vejam a ementa semanal, mas não tenham permissão para editar ou fazer alterações.

### Utilização

Para usar o sistema, siga estas etapas:

1. Acesse o Front-end através do navegador usando o endereço [http://localhost:8080](http://localhost:8080).
2. Faça login com suas credenciais ou crie uma nova conta, se necessário.
3. Depois de fazer login, você terá acesso às funcionalidades mencionadas acima, dependendo do seu nível de acesso.

## Contribuições
Contribuições são bem-vindas! Por favor, envie um pull request para revisão.

## Autores
- [Alexandre Martins]

## Licença
Este projeto está licenciado sob a [Licença XYZ]. Consulte o arquivo LICENSE para obter mais detalhes.
