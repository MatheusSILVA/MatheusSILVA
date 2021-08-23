
    - cron : " * * / 12 * * * "
  workflow_dis
empregos :
  construir :
    nome : Trabalhos para atualizar dados
    roda em : ubuntu-mais recente
    passos :
      # Animação de cobra
      - usa : Platane / snk @ master
        id : snake-gif
        com :
          github_user_name :   ELLEN2121
          svg_out_path : dist / github-Contribution-grid-snake.svg

      - usa : crazy-max/ghaction-github-pages@v2.1.3
        com :
          target_branch : output
          build_dir : dist
        env :
          GITHUB_TOKEN : $ {{secrets.GITHUB_TOKEN}}

