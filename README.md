# ProjectTemplate

Esse projeto serve como base para organização de projetos pessoais.
Nele se encontram múltiplas ocorrências comuns de diretórios e subdiretórios nos ambientes de desenvolvimento do mercado.
A intenção desse projeto é prover um template genérico que sirva de embasamento ao usuário em novos projetos de código (trabalhos de faculdade, projetos pessoais, ...)
Para caso específico do usuário, leia as descrições abaixo e escolha quais diretórios manter.

## Explicações das Folders

| Nome da Folder | Explicação de Uso |
|----------|----------|
| bin 	   | Geralmente reservado para guardar os outputs executáveis dos processos de build do projeto e utilitários executáveis adjacentes ao executável principal do projeto. |
| build    | Contém os arquivos intermediários e metadados que são gerados durante o processo de build. Costuma ser limpo entre builds consecutivos.        |
| config   | Reúne arquivos de configuração de uma aplicação nas extensões .xml, .json, .DAT, .txt, entre outros que são consumidos pela aplicação para pré-definir determinados padrões da mesma durante a inicialização e execução. |
| deploy   | Local para concentração de scripts relacionados ao processo de construção e lançamento da solução, pode conter scripts .bat, .sh, e conter folders/arquivos de saída construídos e prontos para execução. |
| dll      | Local de concentração dos arquivos .dll utilizados pela aplicação, caso utilize alguma.         |
| doc      | Espaço reservado para PDFs, .docs, .txts, .ppts e tudo que for pertinente à documentação do seu projeto.        |
| examples | Costuma conter sub-folders dentro com alguns casos de utilização do programa principal. Pode conter exemplos gráficos em caso de presença de GUI.         |
| include  | Costuma conter arquivos fonte essenciais para a compilação e o runtime da aplicação.        |
| lib      | Costuma centralizar arquivos de biblioteca utilizados em processos de compilação/linkedição/execução, tais como extensões .lib, .jar, .dll e similares. |
| nm       | Pasta que contém códigos fontes de externos ou da própria empresa que são utilizados para integração com o código da própria empresa por meio de métodos nativos (native methods). Costuma ser utilizado quando duas empresas colaboram uma com a outra por meio de suas ferramentas que são construídas de maneiras diferentes. Essas empresas compartilham algumas chamadas de determinadas funções de seus protótipos por meio de códigos dessa pasta nm, para que não tenham que compartilhar todo o seu código fonte. |
| obj      | Pasta temporária que costuma segurar arquivos intermediários fruto de compilação/build/runtime.         |
| res      | Pasta destinada ao armazenamento de recursos gráficos, tal como .PNGs, .JPEGs, .MP4 e quaisquer outros recursos carregados/utilizados pelos códigos fontes da pasta src durante processos de compilação/execução. |
| src      | Pasta onde se reúne a estrutura de pastas e códigos fontes do projeto. É onde estarão os fontes. |
| target   | Se algumas ferramenta de build do projeto jogam os arquivos intermediários e finais para pastas build e bin, outras ferramentas incluem os arquivos intermediários e finais de build para a pasta target. |
| test     | Pasta que geralmente reúne arquivos de configuração, executáveis buildados para teste e arquivos similares pertinentes aos testes antes do lançamento da versão (deploy). |
| util     | Local geralmente reservado para ferramentas executáveis, documentos e qualquer outro tipo de arquivo que venha a auxiliar em configurações de máquina, usuário, ou até no desenvolvimento/deploy da aplicação.         |
