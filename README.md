<h2 align="center">Git studies</h2>
<h3 align="center">Aprendendo a usar comandos do git</h3>

<h3>Índice<h3/>
<ul>
    <li><a href="#1">Iniciar um novo repositório local</a></li>
    <li><a href="#2">Criar conexão com o repositório remoto</a></li>
    <li><a href="#3">Adicionar um arquivo</a></li>
    <li><a href="#4">Adicionar vários arquivos</a></li>
    <li><a href="#5">Ignorar arquivos</a></li>
    <li><a href="#6">Verificar o status das alterações</a></li>
    <li><a href="#7">Realizar um commit </a></li>
    <li><a href="#8">Enviar as alterações para o repositório</a></li>
    <li><a href="#9">Verificar histórico de atualizações</a></li>
    <li><a href="#10">Retorna para a versão anterior no git</a></li>
    <li><a href="#11">Visualizar todo o grafo de commits</a></li>
    <li><a href="#12">Criar uma branch</a></li>
    <li><a href="#13">Outra forma de criar uma branch</a></li>
    <li><a href="#14">Visualizar uma branch</a></li>
    <li><a href="#15">Acessar outra branch</a></li>
    <li><a href="#16">Fusão de duas branches</a></li>
</ul>
------------------------------------------------------------------------------------------------------------------------
<h3 id="1">Iniciar um novo repositório local</h3>

```
git init
```
<h3 id="2">Criar conexão com o repositório remoto</h3>

```
git remote add origin URL do repositorio
```
<h3 id="3">Adicionar um arquivo</h3>

```
git add nomeDoArquivo.tipo
```
<h3 id="4">Adicionar vários arquivos</h3>

```
git add .
```
<h3 id="5">Ignorar arquivos (arquivos que não serão enviados para o github)</h3>

```
touch .gitignore
```
<h3 id="6">Verificar o status das alterações</h3>

```
git status
```
<h3 id="7">Realizar um commit</h3>

```
git commit -m "descrição das alterações"
```
<h3 id="8">Enviar as alterações para o repositório</h3>

```
git push
```
<h3 id="9">Verificar histórico de atualizações</h3>

```
git reflog
```
<h3 id="10">Retorna para a versão anterior no git (uso somente quando necessário)</h3>

```
git reset --hard id do commit
```
<h3 id="11">Visualizar todo o grafo de commits</h3>

```
git log --oneline --graph --all
```
<h3 id="12">Criar uma branch</h3>

```
git branch nome_branch
```
<h3 id="13">Outra forma de criar uma branch</h3>

```
git checkout -b nome_branch
```
<h3 id="14">Visualizar uma branch</h3>

```
git branch
```
<h3 id="15">Acessar outra branch</h3>

```
git checkout nome_branch
```
<h3 id="16">Fusão de duas branches</h3>
  
```
git merge nome_branch
```
