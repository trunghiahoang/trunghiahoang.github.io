---
jupytext:
  formats: md:myst
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.11.5
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---

# Notebooks with MyST Markdown

Jupyter Book also lets you write text-based notebooks using MyST Markdown.
See [the Notebooks with MyST Markdown documentation](https://jupyterbook.org/file-types/myst-notebooks.html) for more detailed instructions.
This page shows off a notebook written in MyST Markdown.

## An example cell

With MyST Markdown, you can define code cells with a directive like so:

```{code-cell}
print(2 + 2)
```

When your book is built, the contents of any `{code-cell}` blocks will be
executed with your default Jupyter kernel, and their outputs will be displayed
in-line with the rest of your content.

```{seealso}
Jupyter Book uses [Jupytext](https://jupytext.readthedocs.io/en/latest/) to convert text-based files to notebooks, and can support [many other text-based notebook files](https://jupyterbook.org/file-types/jupytext.html).
```

## Create a notebook with MyST Markdown

MyST Markdown notebooks are defined by two things:

1. YAML metadata that is needed to understand if / how it should convert text files to notebooks (including information about the kernel needed).
   See the YAML at the top of this page for example.
2. The presence of `{code-cell}` directives, which will be executed with your book.

That's all that is needed to get started!

## Quickly add YAML metadata for MyST Notebooks

If you have a markdown file and you'd like to quickly add YAML metadata to it, so that Jupyter Book will treat it as a MyST Markdown Notebook, run the following command:

```
jupyter-book myst init path/to/markdownfile.md
```


## The Pisel Leviathan

**Chapter 1: The Gladiator's Gamble**

The roar of the crowd was a living beast, hungry for blood and spectacle. Koburo, sweat stinging his eyes, adjusted the worn leather straps of his shield, the crudely painted skull leering back at him. Across the sand, his opponent, a hulking brute named Grogosh, hefted a battleaxe that looked capable of cleaving a man in two. This wasn't Koburo's first dance with death in the brutal fighting pits of Lidel, but something felt different tonight. Maybe it was the desperation clawing at his gut, the knowledge that his winnings were all that stood between his sister and starvation. 

The fight was a blur of sand, steel, and roars. Koburo, agile and quick, danced around Grogosh's lumbering attacks, his own short sword flashing like a viper's tongue. A lucky strike opened a gash on Grogosh's arm, sending a spray of crimson across the sand. The crowd, smelling blood, roared its approval.

But Grogosh, fueled by rage and the promise of a hefty purse from a nobleman with a taste for brutality, rallied. He cornered Koburo, his axe whistling through the air. Koburo, seeing an opening, ducked under the blow and slammed his shoulder into Grogosh's exposed gut. The giant stumbled, his axe clattering to the sand. Koburo pressed his advantage, a flurry of blows forcing Grogosh to his knees. 

The crowd was on its feet, a cacophony of cheers and jeers. Koburo raised his sword for the final blow, his heart pounding in his chest. But something stopped him. A flicker of fear in Grogosh's eyes, a plea for mercy. Koburo hesitated. He wasn't a killer. He was a survivor.

Lowering his sword, Koburo offered Grogosh a hand up. The crowd, stunned into silence, watched as the two gladiators left the arena together. That night, as Koburo counted his meager winnings, he couldn't shake the feeling that he had made a powerful enemy.

**Chapter 2: Whispers of Unfathomable Wealth**

The news spread through the taverns and back alleys of Lidel like wildfire. A treasure, they said, a king's ransom, 673,000 billion Pisel, buried deep beneath the waves. Some scoffed, dismissing it as a drunken sailor's tale. Others, their eyes gleaming with avarice, began to dream. 

Koburo, nursing a mug of ale in a dimly lit tavern, listened with a mixture of skepticism and morbid curiosity. The tale was too fantastical, too good to be true. Yet, a part of him, the part that had stared death in the face in the arena, couldn't help but be drawn in. 

"They say it belonged to the Sea King," whispered a hooded figure at the next table, his voice raspy and low. "A tyrant who ruled the waves centuries ago. His wealth, plundered from a thousand shores, sunk with him to the bottom of the Abyssal Trench."

The Abyssal Trench. Even the name sent shivers down Koburo's spine. A scar on the face of the world, a place of perpetual darkness and crushing pressure, where even the bravest sailors feared to tread. 

"And how, pray tell, does one find a treasure buried at the bottom of the Abyssal Trench?" scoffed a burly man with a salt-and-pepper beard. 

The hooded figure leaned closer, his eyes gleaming. "They say he left a map. A map hidden in plain sight, waiting for a worthy soul to decipher its secrets."

**Chapter 3: The Gladiator's Secret**

The next morning, Koburo found himself drawn to the docks. The salt air, the cries of gulls, the smell of tar and fish, it was all strangely comforting. He had always felt more at home on the open water than in the crowded, stifling streets of Lidel.

He had spent his childhood on a fishing boat with his father, learning the ways of the sea. After his father's death, he had been forced to find his fortune in the city, his skills with a net replaced by a sword. But the sea still held a powerful allure for him.

As he wandered the docks, he overheard a group of sailors arguing over a tattered piece of parchment. Curiosity piqued, he moved closer. 

"It's the Sea King's map, I tell you!" shouted one, a wiry man with a missing eye.

"Nonsense," scoffed another. "It's nothing but a child's drawing."

Koburo peered at the parchment. It was old, the ink faded and the edges frayed. But as he looked closer, he realized that the seemingly random scribbles were actually a series of intricate symbols. Symbols that he recognized.

His father had taught him to read the stars, to navigate by the constellations. And these symbols, he realized with a jolt, were not random. They were stars. And not just any stars. These were the stars that hung over the Abyssal Trench.

The Sea King's map. It was real. And Koburo, the gladiator, held the key to its secrets.

**To be continued...** 
