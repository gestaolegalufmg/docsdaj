Documentos e formulários básicos da Divisão de Assistência Judiciária da UFMG.

Padronização de Código Fonte
----------------------------

Nomes do arquivos de entrevistas (.yml) e de templates (.docx) devem ser feitos:
* Nome completo do documento separado por hífens
* Os arquivos devem ter as extensões *.yml* e *.docx* respectivamente
* Remoção de todos os caracteres especiais (acentos, til, cedilha)
* Todas as letras devem ser minúsculas
* Os arquivos de entrevistas e de templates devem ter o mesmo nome
* Os nomes dos arquivos não podem ser abreviados

Exemplo: Declaração de comparecimento
**CERTO**
```bash
declaracao-de-comparecimento.yml
declaracao-de-comparecimento.docx
```
**ERRADO**
```bash
Declaração-de-Comparecimento.yml - Uso de maiúsculas e carcteres especiais
declaracao_de_comparecimento.yml - Separação por underscore
declaracao-comparecimento.yml - Nome incompleto ou abreviado
declaracao-de-comparecimento.yaml - Extensão errada
```

**ERRADO**
```bash
declaracao-de-comparecimento.yml
declaracao-de-comparecimento-do-assistido.docx - Nomes de entrevistas e de templates divergentes
```


Ainda em desenvolvimento.

Acesse o servidor beta e nos ajude em nossos testes!

* [Servidor de Testes](https://docassemble.robertonovaes.com.br)
