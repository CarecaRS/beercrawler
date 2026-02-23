### <img src="https://github.com/CarecaRS/TCC_USP/blob/master/caution.png" width="48"> This profile is no longer maintained here on GitHub, it has been migrated to [Codeberg.org](https://codeberg.org/twerminghoff/). <img src="https://github.com/CarecaRS/TCC_USP/blob/master/caution.png" width="48">

Na verdade isso é um scrapper, e não um crawler. Eu que me emocionei quando fui criar o nome do repositório e depois que me dei conta fiquei com preguiça de consertar. Então, reforço: ISSO É UM SCRAPPER, NÃO UM CRAWLER.

Inicialmente criado com a ideia de me avisar apenas da alteração dos preços de cervejas pré-selecionadas, resolvi expandir um pouco e o script busca também alterações nos preços de chocolates pré-selecionados.

Por hora funcionando apenas para o supermercados [Continente](https://www.continente.pt) e [Pingo Doce](https://www.pingodoce.pt) (neste tem um issue a ser ajustado nas cervejas), uma vez que são os mais próximos do meu local e os mais frequentes em Lisboa. Também por enquanto funcionando apenas com URLs específicas (sem um crawling dinâmico propriamente dito).

Problema de lazyloading já resolvido, os resultados em texto são 100% dos obtidos na web.

IMPORTANTE: os resultados obtidos (produtos/preço) são referentes aos sites 'genéricos', sem login. Uma vez que o usuário faz o login no site ele recebe informação apenas das lojas mais próximas e da rede inteira. O script aqui funciona somente com a funcionalidade da rede inteira, não vou integrar login nisso.

Ainda falta ajustar o `notify-send` do `hyprland` também. Mas tudo no seu tempo.
