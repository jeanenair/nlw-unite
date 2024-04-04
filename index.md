const participante = {
 nome: "Jeane Nair", 
 email: "jeanenair@gmail.com",
 dataInscricao: new Date(2024, 2, 22, 19, 20), 
 dataCheckIn: new Date (2024, 2, 25, 22, 00)
}
// array
let participantes = [
  { 
   nome: "Jeane Nair", 
   email: "jeanenair@gmail.com",
   dataInscricao: new Date(2024, 2, 22, 19, 20), 
   dataCheckIn: new Date (2024, 2, 25, 22, 00)
  },
]


  //ESTRTURA DE REPETIÇÃO - loop
  for(let participante of participantes) {
    output = output + criarNovoParticipante(participante)
  }
  //FAÇA O PROGRAMA DE REPETIÇÃO ENQUANTO TIVER PESSOAS NA LISTA 