# VodKine

Projeto experimental para estudar e organizar a execução de jogos e aplicativos Windows em Linux e macOS.

## Objetivo

O VodKine pretende oferecer uma interface para configurar ambientes de compatibilidade, instalar launchers de fontes oficiais, registrar diagnósticos e comparar configurações por jogo. O projeto começa pela documentação; ainda não há código-fonte nem suporte de execução garantido.

## Escopo inicial

- Separar os fluxos e as configurações de Linux e macOS, validando cada plataforma no próprio sistema.
- Investigar runtimes, componentes gráficos e dependências adequados a cada plataforma, sem presumir que sejam intercambiáveis.
- Organizar integrações planejadas com Steam, Epic Games e Minecraft Launcher, respeitando os termos e os métodos oficiais de cada fornecedor.
- Registrar ambiente, configurações e resultados para que os testes possam ser repetidos e comparados.
- Comunicar claramente o que foi testado, o que funciona e quais limitações permanecem.

## Princípios

- Não modificar arquivos de jogos ou launchers sem necessidade e autorização explícita.
- Não contornar anti-cheat, mecanismos de proteção ou verificações de plataforma. Quando houver bloqueio do fornecedor, documentar a limitação e depender de suporte oficial.
- Não prometer compatibilidade universal: o resultado depende do jogo, do runtime, dos drivers, do hardware e da versão do sistema.

## Plataformas

### Linux

Investigar runtimes compatíveis com Wine/Proton e as APIs gráficas disponíveis na distribuição e no hardware testados.

### macOS

Investigar os caminhos de compatibilidade próprios do macOS e as opções gráficas disponíveis, incluindo Metal quando aplicável. Instalação, configuração e validação serão documentadas separadamente das de Linux.

A arquitetura final e a divisão entre componentes comuns e específicos de cada plataforma ainda serão definidas pelos mantenedores.

## Estado do projeto

Planejamento inicial. Este repositório contém apenas este README por enquanto. Implementações, instaladores, drivers e testes serão adicionados após a definição do escopo e da arquitetura.
