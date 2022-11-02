# code-scropbar
.vertical-scroll::-webkit-scrollbar {
  width: 2em;
  height: 1em;
}

.vertical-scroll::-webkit-scrollbar-track {
  background: hsl(120 75% 50% / 1);
  border-radius: 100vw;
  margin-block: 0.5em;
}

.vertical-scroll::-webkit-scrollbar-thumb {
  background: hsl(120 100% 20% / 1);
  border: 0.25em solid hsl(120 75% 50% / 1);
  border-radius: 100vw;
}

.vertical-scroll::-webkit-scrollbar-thumb:hover {
  background: hsl(120 100% 10% / 1);
}

/* Vertical scrolling */

.vertical-scroll {
  display: grid;
  gap: 0.5em;
  grid-auto-flow: column;
