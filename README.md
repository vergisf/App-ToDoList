<h2>LAB - Criando um app de lembretes e tarefas para IOS, utilizando Swift.</h2>
<p>O curso pode ser acessado na plataforma da <a href="https://digitalinnovation.one/">Digital Innovation One<a>.</p>

<h2>Sobre o Autor:</h2>
<p>
    <a target="_blank" rel="noopener noreferrer" href="https://github.com/vergisf/moreitens/blob/main/avatarrounded.png?raw=true"><img align="left" width="190" height="190" src="https://github.com/vergisf/moreitens/blob/main/avatarrounded.png?raw=true" data-canonical-src="https://drive.google.com/uc?export=view&amp;id=1Kn8aRAQbLZx9BejvZD2eK8kLhp8j9i5m" style="max-width:100%;"></a> 
    Sou desenvolvedor IOS, amo novos desafios e amo passar conhecimento e tambem aprender, busco sempre me informar e melhorar no que faço, tendo em mente que não sei tudo, 
    nunca vou saber tudo mas posso todos os dias melhorar mais e mais. Uma frase que carrego comigo é: <b>Ninguém é tão sábio que não tenha algo a aprender e nem tão tolo que não tenha algo pra ensinar (Blaise Pascal).</b><br/>
    Quero compartilhar com vocês um pouco de conhecimento e também aprender.
</p>
<br/><br/>
<h2>Descrição do LAB:</h2>
<p>
    O objetivo do projeto é criar um App de Tarefas/<code>To do list</code> do zero mostrando o processo de desenvolvimento usando Swift, 
    uma das linguagens de programação de maior ascensão dos últimos anos. 
    Além disto, desafiar a evolução do App e entregar uma solução mais robusta pensando sempre na melhor experiência do usuário.
</p>

<h2>Materiais de referência:</h2>
<ul>
    <li><b>Documentação Apple</b>: 
        <ul><li><a href="https://developer.apple.com/documentation/uikit/uitableview" target="_blank"> TableView</a>.</li></ul>
        <ul><li><a href="https://developer.apple.com/documentation/uikit/uidatepicker" target="_blank"> UIDatePicker</a>.</li></ul>
        <ul><li><a href="https://developer.apple.com/documentation/foundation/userdefaults" target="_blank">User Defaults</a>.</li></ul>
    </li>
    <li><b>Documentação CocoaPods</b>:
        <ul><li><a href="https://guides.cocoapods.org/" target="_blank"> CocoaPods</a>.</li></ul>
    </li>
</ul>

<h2>Aulas do desafio:</h2>
<ul>
    <li><b>Introdução</b>: 
        <ul><li>Apresentação pessoal e apresentação do desafio.</li></ul>
    <li><b>Aula 1</b>: Inicando nosso desafio
        <ul><li>Introdução ao desafio.</li></ul>
        <ul><li>Criando nosso projeto.</li></ul>
        <ul><li>Configurações básica.</li></ul>
        <ul><li>Fazendo a organização inicial do App.</li></ul>
    </li>
    <li><b>Aula 2</b>: CocoaPods
        <ul><li>Conhecendo o <a href="https://cocoapods.org/" target="_blank">CocoaPods</a> e o que ele faz.</li></ul>
        <ul><li>Utilizando o CocoaPods no projeto</li></ul>
    </li>
    <li><b>Aula 3</b>: Colocando a mão na massa
        <ul><li>Criando nossas telas.</li></ul>
        <ul><li>Criando nossas controllers.</li></ul>
        <ul><li>Conhecendo e utilizando a <a href="https://developer.apple.com/documentation/uikit/uitableview" target="_blank"> TableView</a> e suas Cells</li></ul>
        <ul><li>Criando um componente para selecionar horário</li></ul>
        <ul><li>Finalizando nosso componente de selecionar horário</li></ul>
        <ul><li>Trabalhando com <b>extensions</b> de classes nativas do projeto</li></ul>
        <ul><li>Criando as tarefas utilizando o <a href="https://developer.apple.com/documentation/foundation/userdefaults" target="_blank">User Defaults</a>.</li></ul>
        <ul><li>Editando nossas tarefas, conhecendo algumas coisas de lista no IOS.</li></ul>
        <ul><li>Excluindo nossas tarefas.</li></ul>
        <ul><li>Refatorando nosso código, utilizando o <b>Refactor do XCode</b></li></ul>
    </li>
</ul>

<h2>Desafios:</h2>
<p>
    Criamos o nosso aplicativo utilizando um dos componentes mais sensacionais e simples de usar, que seria a table view. Ela é poderosa pra muitas outras coisas
    então um dos desafios é fazer com que ela seja responsável por permitir editar, deletar uma tarefa, sem acessar uma segunda tela pra isso. No aplicativo também utilizamos
    o <a href="https://developer.apple.com/documentation/foundation/userdefaults" target="_blank">User Defaults</a> do IOS, salvando no próprio dispositivo/simulador, então
    mais um desafio é utilizar o CoreData do IOS. Ambas as documentações estão abaixo para conhecer melhor sobre:
</P>
<ul><li><a href="https://developer.apple.com/documentation/uikit/uitableview" target="_blank"> TableView</a>: é uma tabela no iOS que exibem linhas de conteúdo de rolagem vertical em uma única coluna. Cada linha da tabela contém uma parte do conteúdo do seu aplicativo. A <b>tableview</b> possuí um estado de edição, permitindo o desenvolvedor utilizar delegates e animações nativas, podendo utilizar isso para edição, exclusão ou customizar conforme necessário.</li></ul>
<ul><li><a href="https://developer.apple.com/documentation/coredata" target="_blank">CoreData</a>: é uma interface para o banco de dados de padrões do usuário, onde você armazena pares de valores-chave persistentemente durante as inicializações de seu aplicativo.</li></ul>
