---
name: decorazione-futurista-editoriale
description: "Estranges a page's form toward essential futurism at a 0 to 100 level, drawn from Marinetti's own manifestos, while every word stays legible. Use when the user asks to beautify, decorate or dare more with a page, to make it less generic or more futurist, or to brainstorm visual effects."
---

# Estrange a page with essential futurism

## Input

One number from 0 to 100: how *essenzialmente futurista* the result should be. When I have not given it, ask in a question widget with 40 as the recommended value. The effect covers the whole page or section, unless I name an element. Work with me in chat, with no plan files; the one file you write is the preview page.

## Thesis

Futurism here means its method, not its look. Diagonals, speed lines, red and black, heavy sans, onomatopoeia, math signs between words and scattered words are the surface of 1912. Repeated today they are what Marinetti called *immagini stereotipate*, a museum piece, the art of the lost object that the 1915 *Ricostruzione* rejects. What carries over:

- **Sensibility from the medium.** Futurism "si fonda sul completo rinnovamento della sensibilità umana" brought by the telegraph, cinema and the daily paper (1913). Our medium is the computer: real time, data, network, response to the reader's body, generation. Form comes from what this medium does to perception, as the *parole in libertà* came from the telegraph.
- **Analogy without wires.** Analogy is "l'amore profondo che collega le cose distanti" (1912), graded from immediate, close to a photograph, to vast. The visual layer is the second term of an analogy whose first term is the text. *Immaginazione senza fili* keeps only second terms.
- **Matter instead of the io.** The form lives the life of the subject's matter: its forces of compression, dilation, cohesion and disaggregation, weight as a faculty of flight, noise as dynamism, smell as dispersion, down to molecular motion. It lends the matter no human feelings: "sarò più verde domani".
- **Atmosphere.** The *aggettivo-atmosfera* and the doubtful *x* (1913, 1914) spread one quality over a whole zone of words. One state impregnates every element and signals the speed of reading, like a railway semaphore.
- **Simultaneity and the reader.** *Lirismo multilineo* runs parallel chains of senses; the *Teatro di Varietà* makes the audience a collaborator. Time, scroll, pointer, sound and device become parts of the work.
- **Numerical sensibility.** "campana rintocco ampiezza 20 kmq" (1914): an exact measure replaces a vague adjective. Real figures of the subject can carry the image.
- **Stupefaction.** Its force wears out with time, so the variety theatre invents without repeating. Each page gets a form nobody has seen, futurist clichés included.
- **Tendency.** Marinetti calls his rules "né categorico, né sistematico". Use the few principles the content calls for.
- **Laughter.** *Il controdolore* and the variety theatre estrange through disproportion and irony against solemnity.

Take the method and leave the movement's ideology: war, contempt for women, nationalism.

## Legibility

Marinetti kept syntax for exposition (1913) and listed among his means "i pali analitici esplicativi che sostengono il fascio dei fili intuitivi". The text is the analytic pole; the futurist form is the bundle of wires around it. Once the higher expression is reached, the words "ritornano al loro fluire normale" (1914), and typographic play for its own sake is out. At every level:

- the text keeps its words, order and punctuation, stays selectable and reaches screen readers in reading order;
- every word stays readable at every moment of every animation, at WCAG AA contrast;
- each peak of intensity resolves into normal flow, and white space works as the *riposi dell'intuizione*;
- reduced motion shows a static equivalent that keeps the analogy.

## Level

The level sets how far the analogy reaches and how much of the page the form governs. Each band includes the ones below it.

| Level | Analogy | Form | Sources |
|---|---|---|---|
| 0–20 | immediate, from the subject's own matter | one atmosphere across the page at the smallest amplitude that reads; motion optional | *Manifesto tecnico* 1912 with *Risposte alle obiezioni* |
| 21–45 | a force of that matter | the atmosphere moves with reading time or scroll, with peaks that return to normal flow | *Distruzione della sintassi* 1913, *Lo splendore geometrico* 1914 |
| 46–75 | vast, reaching distant matter and real figures | parallel chains beside the text (sound, data, matter); the reader's input acts on them | *Ricostruzione futurista dell'universo* 1915, *Il Teatro di Varietà* 1913 |
| 76–100 | second terms only | an autonomous object, "somigliante solo a sé stesso", carries an analogy with no visible link to the text's subject | *Fondazione* 1909, *Il controdolore* 1913, further Marinetti manifestos verified in primary form |

## Steps

1. Read the design system: type, colors, spacing, motion and components. Sum it up in one line, then say in one line what the page says, or what the project wants to say if there is no content yet.

2. Research for the level, in this order.
   - Read in full every source of the level's bands, starting from the pointers below. For any other Marinetti manifesto, such as *La radia* (1933), accept a text only after checking author, date and first publication against a primary edition or facsimile, and label secondary sources as secondary.
   - Search for the matter of the page's subject: its physics, numbers and noises, the second terms an analogy could reach.
   - Search the technical means, favouring the last twelve months: variable fonts and their axes, split-text motion, View Transitions, scroll-driven animations, `@property`, masks, SVG filters (Baseline status on webstatus.dev), WebGL and WebGPU shaders, Canvas 2D, Web Audio, device sensors, live data, Motion, GSAP, Paper Shaders, Codrops and CodePen.

   Done when every principle you will use has a short quote, its manifesto, year and URL.

3. Pitch one direction in chat: the analogy (first term, second term), the principles with their quotes, what happens to headings, body text, images, navigation and background, how legibility holds, and the cost.

4. Build the preview: one self-contained HTML page with the prototype on the page's real headings, copy, images and fonts. Load libraries from a CDN and embed the assets, so it runs without the project's server. Give it a Replay control and a reduced-motion toggle, and its own scrollable panel when page scroll drives it. Show it inline or as an artifact when the client supports it; otherwise write it to a temporary folder outside the repo and open it in the browser. Keep it out of the codebase. Before you show it, open it yourself and check that it plays without console errors, every word stays readable throughout, and the reduced-motion version keeps the analogy. Wait for my approval or a new level.

5. Apply the approved direction to every element it names and iterate with me. Loop motion continuously only where the text calls for it.

## Source pointers

- Archive of manifestos: https://www.dada21.com/archivio/manifesti/
- *Fondazione e Manifesto del Futurismo*, Marinetti, 1909: https://www.dada21.com/archivio/manifesti/fondazione-e-manifesto-del-futurismo-1909
- *Contro Venezia passatista*, Marinetti, Boccioni, Carrà, Russolo, 1910: https://www.dada21.com/archivio/manifesti/contro-venezia-passatista-1910
- *Manifesto tecnico della letteratura futurista*, Marinetti, 11 May 1912, with *Risposte alle obiezioni*, 11 August 1912: https://www.dada21.com/archivio/manifesti/manifesto-tecnico-della-letteratura-futurista-1912
- *Distruzione della sintassi. Immaginazione senza fili. Parole in libertà*, Marinetti, 11 May 1913: https://it.wikisource.org/wiki/I_Manifesti_del_futurismo/Distruzione_della_sintassi,_immaginazione_senza_fili,_parole_in_libert%C3%A0
- *Il Teatro di Varietà*, Marinetti, 1913: https://it.wikisource.org/wiki/I_Manifesti_del_futurismo/Il_Teatro_di_Variet%C3%A0
- *Il controdolore*, Palazzeschi, 1913: https://www.dada21.com/archivio/manifesti/il-controdolore-1913
- *Lo splendore geometrico e meccanico e la sensibilità numerica*, Marinetti, 18 March 1914, facsimile: https://www.memofonte.it/files/Progetti/Futurismo/Manifesti/I/61.pdf
- *Ricostruzione futurista dell'universo*, Balla and Depero, with Marinetti's statement, 1915: https://www.dada21.com/archivio/manifesti/ricostruzione-futurista-dell-universo-1915
