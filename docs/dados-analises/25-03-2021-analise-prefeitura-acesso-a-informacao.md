---
template: overrides/main.html
---

<p align="center">
       <a href="https://dadosabertostucano.org/dados-analises/">
          <img src="https://dadosabertostucano.org/assets/images/acesso_informacao.png" width="340" alt="Acesso a informação">
       </a>
    </p>

??? "➡️ Ferramentas de acessibilidade"

    :material-cursor-default-click-outline: Clique no botão abaixo para alternar visualização:

    <div class="tx-switch">
       <button data-md-color-scheme="default"><code>Modo normal</code></button>
       <button data-md-color-scheme="slate"><code>Modo escuro</code></button>
    </div>

    <script>
        var buttons = document.querySelectorAll("button[data-md-color-scheme]")
        buttons.forEach(function(button) {
        button.addEventListener("click", function() {
        var attr = this.getAttribute("data-md-color-scheme")
        document.body.setAttribute("data-md-color-scheme", attr)
        var name = document.querySelector("#__code_0 code span:nth-child(7)")
        name.textContent = attr
       })
    })
    </script>


# 📈 Análise: **Serviço de Informação ao Cidadão** da **Prefeitura de Tucano** não atende requisitos da Lei 
> Publicado em 25 de março de 2021 - Análise: **Dados Abertos de Tucano.**

**Serviço de Informação ao Cidadão** da **Prefeitura de Tucano** não atende requisitos da Lei,
apresentando problemas nas **solicitações de pedido**, **consulta** e **prazos legais**. Foi o que constatamos após análise do sistema que hoje encontra-se no ar. 

## Lei de acesso à informação 

A [Lei nº 12.527, de 18 de novembro de 2011](http://www.planalto.gov.br/ccivil_03/_Ato2011-2014/2011/Lei/L12527.htm) tem como objetivo: 

> Regular o acesso a informações previsto no inciso XXXIII do art. 5º , no inciso II do § 3º do art. 37    e   no § 2º do art. 216 da Constituição Federal; altera a Lei nº 8.112, de 11 de dezembro de 1990; revoga a Lei nº 11.111, de 5 de maio de 2005, e dispositivos da Lei nº 8.159, de 8 de janeiro de 1991; e dá outras providências. 

A **LAI**, como é conhecida a **Lei de Acesso à Informação**, trouxe a possibilidade dos órgãos públicos publicarem seus dados abertos em portais na internet, e quando estes não estiverem disponíveis em portais web, o cidadão poderá fazer pedidos de acesso à informação e mais ainda, deu ao cidadão e cidadã ferramentas de busca de informações públicas que estavam e ainda estão indisponíveis para a população em geral. 

A **LAI** informa prazo máximo de 20 (vinte) dias para o órgão público respoder solicitações de acesso à informação. Depois desse prazo o ente público poderá prorrogar o prazo por mais 10 dias, há ainda 10 dias para o requernete do pedido recorrer da resposta negativa ou insatisfatória obtida e o órgão público tem 5 (cinco) dias para responder o primeiro recurso. A partir daí, caso necessite, é possível recorrer numa 2ª instância e novamente o órgão público tem 5 (cinco) dias para responder esse segundo recurso. 

Observa-se que nem todos os dados públicos estão nos portais de transparência dos municípios. Os que estão sendo publicados muitas vezes encontram-se desatualizados ou em formatos inviávies para trabalho de análise. 

## Portal E-SIC da Prefeitura 

Diante disso, a **Prefeitura Municipal de Tucano**, Bahia, fornece um portal chamado **E-SIC** para pedidos de acesso à informação. Acesse o Portal, [clicando aqui](http://acessoinformacao.org.br/ba/tucano/#sic). Orientamos que você acesse o link após leitura da análise discutida aqui. 

## Problema analisado  

Ao acessar a página do [E-SIC](http://acessoinformacao.org.br/ba/tucano/#sic), nos deparamos com a seguinte tela: 


<p align="center">
<img src="/../assets/images/prefeitura/imagem_1.png" alt="" style="width: 80%; height: auto;">
</p> 


Ao clicar em **Faça um pedido** no item **1 na imagem**, o usuário é redirecionado para a página de [novo pedido](http://acessoinformacao.org.br/ba/tucano/esic/?p=novo-pedido):

<p align="center">
<img src="/../assets/images/prefeitura/imagem_2.png" alt="" style="width: 80%; height: auto;">
</p> 

No item **2 na imagem** o usuário é redirecionado para **Consultar o pedido**. 

Ao abrir a página de novo pedido, é apresentado um formulário eletrônico para preechimento de dados do 
solicitante sinalizado no **item 3 da imagem**: 

<p align="center">
<img src="/../assets/images/prefeitura/imagem_3.png" alt="" style="width: 80%; height: auto;">
</p> 

Já é possível levantarmos que o sistema não faz um cadastro de usuário, fornece apenas um formulário para fazer o pedido. Pela Lei, o órgão público 
deve fornecer um sitema que possibilite por exemplo, ao usuário recorrer da negativa de pedido de acesso à informação. Assim, a priori, o Serviço de Informação ao Cidadão da Prefeitura Municipal de Tucano falha ao não forncer meio para recursos de pedidos negados. 


Nos campos do formulário consta o tipo **Natureza** que pode ser **aberto** ou **sigiloso**, siginifica que o cidadão pode deixar a resposta, se houver, do pedido de informação aberta para consulta de terceiros ou será sigilosa, onde somente quem fez o pedido teria acesso a resposta do órgão. Entretanto, constatamos que o Sistema da Prefeitura não permite que terceiros consulte a lista de pedidos e respostas, ficando a consultar de respostas restrita aos respectivos pedidos somente quem fez o pedido.

Veja outras falhas encontradas: 

+ Não fornecimento dos dados de pedidos de acesso à informação anteriores, mesmo aqueles que foram solicitados na **Natureza** **sigiloso**.

+ O formulário eletrônico não possibilita o **anexo de arquivo** com a redação do pedido de acesso a informação. Dependendo do tipo de pedido de acesso, pode ser necessário no pedido inserir imagens ou tabelas, isso ficaria impossibilidado, pois o campo de texto para **Descrição do Pedido** não aceita anexar arquivos externos.

+ A [Lei nº 13.460/207](http://www.planalto.gov.br/ccivil_03/_Ato2015-2018/2017/Lei/L13460.htm) conforme disposto no art. 10 § 7º, garante ao requerente do pedido ter a 
identidade preservada, em atendimento ao princípio constitucional da impessoalidade, entretanto no formulário fornecido pela prefeitura, não é possível ter a identidade preservada. 

No campo **Meio de Resposta** é possível receber a resposta do pedido por 4 possibilidades: **Correspondência fiscal(com custo)**; **E-mail**; **Pelo Sistema** e **Pessoalmente**.

O sistema **falha** novamente ao não fornecer informações adicionais sobre prazo de atendimento ao pedido de acesso a informação. Segundo a LAI, o prazo é de 20 dias, prorrogáveis por mais 10 dias, sem contar as possibilidades de recurso.  

A **LAI** permite que o requerente possa interpor recursos devido a negativas do órgão público ao acesso à informação solicitada. Infelizmente o **sistema** fornecido pela Prefeitura Municipal de Tucano não tem essa opção. Assim, o órgão público não está seguindo a LAI, acarretando a possiblidade de punições aos agentes públicos previsto na **LAI**. 

É importante salientar que o sistema hoje implementado foi um trabalho de gestões anteriores do executivo municipal, tendo a **nova gestão municipal** que assumiu a prefeitura em janeiro de 2021, pouco mais de 75 dias para realizar melhorias e ajustar eventuais equívocos, ou seja, o sistema que hoje está no ar não é fruto do trabalho da atual gestão municipal. 

!!! failure "Erro grave"
      O **erro grave** constato está presente no recebimento da resposta do pedido **Pelo Sistema**. 
      Especificamente ao acessar o formulário de [**Consultar o Pedido**](http://acessoinformacao.org.br/ba/tucano/esic/?p=consultar-pedido). Como consta nas imagens no itens **4** e **5**. 

<p align="center">
<img src="/../assets/images/prefeitura/imagem_4.png" alt="" style="width: 80%; height: auto;">
</p> 

Após preenchimento dos dados de **Protocolo** e **CPF**, temos 

<p align="center">
<img src="/../assets/images/prefeitura/imagem_5.png" alt="" style="width: 80%; height: auto;">
</p> 

Ao clicar em **Consultar Pedido**:

<p align="center">
<img src="/../assets/images/prefeitura/imagem_6.png" alt="" style="width: 80%; height: auto;">
</p> 

Aguardando o sistema redirecionar, constatamos 

<p align="center">
<img src="/../assets/images/prefeitura/imagem_7.png" alt="" style="width: 80%; height: auto;">
</p> 


!!! success "Erro corrigido"
    Este erro mostrado acima já foi **CORRIGIDO** pela **Prefeitura Municipal de Tucano (atual gestão)** a partir de contato do **Dados Abertos de Tucano**. 


Ao abrir a página de acompnhamento do pedido, temos a seguinte tela: 

<p align="center">
<img src="/../assets/images/prefeitura/imagem_8.png" alt="" style="width: 80%; height: auto;">
</p> 

Apesar do **Meio de Resposta** ter sido e-mail, podemos verificar que não consta nenhum tipo de botão ou formulário para solicitar recursos ou mesmo fazer a consulta da resposta, tão pouco recebemos por e-mail algum tipo de resposta. Até a data de **25 de março de 2021** não fomos atendidos dentro do prazo legal de 20 dias, visto que o pedido de acesso à informação foi feito na data de **14 de fevereiro**. Este pedido requeria a **listagem nominal de vacinados na cidade de Tucano**, Bahia. 


!!! warning "Conclusão"
    Infelizmente o sistema ainda não atende integralmente o que a Lei exige, mas é possível implementar melhorias, pois sem acesso a dados públicos abertos e integros, a transparência do município fica falha,provocando a falta de mecanismos de fiscalização pelos cidadões frente aos atos da gestão executiva municipal. 


## O que diz a Prefeitura de Tucano 

Procurada, a Prefeitura Municipal de Tucano, através da ASCOM, nos atendeu prontamente na busca de solucionar os problemas levantados por nós indicados nesta análise. Tanto que em pouco minutos acionou o suporte da plataforma (http://acessoinformacao.org.br/ba/tucano/esic) para imediatamente corrigir o erro no formulário de **Consulta de Pedido**. A Prefeitura mostrou-se preocupada com a transparência pública e nos sinalizou que buscará verificar a implantação de melhorias. 

O **Dados Abertos de Tucano** sugeriu nesta comunicação com a ASCOM, o estudo de uso pela 
Prefeitura do Sistema da CGU de Acesso à Informação, o [Fala.BR](https://falabr.cgu.gov.br/). É um sistema que possibilita aos órgãos públicos, oferecer ao cidadão e cidadã um sistema robusto para solicitaçãos de acesso à informação com todas as ferramentas de consulta de pedido, processo de recursos e respostas, acompanhamento de prazos e envio eletrônico ágil de eventuais documentos. 

## Como posso usar o E-SIC? 

Qualquer cidadão e cidadã pode utilizar o **Serviço de Informações ao Cidadão** para obter dados e documentos que não contenham dados sigilosos e pessoais ou documentos que não estejam classificados como sigilosos pela adminstração pública. Por exemplo, é possível solicitar cópias de contratos da prefeitura com empresas, caso esses contratos ainda não estejam disponíveis no Portal de Acessso à Informação do órgão público. 


## Fontes 

Assessoria de Comunicação - ASCOM, através da Secretaria de Comunicação de Tucano. 

Escola de Dados, Portal Web. Acese: [Tutoriais](https://escoladedados.org/tutoriais/solicitando-dados-via-lei-de-acesso-a-informacao/). 


[**Lei nº 12.527 - Lei de Acesso à Informação.**](http://www.planalto.gov.br/ccivil_03/_Ato2011-2014/2011/Lei/L12527.htm)

[**Lei nº 13.460/2017.**](http://www.planalto.gov.br/ccivil_03/_Ato2015-2018/2017/Lei/L13460.htm)
