<h1 align="center">Notas para Contribuidores</h1>

### Branches

Os branches do projeto seguem explicados abaixo:

- *main* - branch principal utilizado para RELEASES. Segue o padrão [SEMVER](https://semver.org/lang/pt-BR/), sem o uso de sufixos indicadores, com exceção do sufixo de build de data (AAMMDD), o qual é removido automaticamente da lista de RELEASES, porém deve ser mencionado nas Notas de Versão. Os commits ao *main* devem ser feitas indiretamente por PR do branch *enderdragon*. Não são incentivados commits diretamente ao *main*.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Versionamento - Ao realizar commits para o *main*, é OBRIGATÓRIO constar todos os dados das Notas de Versão dos outros branches, até a numeração da versão de RELEASE a ser commitada.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Delegações ao branch *main* em ordem de prioridade:
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Consolidação de versões
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Implantação de builds

- *enderdragon* - branch para desenvolvimento e revisões do branch *panda*. Segue o padrão SEMVER, com o uso do sufixo 'beta' juntamente com o sufixo de build de data, no modelo 'vx.x.x-AAMMDD-beta'. Única branch com permissão de realizar PRs para a *main*.

Após qualquer commit, antes de realizar quaisquer novas alterações ao código, observar se alguma PR ainda não está pendente. É sugerido aguardar que todas as PRs estejam devidamente resolvidas para, então, prosseguir com novas alterações. Sempre realizar merge com *main* antes de prosseguir com novas alterações ao código.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Versionamento - Ao realizar commits para o *enderdragon*, manter somente as anotações referentes aos commits deste branch, utilizando do versionamento a partir da versão do *main*.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Delegações ao branch *enderdragon* em ordem de prioridade:
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Desenvolvimento de Features
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Documentação
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Normalização de PRs de *panda*

- *panda* - branch para desenvolvimento e patches quando executado em Linux ou Mac. Segue o padrão SEMVER, com o uso do sufixo 'beta' juntamente com o sufixo de build de data, no modelo 'vx.x.x-AAMMDD-beta'. Panda deve enviar PRs para *enderdragon* ao sugerir modificações.

Após qualquer commit, antes de realizar quaisquer novas alterações ao código, observar se alguma PR ainda não está pendente. É sugerido aguardar que todas as PRs estejam devidamente resolvidas para, então, prosseguir com novas alterações. Sempre realizar merge com *main* antes de prosseguir com novas alterações ao código.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Versionamento - Ao realizar commits para o *panda*, manter somente as anotações referentes aos commits deste branch.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Delegações ao branch *panda* em ordem de prioridade:
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Patches de correção para Linux ou Mac
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Implantação de melhorias em código existente
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Linting e Sanitização
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Desenvolvimento de Features

### Admissão de Contribuidores

No momento não estamos abertos a contribuidores para este projeto. No entanto, sinta-se à vontade para fazer um fork e criar uma aplicação da forma que preferir.
