# Criando um phishing no Kali Linux

O repositório é um guia passo a passo para ajudar você a criar um ataque de phishing em sua própria<br>
rede ou em um ambiente de teste. Usando a ferramenta Setoolkit, você aprenderá como projetar e executar<br>
um ataque eficaz, com exemplos práticos e instruções claras.<br>

Este repositório foi criado com o objetivo de educar os usuários sobre as técnicas de phishing e como se<br>
proteger contra elas. Ele é uma ótima opção para estudantes, profissionais de segurança cibernética ou qualquer<br>
pessoa interessada em aprender como detectar e evitar esse tipo de ameaça.<br>

O guia inclui informações detalhadas sobre a configuração do ambiente, como instalar e usar o Setoolkit, como<br>
projetar um e-mail de phishing eficaz e muito mais. Todos os passos são cuidadosamente explicados e ilustrados<br>
com capturas de tela para facilitar o acompanhamento.<br>

Com o repositório "Criando um phishing com Kali Linux usando Setoolkit", você aprenderá as habilidades necessárias<br>
para identificar e evitar ataques de phishing, além de adquirir conhecimentos valiosos sobre segurança cibernética.<br>

### Virtual Machine
É recomendado que você faça isso em casa apenaspara testes, isso pode ser considerado uma técnica ilegal caso você<br>
tente aplicar em alguma rede corporativa ou sem mera autorização do proprietário"<br>

Inicialmnente é interessante modificar a rede em que a Máquina Virtual do Kali Linux está trabalhando, normalmente<br>
eles começam trabalhando em <b>NAT</b> nesse caso você precisará modificar para ela trabalhar em <b>Modo Bridge</b><br>

<ul>Abrir o Virtual Box ou VM Ware que você utiliza</ul>
<ul>Selecione a opção <b>Configurações</b></ul>
<ul>Selecione a opção <b>Rede</b></ul>
<ul>Selecione o adaptador em que seu Kali Linux está rodando a internet</ul>
<ul>Modifique a opção que está escrito <b>Conectado a: </b> para <b>Placa em Modo Bridge</b></ul>
<ul> <b> Salvar </b> </ul>


### Kali Linux
É Necessário acesso ao root para executar essa ferramenta, você consegue através do comando:
<ul><b>sudo su</b></ul>
<ul><b>Digite sua Senha</b></ul><br>

Agora vamos executar a ferramenta:
<ul><b>setoolkit</b></ul>

1° passo é escolher o tipo de ataque que queremos fazer, você escolherá:
<ul><b>1) Social-Engineering Toolkit</b></ul>

2° Passo é escolher de onde vai partir o seu ataque, você escolherá:
<ul><b>2) Website attack Vectors</b></ul>

3° Passo é como o ataque será feito, você escolherá:
<ul><b>3) Credentials Harvester Attack Method</b></ul>

4° Passo - Agora você escolherá a opção que irá clonar um site, que será a opção:
<ul><b> 2 Website Cloner</b></ul>

5° Passo - Como irá rodar um servidor no seu Kali Linux ele irá pedir o IP da máquina, como ele já sugere<br>
um, porquê ele já reconhece, então você já pode teclar <b>Enter</b>.

6° Passo - Agora informe o site a ser clonado, o exemplo que irei mostrar é o do Facebook "https://www.facebook.com"<br>
copia e cola lá no terminal do Kali Linux para o toolkit saber qual o website a clonar, lembrando que o htttp deve está também<br>
e tecle <b>Enter</b>.

7° Passo - Agora você pode testar colocando o IP da sua máquina que foi mensionado em uma etapa falada acima, assim <br>
que a vítima entrar nesse site e tentar logar, dentro do Kali Linux, irá aparecer reports, principalmente o usuário e senha.
