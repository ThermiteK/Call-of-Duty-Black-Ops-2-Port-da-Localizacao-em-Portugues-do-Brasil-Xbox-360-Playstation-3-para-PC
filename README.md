<p align="center">
  <img src="assets/banner.jpg" alt="Call of Duty: Black Ops II — Port da Localização Oficial em Português do Brasil (PC)">
</p>

<p align="center">
  <img src="assets/banner.png" alt="Call of Duty: Black Ops II — Localização Oficial em Português do Brasil">
</p>

# Call of Duty: Black Ops II — Port da Localização Oficial em Português do Brasil (PC)

...

## Sobre o meu projeto

Este projeto tem como objetivo preservar e disponibilizar para a versão de PC a localização oficial em Português do Brasil de **Call of Duty: Black Ops II**, originalmente lançada para Xbox 360 e PlayStation 3 em 2012.

O foco deste trabalho é a preservação. Todo o conteúdo localizado foi portado diretamente das versões oficiais dos consoles, mantendo fidelidade ao material original sempre que possível. Sempre que houve necessidade de adaptação para a versão de PC, as alterações foram limitadas ao estritamente necessário para garantir compatibilidade e uma experiência consistente com a plataforma.

---

# Requisitos

* Uma cópia legítima de **Call of Duty: Black Ops II** no Steam.
* Este projeto **não foi testado** na versão distribuída pela Microsoft Store.

---

# Instalação

## Multijogador e Modo Zumbis

O Multiplayer e o Modo Zumbis utilizam o **Plutonium**.

Para utilizar esta localização é necessário:

1. Possuir uma cópia legítima do jogo no Steam.
2. Criar uma conta no fórum do Plutonium. (https://plutonium.pw/)
3. Instalar e executar o jogo através do Launcher do Plutonium.
4. Copiar as pastas fornecidas deste projeto para:

```
Usuário\AppData\Local
```

As estruturas de diretórios já estão organizadas corretamente. Basta copiar as pastas para o local indicado.

Nenhum arquivo original do jogo precisa ser substituído para utilizar a localização nesses modos.

---

## Campanha

O modo Campanha utiliza o **T6SP-Mod**, desenvolvido por Rattpak.

Diferentemente do Multijogador e do Modo Zumbis, a Campanha utiliza arquivos compilados. Por esse motivo, recomenda-se manter uma instalação separada exclusivamente para este modo.

A instalação consiste em copiar:

```
CoD_T6sp_localizacao_T6sp-mod\T6SP-Mod
```

para a pasta raiz da instalação dedicada da Campanha.

Devem ser copiadas as pastas:

* `spmod`
* `zone`

Dentro da pasta `launcher` contém o executável T6SP-Mod.exe junto com o arquivo t6sp-mod.dll ambos devem ser copiados para a pasta raiz da instalação dedicada da Campanha.

* `launcher`

Após isso, execute o jogo através do launcher incluído no projeto.

---

## Por que são necessárias duas instalações?

O Multiplayer/Zumbis e a Campanha utilizam métodos diferentes para carregar modificações.

O Plutonium trabalha com arquivos carregados dinamicamente e não requer a substituição dos arquivos originais do jogo.

Já o modo Campanha utiliza arquivos compilados que substituem parte do conteúdo original.

Como ambos os launchers utilizam métodos diferentes de carregamento, manter duas instalações separadas evita conflitos e garante o funcionamento correto de todos os modos de jogo.

---

## Observação sobre a aba Solo do modo Zumbis

Para oferecer uma experiência totalmente localizada no modo Zumbis, este projeto inclui um mod complementar chamado bp_solo_patch_loc.

Por uma particularidade do funcionamento do Plutonium, a tela Solo obtém parte de seus textos a partir de uma fonte diferente daquela utilizada pelo restante da interface. Como consequência, algumas descrições de mapas e modos de jogo permanecem em inglês mesmo com a localização instalada.

O bp_solo_patch_loc corrige esse comportamento, fazendo com que a tela utilize os textos já presentes na localização do jogo e mantenha a interface totalmente em Português do Brasil.

A utilização deste mod é opcional. O jogo funciona normalmente sem ele e nenhuma funcionalidade é afetada. Ele é recomendado apenas para quem deseja que a interface do modo Solo permaneça completamente localizada.

Como o Plutonium exige que esse tipo de mod seja carregado manualmente, será necessário selecioná-lo sempre que desejar utilizar a versão localizada da tela Solo.

---


# O que este projeto inclui

## Port da localização oficial

Todo o conteúdo oficial localizado para Xbox 360 e PlayStation 3 foi portado para a versão de PC buscando preservar integralmente o trabalho realizado originalmente pela Treyarch e seus parceiros de localização.

O objetivo nunca foi reinterpretar ou recriar a tradução, mas sim disponibilizar oficialmente esse conteúdo em uma plataforma que nunca recebeu suporte ao Português do Brasil.

---

## Adaptações para a versão de PC

Alguns elementos precisaram ser adaptados para respeitar as diferenças entre as versões de console e PC.

Isso inclui principalmente referências aos controles, botões e comandos específicos dos consoles, que foram atualizados para refletir corretamente os dispositivos de entrada utilizados na versão para computador, preservando a intenção original das instruções exibidas ao jogador.

---

## Correções de texto

Durante o desenvolvimento também foram corrigidos pequenos erros presentes na localização oficial original, incluindo problemas de digitação e inconsistências textuais.

Todas as correções foram realizadas procurando manter o estilo, a terminologia e a identidade da tradução lançada oficialmente.

---

## Legendas da Campanha

Um dos maiores diferenciais deste projeto é a inclusão de legendas completas em Português do Brasil para toda a Campanha.

Originalmente, **Call of Duty: Black Ops II** possui legendas apenas em inglês. Embora diversos idiomas tenham recebido localização oficial da interface, objetivos e demais elementos do jogo, as falas dos personagens durante a jogabilidade e nas cenas permaneciam legendadas exclusivamente em inglês.

Neste projeto, todas essas legendas foram produzidas utilizando como referência a dublagem oficial em Português do Brasil, tornando a experiência totalmente localizada também durante as cenas pré-renderizadas e em tempo real da campanha.

---

## Texturas localizadas

Além dos textos, diversas texturas do jogo contêm informações incorporadas diretamente às imagens.

Esses elementos também foram portados para a versão de PC, preservando a apresentação oficial existente nos consoles.

Isso inclui conteúdos presentes na Campanha e em diferentes modos do Multiplayer, garantindo uma localização consistente em toda a interface do jogo.

---

# Sobre os Launchers

Este projeto utiliza dois launchers diferentes:

* **Plutonium**, responsável pelo Multiplayer e pelo Modo Zumbis;
* **T6SP-Mod**, responsável pela Campanha.

Essa divisão existe porque o Plutonium não oferece suporte ao modo Campanha.

Além disso, ambos os projetos fornecem uma plataforma mais adequada para modificações, permitindo a utilização desta localização de forma segura e compatível, ao mesmo tempo em que evitam limitações presentes no launcher original do Steam.

Outro benefício importante é que essas soluções também mitigam vulnerabilidades conhecidas existentes na versão original do jogo, proporcionando uma experiência mais segura.

---

# Agradecimentos

Este projeto só foi possível graças ao trabalho da comunidade.

Agradecimentos especiais a:

### Jan Laupetin (https://github.com/Laupetin)

Pela criação do O.A.T. (Open Asset Tool), ferramenta fundamental para a compilação dos arquivos utilizados neste projeto.

### Rattpak (https://github.com/Rattpak)

Pelo desenvolvimento do **T6SP-Mod**, tornando possível a execução das modificações no modo Campanha.

### Equipe Plutonium (https://plutonium.pw/)

Por disponibilizar uma plataforma moderna, segura e compatível com modificações para o Multijogador e o Modo Zumbis.

### Non Decet (https://steamcommunity.com/id/nondecet)

Responsável pelos testes completos do projeto, validação da experiência do usuário e fornecimento de feedback durante o desenvolvimento.

### Sérgio Moreno Filmes (https://br.linkedin.com/company/sergio-moreno-filmes)

Pelo excelente trabalho realizado na dublagem oficial em Português do Brasil de **Call of Duty: Black Ops II**, utilizada como base para a produção das legendas deste projeto.

---

# Aviso

Este projeto é uma iniciativa independente de preservação.

Todo o conteúdo utilizado pertence aos seus respectivos detentores de direitos. Este repositório não distribui o jogo nem substitui a necessidade de possuir uma cópia legítima de **Call of Duty: Black Ops II**.

Este projeto não possui qualquer vínculo oficial com a Activision Blizzard King, Treyarch, Microsoft ou quaisquer de suas afiliadas, nem com qualquer outra empresa envolvida no desenvolvimento, publicação ou distribuição do jogo.
