# Organizador de informações para o IRPF

Projeto criado para o desafio da DIO de organização de informações para a declaração do Imposto de Renda da Pessoa Física. A pasta de trabalho reúne campos para anotar rendimentos, pagamentos, bens e direitos, dívidas, dependentes e documentos de apoio.

## Arquivos

- `Organizador_IRPF.xlsx`: modelo vazio com validações, resumo e checklist.
- `images/preview.png`: prévia da aba inicial.

![Prévia da aba Início](images/preview.png)

## Abas da planilha

- **Início:** ano-calendário, exercício seguinte, resumo de valores informados, mapa das abas e endereços de orientações oficiais.
- **Rendimentos:** fonte pagadora, pessoa a que se refere o rendimento, categoria, valor informado, imposto retido ou pago e comprovante.
- **Pagamentos:** beneficiário, categoria, titular/dependente, valor pago e reembolso. A diferença é apenas informativa e não classifica uma despesa como dedutível.
- **Bens e Direitos:** descrição, titularidade e valores informados em 31 de dezembro do ano anterior e do ano-calendário.
- **Dívidas:** credor, saldos de referência, valores pagos e comprovantes.
- **Dependentes:** dados básicos, relação com o titular e indicação para conferir se houve rendimentos.
- **Checklist:** documentos e tarefas gerais com campos para aplicabilidade e situação.

## Recursos do Excel

- Listas suspensas para categorias, titularidade e situação dos comprovantes.
- Validação para restringir valores monetários a números não negativos e o ano-calendário a um intervalo válido.
- Destaque condicional para identificar comprovantes pendentes ou conferidos.
- Resumo automático dos valores digitados e dos itens pendentes.
- Mapa de abas na página inicial; use as abas com esses mesmos nomes na parte inferior do Excel.
- Links da Receita Federal apresentados como URLs para copiar e abrir no navegador.

## Como usar

1. Baixe `Organizador_IRPF.xlsx` e faça uma cópia privada para preencher.
2. Na aba **Início**, informe o ano-calendário. O exercício seguinte é exibido automaticamente.
3. Registre cada informe, pagamento, bem, dívida e dependente na aba correspondente, preferencialmente uma linha por item.
4. Atualize a situação dos comprovantes no checklist e nas abas de dados.
5. Compare os registros com os documentos originais e siga as orientações oficiais para o ano da declaração.

O modelo não calcula imposto devido, não identifica automaticamente deduções e não envia declaração à Receita Federal. As categorias são organizacionais e podem não abranger todas as situações. Consulte as regras atuais para cada item e ano-calendário.

## Privacidade

O arquivo público neste repositório está vazio. Depois de preencher a sua cópia, guarde-a em local privado e **não publique nem envie ao GitHub uma versão preenchida**. Ela pode conter CPF, rendimentos, patrimônio, despesas e informações de dependentes.

## Referências oficiais

- [Meu Imposto de Renda — Receita Federal](https://www.gov.br/receitafederal/pt-br/assuntos/meu-imposto-de-renda)
- [Como fazer a declaração](https://www.gov.br/receitafederal/pt-br/assuntos/meu-imposto-de-renda/preenchimento)
- [Dicas de preenchimento](https://www.gov.br/receitafederal/pt-br/assuntos/meu-imposto-de-renda/preenchimento/dicas)
- [Perguntas e respostas IRPF 2026 — Receita Federal](https://www.gov.br/receitafederal/pt-br/centrais-de-conteudo/publicacoes/perguntas-e-respostas/dirpf/p-r-irpf-2026-v1-00-2026-04-23.pdf)
