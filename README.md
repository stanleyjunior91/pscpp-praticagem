# Tutor PSCPP – Praticante de Prático

Skill para o Claude que ajuda candidatos a estudar para o **PSCPP**, o Processo Seletivo
à Categoria de Praticante de Prático da Diretoria de Portos e Costas (DPC/Marinha do
Brasil).

Quase não existe material aberto e organizado para esse concurso. A skill junta o que o
candidato precisa consultar o tempo todo:

- **Conteúdo programático** (Anexo 2-A da NORMAM-311/DPC) completo, com a numeração
  original, para achar qualquer item do programa.
- **Bibliografia sugerida** (Anexo 2-B) por parte e capítulo, com uma tabela tema → fonte.
- **Pontos-chave conferidos** da NORMAM-311 (versão de 21/09/2026) e da Lei 14.813/2024.
- **Análise das provas anteriores** (2006, 2008, 2011, 2012 e o remanejamento da ZP-07 em
  2023): formato, estilo da banca, distribuição por parte e cuidados com normas que mudaram.

## O que ela faz

- Explica temas do programa (squat, ponto pivô, curva de giro, efeito de banco, interação
  entre navios, rebocadores, COLREG, LESTA, meteorologia, SMCP…) ligando a teoria à prática
  de manobra, e diz onde estudar cada um.
- Gera questões e simulados no estilo da banca, com gabarito comentado.
- Simula a prova prático-oral em inglês, fazendo o papel do comandante no MPX.
- Monta plano de estudos até a prova escrita.
- Responde "isso cai?" e "onde estudo isso?" com o item do programa e a fonte.

Ela não traz os livros da bibliografia, que têm direitos autorais. Se você tiver o
material (PDFs no computador ou no Google Drive, com um conector ligado), a skill usa
esse material para basear as respostas.

## Instalar

**Claude Code:** copie a pasta `pscpp-praticagem` para `~/.claude/skills/` (todas as
conversas) ou para `.claude/skills/` dentro de um projeto.

**Claude.ai:** compacte a pasta `pscpp-praticagem` em um .zip e envie em
Configurações → Capacidades → Skills.

Depois é só conversar: "me explica o efeito squat", "faz um simulado de 10 questões da
Parte I", "monta um plano de estudos de 10 horas por semana".

## Situação do concurso

Pelo cronograma tentativo da DPC (nota de 27/04/2026), o edital sai em julho de 2027 e a
prova escrita é em novembro de 2027. **O edital é quem manda:** quando ele sair, confira
conteúdo, pesos e edições da bibliografia.

## Aviso

Material de estudo independente, sem vínculo com a Marinha do Brasil, a DPC ou a
Praticagem do Brasil. Os textos oficiais estão em
https://www.marinha.mil.br/dpc/normas-autoridade-maritima-brasileira. Correções e
contribuições são bem-vindas: abra uma issue ou um pull request.

## Licença

MIT. Veja [LICENSE](LICENSE).
