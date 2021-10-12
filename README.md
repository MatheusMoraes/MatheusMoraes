# portfolio
Meu Portfólio

[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=MatheusMoraes)](https://github.com/anuraghazra/github-readme-stats)


<!--START_SECTION:waka-->

name: Waka Readme

on:
  schedule:
    # Runs at 12am IST
    - cron: '30 18 * * *'
  workflow_dispatch:
jobs:
  update-readme:
    name: Update Readme with Metrics
    runs-on: ubuntu-latest
    steps:
      - uses: anmol098/waka-readme-stats@master
        with:
          WAKATIME_API_KEY: ${{ aeb37a79-908c-49ab-889e-4cb673da2e2c }}
          GH_TOKEN: ${{ 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 }}
<!--END_SECTION:waka-->