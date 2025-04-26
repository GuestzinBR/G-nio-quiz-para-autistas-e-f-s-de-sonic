# G-nio-quiz-para-autistas-e-f-s-de-sonic
Jogo recomendado para quem gosta de sonic e é autista. 




const perguntas = [
  {
    "pergunta": "Nível 1: Qual é a cor principal do Sonic?",
    "opcoes": ["Vermelho", "Azul", "Verde"],
    "resposta": 1
  },
  {
    "pergunta": "Nível 2: Quem é o maior rival do Sonic?",
    "opcoes": ["Knuckles", "Shadow", "Tails"],
    "resposta": 1
  },
  {
    "pergunta": "Nível 3: Como se chama o vilão que sempre tenta capturar os animais?",
    "opcoes": ["Robotnik", "Bowser", "Eggface"],
    "resposta": 0
  },
  {
    "pergunta": "Nível 4: Em que jogo apareceu o Super Sonic pela primeira vez?",
    "opcoes": ["Sonic 1", "Sonic 2", "Sonic CD"],
    "resposta": 1
  },
  {
    "pergunta": "Nível 5: Qual personagem é uma raposa de duas caudas?",
    "opcoes": ["Shadow", "Tails", "Knuckles"],
    "resposta": 1
  },
  {
    "pergunta": "Nível 6: Qual é o nome do amigo vermelho do Sonic?",
    "opcoes": ["Knuckles", "Tails", "Amy"],
    "resposta": 0
  },
  {
    "pergunta": "Nível 7: Em qual jogo Sonic se encontra com o seu amigo Shadow?",
    "opcoes": ["Sonic Adventure 2", "Sonic Heroes", "Sonic Forces"],
    "resposta": 0
  },
  {
    "pergunta": "Nível 8: Quem é a amada do Sonic?",
    "opcoes": ["Amy", "Tails", "Rouge"],
    "resposta": 0
  },
  {
    "pergunta": "Nível 9: Qual é o nome da irmã de Knuckles?",
    "opcoes": ["Tikal", "Rouge", "Maria"],
    "resposta": 0
  },
  {
    "pergunta": "Nível 10: Como se chama a versão robô de Sonic?",
    "opcoes": ["Metal Sonic", "Silver Sonic", "Tailsbot"],
    "resposta": 0
  },
  {
    "pergunta": "Nível 11: Qual é o nome do vilão que usa um robô gigante em Sonic 3?",
    "opcoes": ["Metal Sonic", "Dr. Robotnik", "Silver"],
    "resposta": 1
  },
  {
    "pergunta": "Nível 12: Qual é o nome do companheiro de Sonic que é um ouriço roxo?",
    "opcoes": ["Knuckles", "Silver", "Espio"],
    "resposta": 2
  },
  {
    "pergunta": "Nível 13: Em que jogo Sonic vai ao espaço?",
    "opcoes": ["Sonic Adventure", "Sonic CD", "Sonic Rush"],
    "resposta": 1
  },
  {
    "pergunta": "Nível 14: O que Sonic sempre diz quando está em apuros?",
    "opcoes": ["Vou vencer!", "Não me deixe!", "Eu sou o melhor!"],
    "resposta": 0
  },
  {
    "pergunta": "Nível 15: Qual é o nome da cidade onde Sonic nasceu?",
    "opcoes": ["Station Square", "Green Hill Zone", "Sonic City"],
    "resposta": 1
  },
  {
    "pergunta": "Nível 16: Quem é o vilão que aparece em Sonic Forces?",
    "opcoes": ["Metal Sonic", "Eggman", "Infinite"],
    "resposta": 2
  },
  {
    "pergunta": "Nível 17: Em qual jogo Sonic se une com outros heróis para salvar o mundo?",
    "opcoes": ["Sonic Heroes", "Sonic Unleashed", "Sonic Generations"],
    "resposta": 0
  },
  {
    "pergunta": "Nível 18: Qual personagem é conhecido por ser o espião da equipe Chaotix?",
    "opcoes": ["Vector", "Espio", "Charmy"],
    "resposta": 1
  },
  {
    "pergunta": "Nível 19: O que Sonic mais ama fazer?",
    "opcoes": ["Correr", "Lutar", "Nadar"],
    "resposta": 0
  },
  {
    "pergunta": "Nível 20: Qual é o nome da versão robô de Sonic?",
    "opcoes": ["Metal Sonic", "Silver Sonic", "Tailsbot"],
    "resposta": 0
  },
  {
    "pergunta": "Nível 21: Qual é o nome do mundo onde Sonic começa suas aventuras?",
    "opcoes": ["Earth", "Mobius", "Green Hill"],
    "resposta": 1
  },
  {
    "pergunta": "Nível 22: O que Sonic e Tails usam para viajar no tempo em Sonic CD?",
    "opcoes": ["Time Stone", "Time Travel Machine", "Time Twister"],
    "resposta": 0
  },
  {
    "pergunta": "Nível 23: Em qual jogo Sonic encontra Blaze?",
    "opcoes": ["Sonic Rush", "Sonic Unleashed", "Sonic 06"],
    "resposta": 0
  },
  {
    "pergunta": "Nível 24: Qual é o nome do primo de Sonic?",
    "opcoes": ["Tails", "Knuckles", "Mighty"],
    "resposta": 2
  },
  {
    "pergunta": "Nível 25: Qual é o nome da equipe que Sonic e seus amigos formam?",
    "opcoes": ["Team Sonic", "Team Heroes", "Team Freedom"],
    "resposta": 0
  },
  {
    "pergunta": "Nível 26: Quem é o vilão que usa uma pedra chamada 'Chaos Emerald'?",
    "opcoes": ["Metal Sonic", "Eggman", "Shadow"],
    "resposta": 1
  },
  {
    "pergunta": "Nível 27: Como se chama o jogo onde Sonic se transforma em um Werehog?",
    "opcoes": ["Sonic Unleashed", "Sonic Forces", "Sonic Adventure 2"],
    "resposta": 0
  },
  {
    "pergunta": "Nível 28: Qual personagem tem uma paixão por joias preciosas?",
    "opcoes": ["Amy", "Rouge", "Blaze"],
    "resposta": 1
  },
  {
    "pergunta": "Nível 29: Quem é o robô fiel ajudante de Dr. Eggman?",
    "opcoes": ["Metal Sonic", "Eggman Nega", "Orbot"],
    "resposta": 2
  },
  {
    "pergunta": "Nível 30: O que Sonic sempre diz ao derrotar um inimigo?",
    "opcoes": ["Fui mais rápido!", "Isso é fácil!", "Não adianta tentar!"],
    "resposta": 0
  },
  {
    "pergunta": "Nível 31: Qual é a origem do nome de 'Sonic'?",
    "opcoes": ["Porque ele é rápido", "Porque ele é azul", "Porque ele tem um som agudo"],
    "resposta": 0
  },
  {
    "pergunta": "Nível 32: Quem é o primeiro amigo que Sonic encontra em suas aventuras?",
    "opcoes": ["Knuckles", "Amy", "Tails"],
    "resposta": 2
  },
  {
    "pergunta": "Nível 33: O que Sonic e Tails fazem para se enfrentar contra Eggman?",
    "opcoes": ["Correm rápido", "Usam os Chaos Emeralds", "Voam com o Tornado"],
    "resposta": 2
  },
  {
    "pergunta": "Nível 34: Quem é o líder da equipe Chaotix?",
    "opcoes": ["Espio", "Vector", "Charmy"],
    "resposta": 1
  },
  {
    "pergunta": "Nível 35: O que Sonic nunca deixa de fazer nas suas aventuras?",
    "opcoes": ["Correr", "Lutar", "Ajudar seus amigos"],
    "resposta": 2
  },
  {
    "pergunta": "Nível 36: Quem é o vilão que é conhecido como 'the ultimate lifeform'?",
    "opcoes": ["Shadow", "Sonic", "Knuckles"],
    "resposta": 0
  },
  {
    "pergunta": "Nível 37: Como se chama o mundo onde Sonic mora?",
    "opcoes": ["Mobius", "Green Hill", "Earth"],
    "resposta": 0
  },
  {
    "pergunta": "Nível 38: Qual é o nome da irmã de Tails?",
    "opcoes": ["Marine", "Amy", "Blaze"],
    "resposta": 0
  },
  {
    "pergunta": "Nível 39: Quem é o aliado de Sonic que tem um par de luvas amarelas?",
    "opcoes": ["Knuckles", "Sonic", "Tails"],
    "resposta": 0
  },
  {
    "pergunta": "Nível 40: Quem é o vilão que quer controlar o mundo com uma máquina gigantesca?",
    "opcoes": ["Eggman", "Silver", "Shadow"],
    "res
