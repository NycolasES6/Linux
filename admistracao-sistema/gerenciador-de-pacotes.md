# Gerenciador de pacotes

Seja trabalhndo como admnistrador do sistema, mantendo nossas próprias máquinas em casa ou construind/atualizando/mantendo nossa distribuição de teste de penetração preferida, é crucial ter um conhecimento firme dos, gerenciadores de pacotes Linux disponíveis e das várias maneiras de utlizálos para instalar, atualizar ou remover pacotes. Pacotes são arquivos que contêm bnários de software, arquivos de configuração, informações sobre dependências e acompanham atualizações e upgrades. Os recursos que a maioria dos sistemas de gerenciamento de pacotes oferecem são :

 - Download de pacote.
 - Resolução de dependência.
 - Um formato de pacote binário padrão.
 - Locais comuns de instalação e configuração.
 - Configuração e funcionalidade adicionais relacionadas ao sistema.
 - Controle de qualidade.

Podemos usar muitos sistemas de gerenciamento de pacotes diferentes que cobrem diferentes de arquivos como ".deb", ".rpm" e outros. O requisito de gerenciamento de pacotes é que o software a ser instalado esteja disponível como um pacote correspondente. Normalmente, isso é criado, oferecido e mantido centralmente nas distribuições linux. Desta forma, o software é integrado diretamente no sistema, e seus diversos diretórios são distribuídos por todo o sistema. O siftware de gerenciamento de pacotes recupera as alterações necessárias para a instalação do sistema do próprio pacote e, em seguida, implementa essas alterações para instalar o pacote com êxito. Se o software de gerenciamento de pacotes reconhecer que pacotes adicionais são necessários para o funcionamento adequado do pacote que ainda  não foi instalado, uma dependência será incluída e avisará o administrador ou tentará recarregar o software ausente de um repositório, por exemplo, e instalar isso com antecedência.

Se um software instalado tiver sido excluído, o sistema de gerenciamento de pacotes retoma as informações do pacote, modifica-as com base em sua configuração e exclui os arquivos. Existem diferentes programas de gerenciamento de pacotes que podemos usar para isso. Aqui está uma lista de exemplos de tais programas:

 - `dpkg` - O dpkg é uma ferramenta para instalar, construir, remover e gerenciar pacotes Debian. O front-end principal e mais fácil de usar é o dpkg aptitude.
 - `apt` - Apt fornece uma interface de linha de comando de alto nível para o sistema de gerenciamento de pacotes.
 - `snap` - Instale, configure, atualize e remova pacotes snap. Os Snaps permitem a distribuilçao segura dos aplicativos e utilitário mais recentes para a nuvem, servidores, desktops e IoT.
 - `gem` - Gem é o front-end do RubyGems, o gerenciador de pacotes padrão do Ruby.
 - `pip` - Pip é um instalador de pacotes Python recomendado para instalar pacotes Python que não estão disponíveis no arquivo Debian. Ele pode funcionar com repositórios de controle de versão (atualmente apenas repositórios Git, Mercurial e Bazaar), registra extensivamente a saída e evita instalações parciais baixando todos os requisitos antes de iniciar a instalação.
 - `git` - Git é um sistema de controle de revisão distribuído, rápido e escalável, com um conjunto de comandos excepcionailmente rico que fornece operações de alto nível e acesso total aos componentes internos.

É altamente recomendável configurar nossa máquina virtual (VM) localmente para experimentá-la. Vamos experimentar um pouco em nossa VM local e estendê-la com alguns pacotes adicionais. Primeiro, vamos instalar git usando apt.




