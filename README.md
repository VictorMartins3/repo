# repo
prompt
Estamos pesquisando uma biblioteca open source em Rust para autorização e reservas de recursos usadas por agentes em APIs financeiras e blockchain.
Em experimentos locais, cotas reduziram bastante o custo de coordenação, mas criaram custos de capacidade ociosa e revogação. Uma alocação adaptativa reduziu mensagens em algumas cargas, mantendo o mesmo teto de cotas.
Usando apenas informações compartilháveis:
1. Onde está o gargalo real: política, assinatura, persistência, reconciliação ou comunicação?
2. Em quais operações seria aceitável delegar uma pequena cota local? Quais exigem verificação central a cada execução?
3. Como deveria ser tratada uma resposta perdida ou uma operação parcialmente executada?
4. O que ainda é difícil mesmo usando um ledger transacional e os controles da plataforma?
5. Qual benchmark, mantendo as mesmas garantias, faria uma equipe considerar adotar essa biblioteca?
Se possível, proponha um cenário reproduzível com requisitos aproximados.