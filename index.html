<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />

    <title>To Make a Dadaist Poem</title>

    <meta
      name="description"
      content="An example of Tristan Tzara's To Make a Dadaist Poem."
    />
    <!-- styles -->
    <style>
      #poem {
        padding: 10px;
        border: 3px solid #000;
      }
      .controls {
        padding: 10px;
      }
    </style>
  </head>
  <body>
    <h1>To Make a Dadaist Poem</h1>
    <ol>
      <li>Take a newspaper.</li>
      <li>Take a pair of scissors.</li>
      <li>Choose an article as long as you are planning to make your poem.</li>
      <li>Cut out the article.</li>
      <li>
        Then cut out each of the words that make up this article and put them in
        a bag.
      </li>
      <li>Shake it gently.</li>
      <li>
        Then take out the scraps one after the other in the order in which they
        left the bag.
      </li>
      <li>Copy conscientiously.</li>
      <li>The poem will be like you.</li>
      <li>
        And here are you a writer, infinitely original and endowed with a
        sensibility that is charming though beyond the understanding of the
        vulgar.
      </li>
    </ol>
    <cite>Tristan Tzara</cite>

    <div class="controls">
      <button id="new-poem">New poem</button>
    </div>
    <div id="poem"></div>
    <!-- script -->
    <script>
      const article = `Government officials were warned repeatedly about making misleading claims about job figures before the official statistics watchdog reprimanded Boris Johnson over the matter. Ed Humpherson, the director general of the UK Statistics Authority (UKSA), said there had been “a series of informal discussions” before the regulator took the “unusual” step of issuing public rebukes to No 10 over the same issue twice last month. During more than half a dozen editions of prime minister’s questions since November, Johnson has made the misleading claim that more people are in employment in the UK than before the pandemic began. Yet, although the numbers of workers on payrolls has risen, the number of self-employed people has dropped significantly so that the total number of people in work is down by 600,000. The chair of the UKSA, Sir David Norgrove, wrote to Johnson saying he was making “a selective use of data” and added that “public trust requires a complete statement”.`;
      const button = document.getElementById("new-poem");
      function shuffleWords(list) {
        return list
          .map((value) => ({ value, sort: Math.random() }))
          .sort((a, b) => a.sort - b.sort)
          .map(({ value }) => value);
      }
      function clearText() {
        const poem = document.getElementById("poem");
        poem.innerHTML = "";
      }
      function addLine(line) {
        const poem = document.getElementById("poem");
        const poemLine = document.createElement("div");
        const lineText = document.createTextNode(line);
        poemLine.appendChild(lineText);
        poem.appendChild(poemLine);
      }
      function assemblePoem(articleWords) {
        let lineText = "";
        for (const [counter, word] of articleWords.entries()) {
          if ((counter + 1) % 5 == 0) {
            addLine(lineText);
            lineText = "";
          } else {
            if (lineText === "") {
              lineText = word;
            } else {
              lineText = lineText + " " + word;
            }
          }
        }
        if (lineText !== "") {
          addLine(lineText);
        }
      }
      function newPoem() {
        const cutUpArticle = article.split(" ");
        const shuffledWords = shuffleWords(cutUpArticle);
        clearText();
        assemblePoem(shuffledWords);
      }
      newPoem();
      button.addEventListener("click", newPoem);
    </script>
    <!-- include the Glitch button to show what the webpage is about and
          to make it easier for folks to view source and remix -->
    <div
      class="glitchButton"
      style="position: fixed; top: 20px; right: 20px"
    ></div>
    <script src="https://button.glitch.me/button.js" defer></script>
  </body>
</html>
