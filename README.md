<h1 align="center">HASITHA  MD</h1>

## welcome TO HASITHA MD WhatsApp BOT   මගෙ yt එකට  පොඩි  සප්එකක්  දානවද   https://youtube.com/@user-md-hasitha?si=3CEod-7LNDG1myHz                         හරිබන් එනම්  යට  තියන  ලින්ක්  එකෙන් සිසන්  id  එක  ගන්න  https://pair-production-68b5.up.railway.app

<img src="https://i.imgur.com/dBaSKWF.gif" height="90" width="100%">

<p align="center">
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=33&pause=1000&color=5513F7&width=435&lines=HASITHA|MD+WHATAPP+BOT" alt="Typing SVG" /></a>
</p>
<p align="center">
<a 


<p align="center">
  <img src="https://files.catbox.moe/oh5bya.jpeg" alt="animated" width="300" height="300" />
</p>


Node.js. file. 👇


    name: Node.js CI

    on:
    push:
    branches:
      - main
    pull_request:
    branches:
      - main

    jobs:
    build:

    runs-on: ubuntu-latest

    strategy:
      matrix:
        node-version: [20.x]

    steps:
    - name: Checkout repository
      uses: actions/checkout@v3

    - name: Set up Node.js
      uses: actions/setup-node@v3
      with:
        node-version: ${{ matrix.node-version }}

    - name: Install dependencies
      run: npm install

    - name: Start application
      run: npm start

