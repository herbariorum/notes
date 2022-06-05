## SelectField Dinâmico com Flask e JQuery

Neste exemplo, faço a carga dinâmica de um wtform selectfield contendo uma lista de cidades, a partir da seleção do estado em outra lista.

```
uf = wtforms.SelectField(
        'UF',
        choices=ufbr.list_uf
    )

```
