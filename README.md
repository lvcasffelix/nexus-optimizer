# NEXUS Optimizer

Otimizador do Windows para jogos: **analisa** o seu PC, **explica** o que pode melhorar, só **altera com a sua
confirmação**, **mede** antes e depois e **desfaz** qualquer ajuste com um clique.

Gratuito · Windows 10/11 64 bits · funciona offline · não envia dados.

## Download

1. Abra **[Releases](../../releases/latest)** e baixe **`NexusOptimizer.exe`**.
2. Dê dois cliques. Não precisa instalar nada.

> **Aviso do Windows ("O Windows protegeu o computador" / "Editor desconhecido").**
> O NEXUS ainda não tem assinatura digital paga, então o Windows SmartScreen mostra esse aviso para programas novos.
> Se você baixou desta página, clique em **Mais informações → Executar assim mesmo**.
> Baixe **somente** desta página: esta é a única fonte oficial.

### Conferir se o arquivo é original (opcional)

Cada versão traz o arquivo `SHA256.txt`. No PowerShell, na pasta do download:

```powershell
Get-FileHash .\NexusOptimizer.exe -Algorithm SHA256
```

O código mostrado deve ser **igual** ao do `SHA256.txt` da mesma versão. Se for diferente, não abra o arquivo.

## O que ele faz

- **Dashboard e diagnóstico:** CPU, GPU, RAM, temperatura, disco e o que pode estar atrapalhando seus jogos.
- **Gaming Boost:** perfis Safe, Performance e Custom com plano, riscos e confirmação antes de qualquer alteração.
- **Latência & Controles:** Timer no Máximo (como o Set Timer Resolution), perfis Competitivo/Padrão, teste de mouse (Hz)
  e de controle, monitor na frequência máxima e guia de limite de FPS para o seu monitor.
- **Perfis por jogo**, **FPS & Benchmarks** (com PresentMon) e comparação antes/depois.
- **Limpeza Inteligente** com prévia, **arquivos duplicados** (cópias vão para a Lixeira) e **saúde do SSD**.
- **Histórico & Restauração:** cada alteração guarda o valor original e pode ser desfeita.

## O que ele **nunca** faz

Não desativa antivírus, firewall, Windows Update ou UAC; não mexe na BIOS; não faz overclock; não interfere em jogos
nem em anticheats (não injeta código, não simula teclas, não mexe no processo do jogo); não promete FPS sem medir;
não coleta nem envia seus dados.

## Termos

Ao abrir o programa você lê e aceita os documentos abaixo (também estão dentro do app, em *Ajuda & Sobre*):

- [Termos de Uso e Licença](TERMOS-DE-USO-E-LICENCA.md)
- [Aviso de riscos e limitações](AVISO-DE-RISCOS.md)
- [Política de Privacidade](POLITICA-DE-PRIVACIDADE.md)
- [Licenças de terceiros](LICENCAS-DE-TERCEIROS.md)

Recomendação: mantenha backup dos seus arquivos importantes e um ponto de restauração do Windows.

© Equipe NEXUS Optimizer. Uso pessoal gratuito; redistribuição não autorizada (veja os Termos).
