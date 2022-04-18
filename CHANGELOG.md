# Changelog

Todas as alterações serão documentadas neste arquivo

Formato baseado em [Keep a Changelog](http://keepachangelog.com/en/1.0.0/),
e [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [0.2.4] - 2022-04-18

### Added
- Sistema de criação de circuitos para corrida.
- Timer para não fica usando meth e colete toda hora.
- Sistema de procurado no tablet policial
- Sistema de porte de arma no tablet policial.
- Novo banco através do celular.
- Bloqueio em algumas funcionalidades  quando está procurado ou em repouso.
- Sounds em toda ações envolvendo dinheiro no tablet.
- Opção de alugar carro vip por dinheiro do jogo por 30 dias.
- Opção de colocar e retirar a peça de roupa especifica no F9.

### Changed
 - Alguns efeitos das drogas.
 - Sistema de procurado e repouso.
 - Sistema de salario já cai automaticamente no banco.
 - Sistema de tablet.
 - Sistema de garagem e novo sistema de salvamento.
 - Sistema impound e towdriver.
 - Layout garagem para o do servidor.
 - Sistema de banimento permanente para a quantidade de dias, o banimento é retirado automaticamente após o total de dias expirar. 
 - Sistema de casa
 - Sistema de morte e layout
 - Organizados o savalmento de roupa no F9
 - Sistema de spawn servidor reformulado, corrigindo que toda hora aparecia onde você queria nascer sendo que deveria aparecer apenas uma vez após o rr.
 - Melhorado algumas threads evitando loading ao carregar o personagem.

### Fixed
- Construção pescador sandy shores.
- Optimização sistema de atm.
- Sistema de multa.
- Comando /e pano e /e pano2 agora é possível limpar o veículo.
- Verificar placa, registrar carro e deter carro.
- Sistema de desmanche com o novo sistema de garagem.
- Fix trunkchest.
- Visual dos logs ( Discord ).
- Sistema Test drive.
- Target com as opções trocar placa, arrombar portas malas e entrar no portas malas. 
- Comandos admin
- Item adrenaline

### Removed
 - Removido tudo relacionado ao serial.

## [0.2.3] - 2022-04-08

### Added
- Efeito hover no target
- Drift pela tecla SHIFT
- Set TheLost MC designado a função de venda de munições
- Set Mayans designado a função de venda de munições
- Bau, Crafting e rota do ilegal para TheLost MC
- Bau, Crafting e rota do ilegal para Mayans
- Set Vanilla designado a função de lavagem de dinheiro
- Bau e crafting para o Vanilla
- Lavagem de dinheiro de 50% por npc necessita de pendrive.
- Crafting de itens ilegais como colete, lockpick e c4.
- Roubo ao caixa registradora com lock pick
- Corrida ilegal que precisa de ticket, caso você inicia sem ticket não tem tempo e nem chama policia.
- Roubo ao carro forte.

### Changed
- Sistema de arma na mão, agora as munições são salvas no banco de dados.
- Layout de todos os vrp.request do servidor. (Caixa onde você tem que aceitar com Y ou negar com N)
- Sistema de roubo de caixa eletronico agora necessita de C4
- Organizado pasta "Roubos"
- Sistema de barbershop e foi alterado a maneira de salvar evitando perdas.
- Sistema de skinshop e foi alterado a maneira de salvar evitando perdas.
- Sistema de tattoos e foi alterado a maneira de salvar evitando perdas.
- Optimização Tela de spawn.
- Layout tela de spawn, barbershop, skinshop e tattoos

### Fixed
- Animação duplicada ao pegar arma pela primeira vez após rr
- Favela01, Favela02, Favela03
- Mapa TheLost
- Sistema de roubos
- Salvamento do sexo da pessoa no banco de dados
- Função gsrkit para ver se foi cometido crime

### Removed
- Sets de mafias e outros ilegais que não estavam sendo utilizados.
- Toda parte de roubo do target e eletronics
- Status de fome, sede e stress que não estavam sendo utilizados no inventory

## [0.2.2] - 2022-03-17

### Added
- Condições no emprego de caminhoneiro players normais uma vez a cada rr e players vips 2 vezes a cada rr (Verificar os vips e condições depois.)
- Mais um farm para todas favela (Farm parado)
- Todos os carros vips para aluguel na concessionária
- Proteção no bau para quando estiver sem espaço ele não atualizar e não move nada.
- Verificação para saber se tem dinheiro na mão, caso não tenha o desconto vai ser no banco automaticamente.

### Changed
- Layout do baú. 
- Layout da garagem.
- Emprego de caminhoneiro ao inves de receber dinheiro agora recebe material para vender. 

### Fixed
- Valor cobrado na retirada de veículos das garagens
- Efeitos ao usar drogas 
- Pagamento do caminhoneiro agora deleta o veiculo.
- Farm de rota de todas as favelas.
- Crafting das favelas
- Baú das favelas.
- Favela morrodopiolho
- Lojas ilegais
- Bug ao pegar qualquer item do baú e sumir

### Removed
- Sets do ilegal sem função
- Guetos
- Peds sem funcionalide

## [0.2.1] - 2022-03-14

### Added
- Novo Chat
- Chat OOC
- Função /me para players
- Função usar baralho
- Log de chatkill (Discord)
- Comandos prioridade na fila (Admin)
- Comandos remover personagem (Admin)
- Informações servidor no Discord do player que estiver jogando
- Função F7 para ver ID do player

### Changed
-

### Fixed
- Roubo de casas
- Sistema de girar dado
- Notify debug

### Removed
- Permissões grupo LastTrain 

## [0.2.0] - 2022-03-11

### Added
- Sistema de roubo de casas

### Changed
- Sistema de casas 
- Sistema de Roupa de Mergulho

### Fixed
- Som de dinheiro ao tentar comprar em lojas que apenas vendem
- Fix no baú da casa 

### Removed

## [0.1.9] - 2022-03-10

### Added
- Emprego de carteiro

### Changed

### Fixed
- Emprego de caçador
- Emprego de pescador

### Removed
- Emprego de jornaleiro
- Removido r34 lado direito estava bugado.

## [0.1.8] - 2022-03-05

### Added

### Changed
- O sistema exigia lockpick para começar a desmancha, agora você iniciar o desmanche e pegar a caixa de ferramentas, após que o desmanche for concluido a caixa será removida automaticamente. 

### Fixed

### Removed

## [0.1.7] - 2022-03-04

### Added
- Notify não está com serviço iniciado no emprego de caminhoneiro
- Emprego Jornaleiro
- Peds que faltavam
- Blips de todos os bancos no mapa
- Animação de cair ao sair do porta-malas

### Changed
- Emprego de lixeiro
- Sistema Desmanche alterado para o nosso autoral

### Fixed
- Notify bancos

### Removed

## [0.1.6] - 2022-03-03

### Added
- Add animação algemar

### Changed

### Fixed
- Fix em todos os sons 
- Chapéu permanecia ao remover roupas através do F9
- Sistema de recarga todas as armas
- Barberia seta de próximo não funcionava 
- Locais de serviços presídio

### Removed

## [0.1.5] - 2022-02-25

### Added
- Npc de venda de drogas em todas as favelas

### Changed
- Emprego guincho
- Registro emprego Guincho
- Sistema venda de drogas
- Item dollarsz para dollarsz
- Reduzido tempo para aparecer chamado venda de drogas

### Fixed
- Notify jobs
- Peds favelas

### Removed
- Sistema de pets
- Comercialização do F9
- Emprego Colheita

## [0.1.4] - 2022-02-24

### Added

### Changed
- Sistema roubo npc
- Coloração interface ATM

### Fixed
- Sessão mochila na loja de roupa 
- Local inicio test drive 
- Controle de velocidade dos carros
- Ação F9 remover chapéu e máscara
- Todos os notifiy request 
- Fix notify ATM

### Removed

## [0.1.3] - 2022-02-23

### Added
- Tuning fora da bennys para veículos que não entram no galpão 
- Peds garagem delegacia, hospital, bennys
- Trancas portas dp, hp, bennys, mecanica

### Changed
- Mudança HUD para melhor visualização

### Fixed
- Target em alguns caixa eletronicos
- Checar porta-mala (F9)
- Loja de tatuagens
- Gasolina bugada na hud ( não descia e nem sincronizava outros players )
- Cobrança de taxa de veiculos várias vezes.

### Removed
- Ações botões 1 ao 9
- Relógio hud
- Algemar e segurar admin

## [0.1.2] - 2022-02-22

### Added
- Blips garagem Delegacia Nova, Hospital Novo, Bennys Nova
- Blips elevador delegacia e hospital
- Blip tuning Bennys

### Changed
- Organização de mapas e empregos

### Fixed

- Target Lasttrain
- Target serviço policia e hospital
- Icones mapa ( novas mecanicas, hospital, delegacia )
- Todos os mapas que estavam invisiveis

### Removed


## [0.1.1] - 2022-02-17

### Added
- Opção finalizar target Caminhoneiro

### Changed
- Posicionamento HUD de acordo com resolução
- Diminuído tempo para fome e sede

### Fixed
- Emprego caminhoneiro agora tem como finalizar a rota
- Função F9 (Rebocar) para emprego de Guincho

### Removed
-  Todos os empregos, icones, garagens de serviço do Norte 
-  Todos os mapas que não estavam sendo utilizados


## [0.1.0] - 2022-02-16

### Added
- Progressbar roubo de carro e de pedestres

### Changed
- Posição da rua no HUD

### Fixed
- Sistema de uniformes corrigidos
- Sistema de roubo ao veiculo e npcs quando o npc morria
- Roubo de carro armado
- Roubo de pedestres
- Notify roubo de carro
- Roubo de carro notificando a policia
- Notify taxi
- Taxas conc tablet
- Farmácias
- Relógio e radio da HUD

### Removed
