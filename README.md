### Hi there 👋

<!--
**Sadeen-Alaa/Sadeen-Alaa** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
<div>
  <h1>fs
    <h1>
  </div>
    <script>
      
fetch('https://codeforces.com/api/user.status?handle=sadeen&from=1&count=10').then(response => response.json()).then(characters => showCharacters(characters.results));
  showCharacters = characters => {
  const charactersDiv = document.querySelector(‘#rick-and-morty-  characters’);
  characters.forEach(character => {
    const characterElement = document.createElement(‘p’);
    characterElement.innerText = `Character Name: ${character.name}`;
    charactersDiv.append(characterElement);
  });
}
    </script>
