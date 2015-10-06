<h2>Fazendo o primeiro Push</h2>

<p>Criei um diretório na minha máquina local chamado "primeiropush_escola"</p>

<p style="background: #f5f5f5;">$ mkdir primeiropush_escola</p>

<p>acessei esse diretório e dentro executei o seguinte comando:</p>

<p style="background: #f5f5f5;">$ git init</p>

<p>logo após criei os arquivos do meu projeto com o conteúdo.<br />
E criei também o README.md</p> 
<p style="background: #f5f5f5;">$ touch README.md</p>

<p>Instalei o Markdown, e com ele editei o arquio README.md inserindo as informações necessárias</p>

<p>Após isso usei: <span style="background: #f5f5f5">$ git add .</span>,  para adicionar os arquivos para a fase de estarem prontos para entrar no controle de versão</p>

<p>E depois: <span style="background: #f5f5f5">$ git commit</span>. Ele abriu um arquio te texto no terminal e adicionei algumas informações no arquivo
</p>
<p>Acessei minha conta no Github e criei um repositório, <i>Repositories/new</i>, e coloquei o nome primeropush_escola</p>
<p style="background: #000; color: #fff; padding: 20px">
<span style="background: #000; font-size: 14px;">resultado</span><br />
…or create a new repository on the command line

echo "# primeiropush_escola" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/edimaurolima/primeiropush_escola.git
git push -u origin master
</p>
<p>Para configurando o repositorio remoto local execuetei:</p>
<p style="background: #f5f5f5;">$ git remote add origin https://github.com/edimaurolima/primeiropush_escola.git</p>
<p>E por último o comando do PUSH</p>
<p style="background: #f5f5f5;">$ git push origen master</p>

<p>Prontinho</p>