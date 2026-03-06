<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Mochila Escolar Digital</title>

<style>

body{
font-family: Arial;
background:#eef2f7;
margin:0;
}

header{
background:#2d5aa0;
color:white;
text-align:center;
padding:20px;
}

.container{
padding:20px;
max-width:900px;
margin:auto;
}

.addMateria{
display:flex;
gap:10px;
margin-bottom:20px;
}

input{
padding:10px;
border-radius:6px;
border:1px solid #ccc;
flex:1;
}

button{
padding:10px;
border:none;
border-radius:6px;
background:#2d5aa0;
color:white;
cursor:pointer;
}

button:hover{
background:#1f4175;
}

.materia{
background:white;
padding:15px;
margin-bottom:15px;
border-radius:10px;
box-shadow:0 2px 6px rgba(0,0,0,0.1);
}

.materia h2{
display:flex;
justify-content:space-between;
align-items:center;
}

ul{
list-style:none;
padding:0;
}

li{
display:flex;
justify-content:space-between;
padding:6px;
border-bottom:1px solid #eee;
}

.concluida{
text-decoration:line-through;
color:gray;
}

.tarefaAdd{
display:flex;
gap:10px;
margin-top:10px;
}

.deleteBtn{
background:red;
}

</style>

</head>

<body>

<header>
<h1>🎒 Minha Mochila Escolar</h1>
<p>Organize suas matérias e tarefas</p>
</header>

<div class="container">

<div class="addMateria">
<input id="novaMateria" placeholder="Nova matéria">
<button onclick="addMateria()">Adicionar</button>
</div>

<div id="materias"></div>

</div>

<script>

let dados = JSON.parse(localStorage.getItem("mochila")) || {
"Português":[],
"Matemática":[],
"História":[],
"Geografia":[],
"Ciências":[],
"Inglês":[],
"Artes":[],
"Educação Física":[]
}

function salvar(){
localStorage.setItem("mochila",JSON.stringify(dados))
}

function render(){

const area = document.getElementById("materias")
area.innerHTML=""

for(let materia in dados){

let tarefas = dados[materia]

let div = document.createElement("div")
div.className="materia"

div.innerHTML = `
<h2>
${materia}
<button class="deleteBtn" onclick="deleteMateria('${materia}')">Excluir</button>
</h2>

<ul>
${tarefas.map((t,i)=>`
<li class="${t.done ? 'concluida':''}">
<span onclick="toggle('${materia}',${i})">${t.nome}</span>
<button onclick="deleteTarefa('${materia}',${i})">❌</button>
</li>
`).join("")}
</ul>

<div class="tarefaAdd">
<input id="input-${materia}" placeholder="Nova tarefa">
<button onclick="addTarefa('${materia}')">Adicionar</button>
</div>
`

area.appendChild(div)

}

salvar()

}

function addMateria(){

let nome = document.getElementById("novaMateria").value

if(nome && !dados[nome]){

dados[nome]=[]
document.getElementById("novaMateria").value=""
render()

}

}

function deleteMateria(materia){

if(confirm("Excluir matéria?")){

delete dados[materia]
render()

}

}

function addTarefa(materia){

let input = document.getElementById(`input-${materia}`)
let texto = input.value

if(texto){

dados[materia].push({nome:texto,done:false})
input.value=""
render()

}

}

function deleteTarefa(materia,index){

dados[materia].splice(index,1)
render()

}

function toggle(materia,index){

dados[materia][index].done = !dados[materia][index].done
render()

}

render()

</script>

</body>
</html>
