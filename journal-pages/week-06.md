---
layout: default
---

# Week 06

[← Back to Home](../index.md)

## Documentation 

 # Introduction
 Hello and welcome to Week Six of DES250: Designing with Data! This week marked the shift from broad experimentation into a focused project direction. Following our individual Proposal Consultations, each of us committed to a direction for the Data Driven Visualisation project and began working directly with real datasets for the first time. The week involved exploring data sources, developing visual references, sketching out what the final artefact might look like, and producing a first working prototype.
 
 ##  Data Exploration
 ### What the data source is, Where it comes from, What the data contains and How it is structured
 This project draws on two primary data sources: Movebank, an open animal tracking repository, and ICES (International Council for the Exploration of the Sea), an ocean monitoring organisation that compiles marine research across member countries. The first dataset I have chosen is whale shark movement data from the Gulf of Mexico, compiled by researcher Eric Hoffmayer and accessed via Movebank. It contains GPS tracking coordinates for 41 individual whale sharks over a multi year period, recording where each animal was first tagged, their movements across time, the organisations involved in tagging, and positional data in latitude and longitude. For this project the dataset contained 3,424 GPS observations, which I later sampled down to 448 points for performance in p5.js. This dataset is the primary driver of the visual as each data point becomes a circle on the canvas, positioned where that shark physically was, pulsing at a rate driven by its movement speed.
 
 [picture of data and data set from movebank]

 The second data set I have chosen is ICES oceanographic data, specifically biological community records covering zooplankton and phytoplankton populations, and sea temperature measurements from the Northern Norwegian Sea (Sørkapp Section, Atlantic Water layer), compiled by the Institute of Marine Research Norway. This dataset spans from the 1980s to the present day (2026), providing a long term record of ocean conditions. Its structure includes fields such as sample ID, country, latitude, longitude, depth range, date, season, species identifier, species name, and AphiaID. This environmental data will provide the second visual layer of my data portrait; ocean temperature and biological activity inflecting colour and saturation over time.

 [Screenshot: the Movebank dataset open in a spreadsheet or browser — showing the column headers and first few rows of data]
 [Screenshot: the ICES data portal or the downloaded CSV open, showing its structure and fields]

 ### Any limitations, biases, or gaps that you notice (or anticipate, if the data is to be collected or simulated); and what these mean for your project direction
 ### Geographical Fragmentation
 The most significant limitation is geographical. Ideally, this project would draw on data covering the entire ocean at a single point in time to show a complete, simultaneous portrait of the whole system, however, no such dataset exists. Data is collected by specific research teams, in specific locations, over specific periods, funded by specific institutions with specific priorities. The whale shark data is from the Gulf of Mexico. The temperature and biological records are from the Northern Norwegian Sea. These are two very different parts of the world, and combining them into a single visual means the work is not a precise scientific record of one place, it is a layered impression drawn from multiple fragments. I have thought carefully about whether this is a problem. My conclusion is that it may actually be a strength. The ocean is one connected system. The Gulf of Mexico and the Norwegian Sea are part of the same body of water, subject to the same pressures, responding to the same climate forces. Bringing data from both into the same visual space might communicate something true about the scale and interconnectedness of ocean ecosystems that a single location could never convey. The fragmentation of the data mirrors the fragmentation of how humans actually relate to the ocean in pieces, from specific vantage points, never all at once. 

 ### Tagging Gaps In The Animal Tracking Data
 The second limitation is specific to the Movebank dataset. The number of whale sharks observed and counted in the field does not always match the number successfully tagged.

Temporal mismatch
A third limitation, less obvious but worth naming, is temporal. The whale shark data covers a specific multi-year window. The ICES temperature records span from the 1980s to now. These two datasets do not share the same time frame, which means they cannot be precisely synchronised in the visualisation. A temperature reading from 1987 and a shark location from 2015 will exist in the same visual space without a direct causal relationship between them.
Again, I do not think this undermines the work. The project is not making a scientific argument about cause and effect. It is making an experiential argument about presence — asking viewers to feel the reality of a living system under pressure. The temporal layering of different datasets might actually add depth, like looking at geological strata: different records of the same ongoing story, laid on top of each other.
What these limitations mean for the project direction
All three limitations reinforce the conceptual argument of the project rather than undermining it. The Sri Lanka case that grounds this work showed that the problem was never missing data — it was that the data which existed was not felt by the people with the power to act. A partial, imperfect, fragmentary dataset that still speaks honestly about animal lives and ocean conditions is entirely consistent with that argument. Science has never had complete data about the ocean. It has always worked with fragments. And those fragments have always told a true enough story for people to act on, if they were paying attention in the right way. The gaps in the data are part of the truth the work is trying to tell.

 ## Visual Research and Precedent Study
 A central design challenge for this project has been finding a way to represent the ocean without relying on obvious ocean imagery (no waves, no fish, no boats). That kind of literal iconography would undermine what the project is trying to do. If the data is the most honest version of the ocean, the visual language needs to come from the data itself, not from a pre existing idea of what the ocean is supposed to look like. The direction I landed on is abstract and watercolour based colour fields that bleed into each other, circles that grow and shrink like breathing, movement that drifts rather than rushes. The goal is that a viewer recognises the ocean not because they see a wave, but because they feel the quality of water; its weight, its slowness, its depth, the way light moves through it. The biggest influence on this has been Claude Monet, whose late water lily paintings show how a natural system can be rendered through pure colour and mark making, with no horizon line and no literal reference point, and yet still be immediately recognisable as water.

 [Image: Claude Monet — Water Lilies, any from the late series. Source from MoMA or the Art Institute of Chicago and credit properly]

 ###  1Ocean — Oceanic Humanity Installation
 The Oceanic Humanity installation by 1Ocean is a site specific light work made up of luminous cubes, each side displaying artworks that merge X-rays of human bodies with microscopic ocean imagery — collapsing the boundary between human biology and ocean biology into a single image. What draws me to it is the idea that the ocean is not something external to us but continuous with us. The installation does not ask you to care about the ocean as a distant problem — it shows you that you are already part of the same system. I want to carry that sense of continuity into my own work — the feeling that looking at ocean data is, in some sense, looking at ourselves. This reference reinforced my direction rather than changing it, but gave me a clearer way of articulating the connection I am trying to build.
 
[Screenshot: an image of the Oceanic Humanity installation from 1ocean.org/projects/art-and-culture]

 ### Bow Seat — Sea Life Hears More Than You
 Bow Seat is an organisation that runs an annual Ocean Awareness Contest, inviting young people worldwide to make art, poetry, film, and multimedia work exploring how human activity impacts the ocean. The works in this theme explore ocean noise pollution — the way industrial activity intrudes into the acoustic world of marine animals in ways that are completely invisible to most people. What draws me to this is the idea of making a hidden dimension of ocean life perceptible. Sound is data too — it is just data most of us cannot access without some kind of intervention or translation. My project is doing something similar with GPS and temperature records: taking data that exists but is invisible to ordinary people and rendering it in a form they can actually experience. This reference reinforced the idea that the most powerful ocean art is not the work that shows you the ocean — it is the work that helps you sense something about it you could not sense before.

 [Screenshot: a work from the Bow Seat gallery at bowseat.org/gallery, ideally from the noise or sound pollution theme]

 ### Gustav Klimt — Attersee (1900)
 Klimt's water surface paintings are the closest visual precedent I have found for the aesthetic I am working toward. The way he builds up light on water through repeated organic marks — small brushstrokes accumulating into something shimmering and alive — is exactly the quality I am chasing. The pale aqua and sage palette in the p5.js sketch draws directly from this. What I want to carry forward is not the subject matter but the technique: the idea that a natural system can be rendered through accumulated small marks rather than a single composed image, and that this accumulation produces something that feels alive rather than described. Encountering this reference confirmed that what I am doing has a serious art historical precedent, and that beauty rendered from close observation of a natural system is a legitimate mode of representation, not just a decorative choice.

 [Image: Gustav Klimt — Attersee (1900). Public domain — source from a museum website and credit accordingly]

 ### Claude Monet — Water Lilies Series (1896–1926)
 Monet's water lily paintings are probably the most important reference for this project. In his final decades he painted the surface of his garden pond obsessively, eventually producing canvases with no horizon line, no sky, no fixed perspective — just water, light, and reflection filling the entire frame. The viewer does not observe the pond from a distance. They are inside it. This is the relationship I want my work to create between a viewer and the ocean data. Monet was not painting what the water looked like. He was painting what it felt like to be present with it. That is the most precise description I have found of what I am trying to achieve with this project. This reference did not change my direction but gave me the clearest language I have had for what I am actually going for.

 [Image: Claude Monet — Water Lilies, late series. Source from MoMA, Art Institute of Chicago, or Musée de l'Orangerie and credit properly]

 ### Club Ocean — Animal Tracking Bracelets and Adoption Plushies
 Club Ocean sells bracelets and adoption plushies that each come with a secret access link letting you track a real named animal's movements in the ocean. What draws me to this is what it reveals about how people form emotional connections with data. Club Ocean has found a way to make animal tracking feel personal and intimate — you are not looking at a dataset, you are following your animal, checking where it went, caring about it. The specific quality I want to carry forward is that sense of personal relationship with a tracked animal. My project is working with the same underlying data — GPS coordinates of individual animals — but rendering it as ambient art rather than a consumer product. The question this raises for my work is: how do I create that same feeling of connection without the explicit personalisation? My answer keeps coming back to sustained exposure and beauty. If the work is something you return to daily, you develop a relationship with it over time without being told to. This reference sharpened my thinking considerably.

 [Screenshot: the Club Ocean website at club-ocean.com, showing the bracelet product and the animal tracking map]

 ### 100 for the Ocean — Photography Print Fundraiser
 100 for the Ocean is a print fundraiser organised by photographers Paul Nicklen, Cristina Mittermeier, and Chase Teron, bringing together 100 world-class photographers whose work is sold with 100% of net proceeds going to ocean conservation. Mittermeier has described the goal as not just raising funds but starting a conversation — sharing the stories of the planet, creating connection, and making a lasting impact. What draws me to this is the model it proposes: art as the mechanism for creating connection between people and the ocean, with that connection then translating into real conservation outcomes. The photographers in this project are not making diagrams or infographics. They are making things people want to look at, own, and live with. That is exactly the hypothesis my project is built on — that beauty is not a luxury in ocean conservation communication, it is the strategy. This reference gave me a lot of confidence that prioritising aesthetic quality over informational clarity is not a naïve choice. It is proven.

 [Screenshot: the 100 for the Ocean website at 100fortheocean.com, showing one of the photography prints and the project overview]

 ## Project Planning and Skills Roadmap
3.1 What do I need to make?
The final artefact is going to be a slowly shifting, screen-based colour-field visualisation — basically a living painting driven by real data. No map, no legend, no chart. Animal movement and environmental conditions will translate directly into colour, saturation, and form, and everything will move continuously. The plan is for the work to exist in two states: a calm default state where the ocean breathes slowly in soft aquas and greens, and a tension state where shipping lane density causes warm amber and red tones to fracture through the canvas and hard geometric lines appear cutting across everything.
[Photo or scan: your hand-drawn concept sketch from class showing the two-state structure with annotations]
[Screenshot: the revised digital concept sketch showing the calm state and tension state side by side with the ghosted coastline]
3.2 What do I need to learn?
Based on the concept sketch, here are the skills I need to develop, in priority order:
1. Integrating the ICES temperature data as a second layer — right now the prototype only uses the whale shark movement data. Mapping annual temperature values to colour warmth is the next most important thing because it is central to the conceptual argument. The work needs to show the environment the animals are moving through, not just the animals themselves.
2. Building the tension state — the shipping lane layer — hard geometric lines that appear and cut through the colour field when shipping density increases. This is the visual provocation the whole project is built around and needs to be developed carefully so it feels like collision rather than just decoration.
3. Performance optimisation — making sure the sketch runs smoothly and reliably on different computers for the week 12 showcase. Currently it runs but can be sluggish depending on the machine.
4. Background texture — making the background feel like watercolour paper rather than a flat screen gradient. Lower priority but will make a real difference to the final look.
5. Sound (stretch goal) — an ambient audio layer driven by the same data if there is time. Speculative for now.
3.3 What are my next steps?
The immediate priority is getting the ICES temperature data into the sketch so the colour field is being driven by two sources rather than one. I will download the relevant data from ICES, process it in Python the same way I did with the Movebank CSV, and build a mapping from annual temperature values to colour properties in p5.js. At the same time I want to start building the tension state so both visual states exist in a working prototype before next week. I also want to keep refining the circle behaviour so the canvas feels more painterly — varying the drift speeds more, introducing occasional large slow circles that cross the whole canvas, and experimenting with how quickly the painting fades and rebuilds over time. The goal for next week is a prototype showing both states, running on real data from both sources.

Independent Study
1. Consultation Reflection
The Proposal Consultation was one of the most useful conversations I have had about this project. The questions pushed me to articulate things I had been thinking but had not yet said clearly — particularly around why beauty is the right mode of representation for this subject matter, rather than a functional map or dashboard. The question I found most useful was about the tension between making something artsy and making something actually useful. I had been treating those as opposites, but the consultation helped me see that they are the same thing. The most useful thing this work can do is make someone feel genuinely connected to a living system they would otherwise never encounter. A functional tool can be dismissed. Something you develop a relationship with over time cannot. The consultation also sharpened the future scenario — moving away from infrastructure language toward ambient public culture, which feels more honest about what the project is actually imagining. I came out of it much more confident in the aesthetic direction and less tempted to add explanatory text or data labels to the piece.

2. Technical Skill Building — First p5.js Prototype
My first priority technical gap was getting real data from Movebank into a p5.js sketch and having it actually drive the visual output. I had used Movebank before in the Week 3 puffin experiment, but that was a much simpler map-based approach. This time I needed the data to translate into something purely aesthetic — position into location on canvas, speed into pulse rate, nothing else visible.
I used Python to process the raw CSV from Movebank, calculating the movement speed between each consecutive pair of GPS points for each individual shark, then normalising all the coordinates to a 0–1 scale so they would map correctly onto the canvas regardless of screen size. I then sampled every 8th data point to bring 3,424 observations down to 448. This was partly a practical decision — rendering all 3,424 points with multiple gradient layers per circle at 30fps was too computationally expensive for reliable performance. But it also became a conceptual one. The work is not trying to be a complete data inventory. It is trying to create a felt presence, and 448 carefully sampled points does that just as honestly as the full dataset would.
[Screenshot: the Python script open in your code editor showing the data processing steps]
[Screenshot: the raw CSV file open, showing the original data before processing]
The prototype renders each data point as a circle using a radial gradient system accessed through p5.js's drawingContext — the native canvas API that p5 does not expose directly, but gives you access to when you need effects like radial gradients that p5 cannot produce on its own. Each circle has multiple translucent layers that dissolve at the edges, producing a watercolour bleeding effect. Movement speed drives both the base radius and the pulse rate, so faster-moving animals produce larger, more agitated circles. The palette pulls directly from the Klimt reference — luminous soft aquas and sage greens on a warm paper-white background.
[Screenshot: the p5.js sketch running in the browser — the full canvas mid-animation]
[Screenshot: the p5.js code open in the editor, showing the Circle class or the draw() function]
The main thing I learned from this is that the most interesting output came from constraints I did not plan for. The performance sampling made the canvas feel more breathable rather than less complete. The drawingContext gradient approach, which I had not used before, produces a quality of light that p5.js's native fill() just cannot — each circle genuinely glows rather than just being a coloured shape. The next step is getting the ICES temperature data into the sketch as a second layer so the colour field is responding to the environmental conditions the animals are moving through, not just the animals themselves.


 <iframe src="https://editor.p5js.org/akim318/full/cTABIT9Cs"></iframe>


3. Initial Concept Sketch
[Photo: your original hand-drawn concept sketch with the peer feedback post-it notes still attached, exactly as it was in class]
My initial concept sketch showed the visualisation as a full-bleed canvas of organic colour fields — blobs of aqua and green with shipping lane lines cutting through as hard geometric marks. During the peer critique, classmates left post-it note responses on the sketch. The feedback was pretty consistent across everyone: the visual was compelling and colourful, but nobody could tell what it was showing. Comments included things like "looks colourful but don't know where it is and what it's showing", "what data will you use?", and "looks cool, very abstract — possibly could be more specific so it's easier to understand."
This was useful feedback because it identified the central tension in the project rather than a flaw in it. The abstraction was working visually — the energy and colour were landing — but without any spatial or contextual anchor, the connection to real data was invisible. I had been so focused on the aesthetic that I had not thought about how a viewer with no prior knowledge of the project would encounter it.
In response, I revised the sketch with two changes. First, I added a faint ghosted coastline beneath the colour fields — just enough to say this is a real place without the work becoming a map. Second, I added a two-state structure: a calm default state and a tension state where shipping density fractures the canvas with warm tones and hard lines. This addressed the feedback while keeping the abstraction intact — the answer to "what is this showing?" is now felt spatially rather than read from a label.
[Screenshot: the revised digital two-state concept sketch showing the calm state on the left and the tension state on the right, with annotation labels]

Reflection
Week 6 was the most productive week of the course so far. The consultation confirmed the direction. The peer feedback gave me a concrete problem to solve in the revised sketch. The prototype proved the data pipeline actually works. The thing I keep coming back to is the line between abstraction and legibility — how much the work needs to explain itself versus how much it should just be felt. That question is not resolved yet, and I think it is going to keep driving the development of the project over the coming weeks.


What gets counted and what gets left out is never a neutral decision, it reflects the priorities, resources, and constraints of the people doing the counting. The untagged sharks are not less real. They are just harder to reach. Their absence from the dataset is itself a kind of data; evidence of the limits of what science can observe and record.





## Images & Media

*Use the format below to embed images from your assets folder:*

`![Alt text](../assets/week-01/your-image.jpg)`
`*Your caption here*`

*The text inside the square brackets is alt text (a description for accessibility), not a visible caption. To add a caption, place a line of italic text below the image.*

## AI Usage Statement

*Document any use of AI tools under an AI Usage Statement heading. Explain which tools you used and describe how you used them. Reference any AI-generated content (see [QuickCite](https://auckland.libguides.com/referencing-generative-ai-tools) for guidance).*
