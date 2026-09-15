
// Pegando os elementos do HTML

let nome = document.getElementById('text')
let email = document.getElementById('email')
let number = document.getElementById('number')
let botao = document.getElementById('botao')

let h2 = document.getElementById('textinsert')
let h3 = document.getElementById('emailinsert')
let h4 = document.getElementById('numberinsert')


// Função executada ao clicar no botão

function inserir() {

    // Pegando os valores digitados

    let nomeValor = nome.value
    let emailValor = email.value
    let numberValor = number.value


    // Exibindo os dados na página

    h2.textContent = nomeValor
    h3.textContent = emailValor
    h4.textContent = numberValor


    // Salvando os dados no navegador

    localStorage.setItem('nome', nomeValor)
    localStorage.setItem('email', emailValor)
    localStorage.setItem('number', numberValor)
}


// Evento do botão

botao.addEventListener('click', inserir)


// Recuperando os dados salvos
// quando a página for aberta ou atualizada

window.addEventListener('load', function() {

    let nomeSalvo = localStorage.getItem('nome')
    let emailSalvo = localStorage.getItem('email')
    let numberSalvo = localStorage.getItem('number')


    // Se existir nome salvo

    if (nomeSalvo !== null) {

        nome.value = nomeSalvo
        h2.textContent = nomeSalvo

    }


    // Se existir e-mail salvo

    if (emailSalvo !== null) {

        email.value = emailSalvo
        h3.textContent = emailSalvo

    }


    // Se existir número salvo

    if (numberSalvo !== null) {

        number.value = numberSalvo
        h4.textContent = numberSalvo

    }

})
