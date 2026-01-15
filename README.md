<div id="intro"></div>
const intros = [
  "What how? .",
  "&!*)#(@? .",
  "unstable.",
  "You were not expected.",
  "What?",
  "Is this Quill?"
];

document.getElementById("intro").textContent =
  intros[Math.floor(Math.random() * intros.length)];
