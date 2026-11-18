# 🌿 Nutrologia e Equilíbrio Natural: Site para Médico Nutrólogo

Site institucional premium para um consultório de nutrologia, com um conceito visual que une natureza e ciência. O foco é transmitir autoridade médica e levar o visitante ao agendamento de consulta.

<p align="center">
  <img src="docs/desktop.jpg" alt="Versão desktop" width="72%">
  <img src="docs/mobile.jpg" alt="Versão mobile" width="24%">
</p>

> Os dados do médico (nome, CRM e contato) ficam num objeto `CONFIG` e são preenchidos na publicação. Por isso, os prints mostram os campos de exemplo.

## Destaques

- **Hero em 3D com three.js**, carregado sob demanda e com versão 2D automática quando o navegador não tem WebGL
- **Luz do hero que muda com a hora local do visitante:** manhã, dia, entardecer e noite
- **Planta que cresce pela margem** conforme a rolagem
- **Seções interativas e educativas:** mapa do organismo e simulador do dia
- **Configuração centralizada:** todo o conteúdo do médico fica num único objeto `CONFIG`
- **SEO médico:** Schema.org `Physician` gerado automaticamente, sitemap e Open Graph
- **Conformidade:** textos estruturados para revisão médica, seguindo a Resolução CFM 2.336/2023 sobre publicidade médica

## Stack

`HTML5` · `CSS3` · `JavaScript` · `three.js` · `Schema.org`

## Rodar localmente

```bash
git clone https://github.com/GustavoPires275/nutrologia-site.git
cd nutrologia-site
python3 -m http.server 8000
```

---

Desenvolvido por **Gustavo Pires**: sites, sistemas e automações para negócios reais.
