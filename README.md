# Class-Helpers
Classe de ajuda ao desenvolver PHP! 
Irá conter vários métodos usados no dia a dia de todo programador PHP!

Métodos da Classe:

<strong>Helpers::limitWords($string, $limite, $terminarCom = null);</strong>
<br />
limita a quantidade de palavras de uma string.
<br />
<strong>Helpers::limitChars($string, $limite, $terminarCom = null, $ocorrencia = "");</strong>
<br />
limita a quantidade de caracteres de uma string.
<br />
<strong>Helpers::slug($string);</strong>
<br />
cria os famosos "slug" ou url amigável
<br />
<strong>Exemplo:</strong> se tivermos uma url assim 'site.com.br/produto/15", podemos criar um slug pra ficar assim: 'seusite.com.br/produto/camiseta-amarela-tam-p'
<br />
<strong>Helpers::isMail(string $email);</strong>
<br />
valida através de expressões regulares o formato do e-mail passado.
<br>
<strong>Helpers::CPF();</strong>
<br/>
<br>Exemplo de Uso:         if(Helpers::CPF('111.111.111-11')){
            echo "valido";
        }else{
            echo "invalido";
        }
        <br/>

