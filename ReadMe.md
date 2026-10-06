Trânsito agora (Lisboa e Porto)
Mapa de trânsito em tempo real. Dados: TomTom Traffic (cores por tile + velocidade por estrada).
Local
        1.      Crie uma chave em https://developer.tomtom.com e cole-a em config.js.
        2.      python3 -m http.server e abra http://localhost:8000.
GitHub Pages
        1.      Envie para main. Em Settings > Pages, Source: GitHub Actions.
        2.      Em Settings > Secrets and variables > Actions, crie o segredo TOMTOM_KEY.
        3.      No painel da TomTom, restrinja a chave ao domínio https://<utilizador>.github.io.
A chave fica visível no navegador, por isso a restrição é obrigatória.
Verifique os limites diários do seu plano TomTom. Para muito tráfego, ponha um proxy à frente da API.
Os pontos da lista estão em CITIES no index.html e ligam-se à estrada mais próxima.
