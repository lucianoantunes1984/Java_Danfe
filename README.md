> [!IMPORTANT]
> **Projeto descontinuado.** O Java_Danfe não recebe mais manutenção: a impressão dos documentos fiscais passou a ser feita dentro do projeto de cada documento, e não mais em uma biblioteca separada. Assim cada impressão acompanha a mesma versão dos schemas e das notas técnicas do documento que ela imprime, sem depender de uma atualização à parte.

## Para onde foi a impressão

| Documento | Projeto | Onde está |
|---|---|---|
| NF-e, NFC-e e CC-e | [Java_NFe](https://github.com/Samuel-Oliveira/Java_NFe) | pacote `br.com.swconsultoria.nfe.impressao`, com o DANFE v2 (leiaute da NT 2026.010) em `impressao.v2` |
| NF3e | [Java_NF3e](https://github.com/Samuel-Oliveira/Java_NF3e) | `br.com.swconsultoria.nf3e.util.ImpressaoUtil` |
| DC-e | [Java_DCe](https://github.com/Samuel-Oliveira/Java_DCe) | `br.com.swconsultoria.dce.util.ImpressaoUtil` |
| CT-e | [Java_CTe](https://github.com/Samuel-Oliveira/Java_CTe) | a impressão será publicada no próprio projeto |
| MDF-e | [Java_MDFe](https://github.com/Samuel-Oliveira/Java_MDFe) | a impressão será publicada no próprio projeto |

Os demais projetos da família seguem o mesmo caminho: [Java_ABI](https://github.com/Samuel-Oliveira/Java_ABI), [Java_NFag](https://github.com/Samuel-Oliveira/Java_NFag), [Java_Certificado](https://github.com/Samuel-Oliveira/Java_Certificado).

Este repositório fica somente como referência, em modo leitura. A versão `1.8` continua no Maven Central para quem ainda depende dela, mas não haverá novas versões, correções nem suporte. **Issues e Pull Requests devem ser abertos no projeto do documento correspondente.**

Dúvidas e sugestões: [Discord do projeto](https://discord.gg/ZXpqnaV).
