# Licenças e avisos de terceiros

> Inventário técnico em 16/11/2026. Revisar antes de cada versão distribuída.

| Componente | Uso no NEXUS | Licença / situação |
|---|---|---|
| .NET 10 e WPF (Microsoft) | Plataforma do aplicativo | MIT. Se o instalador incluir o runtime (autossuficiente), anexar os avisos de licença do .NET e de seus componentes. |
| PresentMon (Intel) | Medição de FPS, executado sob demanda | MIT. **Não é distribuído** com o NEXUS: o usuário baixa do repositório oficial; a assinatura digital da Intel é verificada antes do uso. |
| Fontes Segoe UI, Bahnschrift e ícones Segoe Fluent Icons | Interface | Fontes do Windows, usadas a partir do sistema. **Não são redistribuídas** com o NEXUS. |
| Ferramentas do Windows (SFC, DISM, CHKDSK, Limpeza de Disco) | Abertas a pedido do usuário | Parte do Windows; não são redistribuídas. |
| xUnit e pacotes de teste | Somente no projeto de testes | Não fazem parte do aplicativo distribuído. |
| Logo NEXUS | Ícone e marca | Arte própria do NEXUS Optimizer. |

## Licença MIT do .NET (incluído no executável autossuficiente)

Copyright (c) .NET Foundation and Contributors. Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the "Software"), to deal in the Software without
restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense,
and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the
following conditions: The above copyright notice and this permission notice shall be included in all copies or
substantial portions of the Software. THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

O runtime do .NET também inclui componentes de terceiros com avisos próprios, publicados no arquivo
THIRD-PARTY-NOTICES.TXT do repositório oficial dotnet/runtime.

Marcas citadas (Microsoft, Windows, DirectX, Xbox, NVIDIA, AMD, Ryzen, Intel, Steam, Epic Games, Discord, OBS e
outras) pertencem aos seus respectivos titulares e são mencionadas apenas para identificar compatibilidade.
