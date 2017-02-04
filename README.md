Configuração:
Abra "favd.sh" procure a quarta linha onde diz "arquivo" e coloque seu arquivo de backup de favoritos gerado pelo mozilla (acredito que no chrome também funcione mas ainda nao testei) entre as aspas.
Na linha de baixo coloque entre as aspas o diretório onde quer salvar seus favoritos. 

Modo de Uso:
Execute ./fav.sh para transformar o arquivo html em diretórios.

Modo Reverso:
./favr.sh transforma os diretórios no arquivo html.

Modo Bakup:
./favb.sh mesmo que o fav.sh porém passa apenas os arquivos na pastra 'Outros favoritos'.

A ideia é salvar os favoritos pelo navegador, a pasta 'Outros favoritos' já é a padrão. Quando sentir necessidade de organizá-los, seguir as etapas:

<ol>
<li>Exportar arquivo do navegador.</li>
<li>Executar o favb.sh para trazer os novos favoritos ao seu pc.</li> 
<li>Organizá-los da forma que achar melhor.</li>
<li>Executar o favr.sh para gerar o novo arquivo.</li>
<li>Apagar favoritos do navegador.</li>
<li>Importar favoritos do arquivo para o navegador.</li>
</ol>

Dependências:
Nenhuma.

Bugs:
Em favoritos cujo o nome tem barras '/' defini para substituir por '"-"' pois não é possível diretórios ou arquivos com barras.
Alguns caracteres específicos não são escritos corretamente no nome dos favoritos.


