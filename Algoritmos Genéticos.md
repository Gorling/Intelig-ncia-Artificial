**Algoritmos Genéticos são baseados na teoria da evolução de Charles Darwin, são algoritmos generativos e funcionam apartir desses conceitos**:

  - **População**: o algoritmo começão com um conjunto de possíveis soluções que é chamado de população.
  - **Função de Aptidão (fitness)**: cada indivíduo é avaliado por uma função que mede o quão boa é a solução para o problema.
  - **Seleção**: indivíduos com maior aptidão têm mais chance de serem escolhidos para reprodução.
  - **Reprodução/Cruzamento (crossover)**: dois indivíduos (pais) são combinados para gerar novos indivíduos (filhos).
  - **Mutação**: para evitar convergência prematura e manter diversidade, pequenas alterações aleatórias são feitas em alguns indivíduos.
  - **Iteração**: o processo de seleção, cruzamento e mutação é repetido por várias gerações até que uma solução satisfatória seja encontrada ou um número máximo de iterações seja atingido.

  **Vantagens**

    Flexibilidade: podem ser aplicados a uma ampla variedade de problemas, mesmo com espaços de busca não lineares ou descontínuos.
    
    Robustez: são menos propensos a ficar presos em ótimos locais (máximos ou mínimos subótimos).
    
    Paralelismo: a natureza da população permite explorar várias soluções simultaneamente.
  
  **Desvantagens**

    Complexidade: podem ser lentos para problemas muito grandes ou com populações enormes.
    
    Não garantem a solução ótima: são heurísticos, então a solução final pode ser apenas uma aproximação.
