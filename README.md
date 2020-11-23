# Analysis-of-security-vulnerabilities
Iniciação Científica - Análise de vulnerabilidades de segurança presentes no StackOverflow

Resumo

Com os avanços tecnológicos, as vulnerabilidades se tornaram mais complexas e perigosas, tal afirmação pode ser comprovada ao observar a rápida disseminação dos vírus, que estão mais sofisticados. Uma alternativa para amenizar esse problema foi a criação do NVD (National Vulnerability Database) que é o repositório de dados de gerenciamento de vulnerabilidade do governo dos Estados Unidos. Esses dados permitem a automação desse gerenciamento, além de medidas de segurança e conformidade, como por exemplo, a correção de falhas encontradas em um determinado software, com objetivo de deixá-lo seguro e funcional.


O NVD inclui dados de referências de listas de verificação relacionadas à segurança, falhas de software relacionadas a ela, configurações incorretas, nomes de produtos e métricas de impacto. Esses dados servirão de fonte para o desenvolvimento da pesquisa. Assim, obtém-se estatísticas relacionadas à nossa linha de estudos. Além disso, neste projeto iremos trabalhar com a plataforma do Stack Overflow, coletando posts que tenham alguma citação relacionada à segurança da informação, em especial às citações de CVE (Common Vulnerabilities and Exposures) e CWE (Common Weakness Enumeration).

O objetivo geral deste trabalho é usar métodos de Mineração de Dados para analisar vulnerabilidades de segurança presentes na base de dados da NVD e que são citados no Stack Overflow, o qual é um site de perguntas e respostas voltado para profissionais e entusiastas na área de programação de computadores. Para alcançar tal objetivo é necessário o conhecimento em assuntos como: conceitos básicos sobre segurança da informação, ferramentas estatísticas, banco de dados, Big Data e programação. 

A metodologia utilizada em algumas das etapas deste trabalho envolveu o desenvolvimento de scripts, parsers e expressões regulares para a obtenção e manipulação dos dados. Além disso, também foram utilizados como fonte de informações dois bancos de dados: o da NVD e o do Stack Overflow. Os dados coletados foram salvos em formato de arquivo .csv e posteriormente analisados utilizando a ferramenta Excel e linguagens de programação como Python e R.

Os resultados preliminares indicam um total de 1285 CVE’s diferentes, com média de CVSS - indicador do grau de severidade da vulnerabilidade - igual a 6,3. Além disso, 74,7% dos CVE’s apareceram em apenas uma postagem. Outro resultado alcançado se refere à quantidade de CVE’s que possuem exploits presentes no mundo real, que totalizou 6,38% e possui média de CVSS igual a 8,14. Ademais, para analisar o impacto das postagens relacionadas às vulnerabilidades foram analisados os votos de cada uma no Stack Overflow, que obteve média de 6,22.
