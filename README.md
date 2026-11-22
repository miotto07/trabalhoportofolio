# TRABALHO-PORTF-LIO-EDUARDO-FERREIRA-MIOTTO-
MEU PORTFÓLIO
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Portfólio acadêmico de Eduardo Ferreira Miotto, estudante de Ciência de Dados na Fatec Adamantina.">
  <title>Eduardo Ferreira Miotto | Portfólio</title>
  <style>
    :root {
      --bg: #0b1220;
      --panel: #111c2e;
      --panel-soft: #16243a;
      --text: #edf3fb;
      --muted: #a9b8cc;
      --accent: #63d6b1;
      --accent-dark: #183f3b;
      --line: rgba(210, 228, 245, .13);
      --max: 1050px;
    }
    * { box-sizing: border-box; }
    html { scroll-behavior: smooth; }
    body {
      margin: 0;
      font-family: Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
      background:
        radial-gradient(ellipse at 85% 5%, rgba(55, 120, 119, .20), transparent 34rem),
        var(--bg);
      color: var(--text);
      line-height: 1.65;
    }
    a { color: var(--accent); text-decoration: none; }
    a:hover { text-decoration: underline; }
    .wrap { width: min(var(--max), calc(100% - 40px)); margin: 0 auto; }
    header { padding: 76px 0 58px; border-bottom: 1px solid var(--line); }
    .eyebrow {
      display: inline-flex; align-items: center; gap: 9px;
      color: var(--accent); font-size: .78rem; font-weight: 800;
      letter-spacing: .14em; text-transform: uppercase;
    }
    .eyebrow::before { content: ""; width: 24px; height: 2px; background: var(--accent); }
    h1 { font-size: clamp(2.5rem, 7vw, 5rem); line-height: 1.04; letter-spacing: -.055em; margin: 22px 0 14px; }
    .subtitle { color: var(--muted); font-size: clamp(1rem, 2.5vw, 1.2rem); max-width: 680px; margin: 0; }
    .meta { display: flex; flex-wrap: wrap; gap: 10px; margin-top: 28px; }
    .tag {
      border: 1px solid var(--line); border-radius: 999px;
      padding: 7px 13px; color: #d8e5f2; background: rgba(255,255,255,.035);
      font-size: .88rem;
    }
    main { padding: 54px 0 70px; }
    .section-heading { margin-bottom: 24px; }
    .section-heading p { color: var(--muted); margin: 7px 0 0; }
    h2 { font-size: clamp(1.65rem, 4vw, 2.25rem); letter-spacing: -.035em; margin: 0; }
    .project-intro {
      padding: 27px; border-radius: 20px; border: 1px solid var(--line);
      background: linear-gradient(135deg, rgba(99,214,177,.10), rgba(17,28,46,.92) 55%);
      margin-bottom: 18px;
    }
    .project-label { color: var(--accent); font-size: .76rem; font-weight: 800; letter-spacing: .12em; text-transform: uppercase; }
    h3 { font-size: 1.25rem; margin: 8px 0 8px; }
    .project-intro p, .card p { color: var(--muted); margin: 0; }
    .grid { display: grid; grid-template-columns: repeat(2, minmax(0, 1fr)); gap: 16px; }
    .card {
      padding: 24px; border-radius: 18px; background: var(--panel);
      border: 1px solid var(--line); min-height: 190px;
    }
    .number { color: var(--accent); font-size: .78rem; font-weight: 800; letter-spacing: .12em; }
    .card h3 { margin-top: 9px; }
    .note {
      margin-top: 18px; padding: 17px 20px; border-left: 3px solid var(--accent);
      background: rgba(99,214,177,.07); border-radius: 0 12px 12px 0;
      color: var(--muted); font-size: .93rem;
    }
    .about { margin-top: 54px; display: grid; grid-template-columns: 1fr 1fr; gap: 22px; }
    .about-box { padding: 24px; background: var(--panel-soft); border: 1px solid var(--line); border-radius: 18px; }
    .about-box p { color: var(--muted); margin-bottom: 0; }
    footer { border-top: 1px solid var(--line); padding: 30px 0 38px; color: var(--muted); }
    .footer-inner { display: flex; flex-wrap: wrap; justify-content: space-between; gap: 16px; align-items: center; }
    .footer-name { color: var(--text); font-weight: 700; }
    @media (max-width: 680px) {
      header { padding: 55px 0 42px; }
      .grid, .about { grid-template-columns: 1fr; }
      .card { min-height: 0; }
      .project-intro { padding: 22px; }
      main { padding-top: 40px; }
    }
  </style>
</head>
<body>
  <header>
    <div class="wrap">
      <div class="eyebrow">Portfólio acadêmico</div>
      <h1>Eduardo Ferreira Miotto</h1>
      <p class="subtitle">Estudante de Ciência de Dados na Fatec Adamantina, com interesse em compreender como os dados podem ajudar a interpretar situações reais — inclusive no esporte.</p>
      <div class="meta">
        <span class="tag">Ciência de Dados</span>
        <span class="tag">Fatec Adamantina</span>
        <span class="tag">4º Termo</span>
      </div>
    </div>
  </header>

  <main class="wrap">
    <section aria-labelledby="projeto">
      <div class="section-heading">
        <h2 id="projeto">Projeto em destaque</h2>
        <p>Um tema acadêmico que conecta tecnologia, informação e futebol.</p>
      </div>

      <div class="project-intro">
        <div class="project-label">Projeto acadêmico</div>
        <h3>Ciência de Dados aplicada nos esportes: futebol</h3>
        <p>Estudo sobre a aplicação da Ciência de Dados no contexto do futebol e sobre como informações e indicadores podem contribuir para analisar o desempenho esportivo e apoiar a interpretação do jogo.</p>
      </div>

      <div class="grid">
        <article class="card">
          <div class="number">01 / PROBLEMA</div>
          <h3>Problema</h3>
          <p>O futebol envolve muitas informações, como desempenho de equipes e atletas, resultados e estatísticas de partidas. Sem uma análise organizada, pode ser difícil identificar padrões e transformar esses registros em informações úteis.</p>
        </article>

        <article class="card">
          <div class="number">02 / SOLUÇÃO</div>
          <h3>O que eu fiz</h3>
          <p>Desenvolvi o tema de estudo “Ciência de Dados aplicada nos esportes: futebol”, explorando a relação entre dados e análise esportiva. A proposta é mostrar como informações organizadas podem auxiliar a compreensão do desempenho no futebol.</p>
        </article>

        <article class="card">
          <div class="number">03 / METODOLOGIA</div>
          <h3>Como eu fiz</h3>
          <p>O trabalho foi estruturado a partir do tema e de seus conceitos centrais: dados esportivos, organização das informações e análise de indicadores relacionados ao futebol. As ferramentas, bases de dados e procedimentos específicos podem ser acrescentados conforme o desenvolvimento efetivo do trabalho.</p>
        </article>

        <article class="card">
          <div class="number">04 / RESULTADO</div>
          <h3>Resultado</h3>
          <p>O estudo permite compreender a importância dos dados para analisar o futebol de maneira mais estruturada e fundamentar interpretações sobre o desempenho esportivo. Não são apresentados resultados numéricos porque nenhum valor ou medição foi informado para este portfólio.</p>
        </article>
      </div>

      <div class="note">
        <strong>Observação:</strong> este portfólio apresenta o tema acadêmico informado. Antes de publicar, complemente a metodologia com as ferramentas e os dados realmente utilizados e atualize os resultados com as conclusões efetivamente obtidas no trabalho.
      </div>
    </section>

    <section class="about" aria-label="Sobre o estudante">
      <div class="about-box">
        <h2>Sobre mim</h2>
        <p>Sou estudante do 4º Termo de Ciência de Dados da Fatec Adamantina. Tenho interesse em aprender e aplicar conceitos de análise de dados para transformar informações em conhecimento.</p>
      </div>
      <div class="about-box">
        <h2>Áreas de interesse</h2>
        <p>Ciência de Dados, análise de informações, tecnologia e aplicações de dados no esporte.</p>
      </div>
    </section>
  </main>

  <footer>
    <div class="wrap footer-inner">
      <div><span class="footer-name">Eduardo Ferreira Miotto</span><br>4º Termo de Ciência de Dados · Fatec Adamantina</div>
      <div>Portfólio acadêmico · <a href="https://github.com/" target="_blank" rel="noopener noreferrer">GitHub</a></div>
    </div>
  </footer>
</body>
</html>
