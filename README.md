# CVSS Converter

## O que faz?
- Converte o link de métricas para conjunto em português:
  - De: ```https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:N/A:N&version=3.0```
  - Para: ```CA:Baixo,RA:Não,IU:Não,AE:Não,C:Alto,I:Não,D:N```
- Converte as métricas de vulnerabilidade de inglês para português:
  - De: ```AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:N/A:N```
  - Para: ```VA:Remoto,CA:Baixo,RA:Não,IU:Não,AE:Não,C:Alto,I:Não,D:Não```
- Converte as métricas de vulnerabilidade de português para inglês (link):
  - De: ```VA:Remoto,CA:Baixo,RA:Não,IU:Não,AE:Não,C:Alto,I:Não,D:Não```
  - Para: ```https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:N/A:N&version=3.0```
- Possui compatibilidade com sites NIST e FIRST.
