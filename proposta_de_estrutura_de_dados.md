# Metadados de CNPJs

## Súmario

<ol>
    <li> <a href="#introducao"> Introdução </a> </li>
        <ul>
            <li> <a href="#problema"> Problema </a> </li>
            <li> <a href="#solucao"> Solução </a> </li>
        </ul>
    <li> <a href="#desenvolvimento"> Desenvolvimento </a> </li>
        <ul>
            <li> <a href="#estruturacao"> Estruturação dos dados </a> </li>
            <ul>
                <li> <a href="#der"> Proposta de Estrutura de dados </a>  </li>
            </ul>
            <li> <a href="#analises"> Análise dos Dados </a> </li>
        <ul>
</ol>

<h1 id = 'introducao'> Introdução </h1>
<p> Imagine que você foi contratado para trabalhar como <b> engenheiro analítico </b> na <b> "FilmTech Solutions"</b>, uma empresa líder em soluções para o setor de cinema e audiovisual. Sua função é explorar e analisar dados para fornecer insights valiosos, focando em auxiliar a tomada de decisões estratégicas. </p>

<h2 id = 'problema'> Problema </h2>
<p> A <b> "FilmTech Solutions" </b>, uma empresa fictícia B2B¹ especializada em fornecer soluções para empresas do ramo de cinema e audiovisual, enfrenta uma <b> <u> dificuldade significativa em compreender profundamente o perfil de seus clientes dentro desse setor específico. </b> </u> Essa lacuna de entendimento não apenas compromete a personalização dos serviços oferecidos aos clientes existentes, mas também <b> dificulta a identificação e a abordagem de novos potenciais clientes dentro do mercado de cinema e audiovisual. </b> Sem uma compreensão clara e detalhada do perfil do cliente, a <b> "FilmTech Solutions" </b> enfrenta obstáculos na definição de estratégias eficazes de prospecção, limitando assim seu potencial de crescimento e expansão dentro do setor. </p> 

<blockquote> <b>B2B:</b> B2B é quando uma empresa vende coisas para outra empresa em vez de para pessoas. <i>("Business-to-Business")</i>
</blockquote> 

<h2 id = 'solucao'> Solução </h2>
<p> Você como <b> Engenheiro Analitico </b> da "FilmTech Solutions" ao analisar este problema identifica pontos que explicam esta dor, pontos como: </p>
<ul>
    <li> <b> Dados limitadas sobre os clientes. </b> </li>
    <li> <b> Campanhas de Marketing genêricas. </b> </li>
</ul>

Sendo assim você propõe a empresa um projeto para solucionar esta escassez de dados relacionados aos clientes <b> obtendo os dados cadastrais relacionados aos CNPJs dos clientes </b> e através disso realizar análises para entender melhor o perfil de clientes e mapear ações a partir disso.

<hr>  
<br>


<h1 id = 'desenvolvimento'> Desenvolvimento </h1>
<p> Conhecendo o problema e a solução proposta, seu trabalho será realizar a estruturação dos dados relacionados aos CNPJs dos clientes, de modo com que as estruturas sejam escaláveis e fácilmente navégaveis. Posteriormente após o ambiente devidamente construido e funcionando deverá ser realizado análises nos dados para entender qual o perfil de clientes que a empresa possui. </p>
<p> Portanto, o Desenvolvimento deste projeto ocorrerá em duas etapas. </b>
<ul>
    <li> <b>Estruturação das tabelas </b> </li>
    <li> <b> Análise de dados </b> </li>
</ul>

<hr>

<h2 id = 'estruturacao'> Estruturação dos Dados </h2>

<h4 id = 'der'> Proposta de estrutura de dados </h4>
<p> Ao analisar alguns serviços de API relacionado a consulta de CNPJs (<a href='https://www.gov.br/conecta/catalogo/apis/consulta-cnpj'>Consulta CNPJ GOV</a>, <a href='https://www.cnpj.ws/'>CNPJ.ws</a> e <a href='https://cnpja.com/'> CNPJá </a>) entendemos que todas seguem uma estrutura similar referente aos dados. Sendo assim vamos realizar um esboço do que consideramos a estrutura ideal de tabelas que se adeque ao nosso escopo.

<blockquote> <code> Para visualizar e acessar o DER (Diagrama de Entidades e Relacionamentos)</code> <a href='https://github.com/zThanael/Metadados_CNPJ/blob/main/proposta_de_estrutura_de_dados.md'><b>clique aqui </b> </a> </blockquote>

<hr>
<br>

<h2 id = 'analises'> Análise dos Dados </h2>