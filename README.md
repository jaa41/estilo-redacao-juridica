# Estilo de redação jurídica

Uma *skill* (arquivo de instruções que a IA lê antes de escrever) para textos jurídicos
redigidos com apoio de inteligência artificial: decisões, sentenças, votos, petições,
pareceres, artigos e postagens.

Autor: **Jorge Araujo**, juiz do trabalho. Apresentada no artigo
*A IA Escreve Como Nós*, no Substack [IA e Direito](https://jorgealbertoaraujo.substack.com).

## O que ela faz

- Corta o vocabulário que denuncia a máquina ("crucial", "robusto", "é importante
  destacar") e o bacharelês ("outrossim", "nesse diapasão").
- Exige concretude (valores, datas, o documento que prova) e referências verificáveis:
  não conferiu na fonte oficial, não cita.
- Traz um roteiro para a decisão sair sem as omissões, contradições e obscuridades que
  geram embargos de declaração (`references/evitar-embargos.md`).
- Foi feita para ser adaptada: a seção 9 recebe o padrão pessoal de quem a usa, e
  `references/como-adaptar.md` explica como montá-lo comparando minutas com as versões
  assinadas.

## Como instalar

**[Baixar a skill (.zip)](https://github.com/jaa41/estilo-redacao-juridica/releases/latest/download/estilo-redacao-juridica.zip)**

- **Claude (site ou aplicativo)**: Configurações → Capacidades → Skills → enviar o `.zip`.
- **Claude Code**: descompactar a pasta `estilo-redacao-juridica` em `~/.claude/skills/`.
- **Outras ferramentas**: as que adotaram o padrão aberto
  [Agent Skills](https://agentskills.io/home) leem a pasta. Nas demais, cole o conteúdo do
  `SKILL.md` como instrução do projeto ou do assistente.

Antes de usar a IA com peças de processos reais, retire nomes e dados pessoais ou use
uma ferramenta autorizada pelo seu tribunal ou escritório.

## Licença

[CC BY 4.0](LICENSE): use, adapte e redistribua à vontade, citando a autoria.
