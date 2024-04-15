### Hi there 👋

<!--
**SoulGamer8/SoulGamer8** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->


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
      - uses: SoulGamer8/waka-readme-stats@master
        with:
          WAKATIME_API_KEY: ${ waka_fc832123-d699-4d58-964a-d62e58748435 }
          GH_TOKEN: ${ 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 }
