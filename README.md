# Ficha de Personagem – RPG (layout medieval)

Ficha interativa de RPG com sistema próprio. Funciona direto no navegador, sem instalação.

## Recursos

- Status: Vida (PV), Sanidade (SAN) e Mana (PM)
- Raças, idades e classes com bônus automáticos
- Atributos e perícias com controle de pontos
- Rolador de dados (atributos, perícias e magias com dano)
- Armas de combate: catálogo para adicionar com um toque (ou arma em branco), rolagem de dano e controle de munição com recarga
- Magias com custo em PM e dano
- Condições, defesa calculada por armadura e AGI, equipamentos com peso total
- Botão de descansar (restaura PV, SAN e PM)
- Diário de sessão e anotações
- Vários personagens salvos no mesmo navegador
- Salvamento automático no navegador
- Exportar e importar a ficha em arquivo `.json`

## Como publicar no GitHub Pages

1. Crie um repositório e envie `index.html` e `README.md` para a raiz.
2. Vá em **Settings → Pages**.
3. Em **Branch**, escolha `main` e a pasta `/ (root)`, e salve.
4. Após um ou dois minutos, a ficha estará em `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

## Observação

Os dados ficam salvos apenas no navegador de quem usa. Use **Exportar** para guardar uma cópia da ficha.

## Escudo do Mestre

- O mestre abre `escudo-mestre.html` e mantém a página aberta durante a sessão. Ela mostra um código de sala.
- Cada jogador digita o código na ficha, na seção **Escudo do Mestre**, e aperta **Conectar**.
- O escudo mostra a ficha de cada jogador em tempo real (vida, sanidade, mana, defesa, atributos e condições) e um histórico de rolagens que todos veem.
- O mestre pode ajustar a vida, a sanidade e a mana dos jogadores, cadastrar criaturas e rolar dados.
- A conexão é direta entre os aparelhos (PeerJS) e precisa de internet.
