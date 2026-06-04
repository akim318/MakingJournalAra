---
layout: default
---

# Week 11

[← Back to Home](../index.md)

## Documentation 
# Introduction
 Hello and welcome to Week Eleven of DES240: Designing with Data! This week was about reviewing each other's journals for clarity and completeness, practising the consultation with a partner, and making plans for how we want to install our work at the showcase. 

## Journal Review
 Working in pairs, we used the Journal Checklist to review each other's entries for weeks 6–10, checking for clarity, completeness, a good balance of visuals and text, and correct technical implementation. My partner (Erica!) went through my journal and used the checklist given to us in class, to go through my online GitHub journal and tick to symbolise if the work had been completed.
 
 ![picture of journal review checklist](../assets/week-09/checklist.png)
 *Picture of Journal Review Checklist*

 After the peer review, I re-read my own journal entries from start to finish in preparation for the Studio Consultation. Reading back through everything from Week 6 to now gave me a clearer sense of how far the project has come and what the key turning points were. I identified three key moments that shaped the direction of the work:
 1. Reducing the dataset from 3,424 to 448 points (Week 7)
 The decision to sample every 8th data point to solve a performance issue turned out to be conceptually important too. Rather than curating which sharks to keep, I made a uniform reduction so that all 41 animals remained present in the visualisation, just at a lower frequency. Thinking through that decision made me realise that what gets counted and what gets left out is never neutral, the gaps in any dataset are themselves a form of data.
 2. The shift from watercolour aesthetic to microorganism visual language (Week 8)
 The early watercolour style prototype looked beautiful, but peer feedback kept raising the same problem: it didn't feel connected to the ocean. The pivot toward a bioluminescent, microorganism inspired visual language came from a simple observation that the organisms already living in my datasets had their own visual logic, and I should be drawing from that rather than from painting traditions.
 3. The round robin feedback moment in Week 9
 One comment has stuck with me since that session: "I don't know what it is so that's what keeps my interest, I want to keep seeing to figure it out." That felt like confirmation that the balance I'd been trying to find between abstraction and legibility was actually working. The work was producing genuine curiosity, not just confusion. It was the moment I stopped second guessing the level of abstraction and started trusting it.

## Practice Consultations
 We worked in pairs, taking turns interviewing each other using the question prompts from the class slides and following the same format as the Studio Consultation, ten minutes each, with the interviewer using the prompts as a guide and asking follow up questions to encourage the interviewee.

### Questions
 - Tell me about your projects theme
 - What is your data source? how did you access or collect it?
 - Tell me about a key moment in your design journey
 - How does your work challenge conventional ideas?
 - What impact do you want your visualisation to have?
 - What suprised you the most in the making progress?

### Self Reflection
 - Were your answers focused, or did you find yourself drifting?
 - Could you maintain a clear narrative about your work across different questions?
 - Were you able articulate how your work positions itself within broader ideas about data?
 - Which question was hardest to answer, and why?

 Some of the questions I found harder to answer clearly were the ones asking me to articulate why this data and why this form, not just what the project is, but the specific reasoning behind the choices I made. When asked "why whale sharks and why plankton?", my instinct was to explain the data sources rather than the conceptual logic, which isn't the same thing. The two datasets come from completely different parts of the ocean, which I've always argued is a conceptual strength; the ocean is one interconnected system, but I realised I haven't been articulating that as confidently as I should be. I also found myself over explaining the technical side when the interview moved toward the data, going into the specifics of the CSV structure and the sampling method rather than keeping focus on what that data becomes in the visualisation. That's not what the consultation is really asking for. For the second round with a new partner, I tried to stay more in the conceptual register and found it easier to be direct. What I want to work on going into Friday is keeping my answers focused on the relationship between the data and the viewer, rather than the technical pipeline behind it. I also want to be prepared to say something concrete about what the work is arguing, not just what it shows, but what it wants the viewer to feel and why that matters beyond the canvas.

## Showcase Planning
 I added my sticky note to the showcase Miro board and marked where I wanted to display my data portrait for the showcase. I'm currently planning on using one of the large screens at the front of the class to give the piece a painting like presence, to be consistent with the project's position of the data as a living artwork. 
 
 ![screenshot of miro board](../assets/week-09/miro.png)
 *Screenshot of Showcase Planning Miro Board*

 03/06/26:
 After speaking with Leo in Friday's lesson, he suggested I visit the studio when I had time to ensure the screens were working properly and that I knew how to use them. I went in and asked one of the lab technicians for help, who showed me how to use the lectern to set up my computer. However, for using the screens individually, the cables would need to be rearranged, which the technician explained is not permitted without supervision from an AV technician or LESU. I emailed Leo afterwards to ask if he could arrange this for us. Additionally, although we had booked the screens first, another pair of students also wanted to use them, so I texted Erica to confirm whether sharing one screen would be okay (she said she didn't mind sharing!).

 ![photo of setup testing](../assets/week-09/setup1.png)
 *Photo of Setup Testing*

 ![photo of setup testing](../assets/week-09/setup2.png)
 *Photo of Setup Testing*
 
 ![photo of setup testing](../assets/week-09/setup3.png)
 *Photo of Setup Testing*

 ![photo of setup testing](../assets/week-09/setup4.png)
 *Photo of Setup Testing*

## Independent Study
### Project Finalisation
 With the submission deadline on Thursday and the showcase on Friday, this week's independent study time is focused on finishing the visualisation. The current prototype from Week 10 is the closest version to the final work, but there are still refinements I want to make before it goes on display.

 The priorities I have identified are:
 - Visual polish: The current version still has some visual roughness in how the organism forms render at different canvas sizes. I want to spend time making sure the piece holds up when displayed on a larger screen without losing the quality of the motion or the layering of the gradient forms.
 - Pacing and rhythm: The earlier versions moved too fast, creating a restless visual energy rather than the slow, breathing quality I am after. I have been gradually slowing the animation down across the past few weeks, but I want to make a final decision on timing before the showcase.
 - Project statement finalisation: The second draft from Week 9 is strong, but I need to check whether it still fully describes the work now that the visual direction has been refined. 

 The project has been in a constant state of becoming since Week 6, and there is something fitting about having to make a final decision about what it is right before it goes into a room full of people who will look at it without any of the context I've been building up. That tension — between what the work knows about itself and what a viewer can sense from it alone — is in some ways what the whole project is about.
 
### The Final Data Portrait
<iframe src="https://editor.p5js.org/akim318/full/icWuj1zyO" height="500" width="600"></iframe>

 This week I finalised the data portrait! What follows is a complete account of how every dataset is translated into the visual, every colour, every pulse, every organism form is a direct consequence of real data. Just for a recap, these are my 3 datasets:
 1. Norway Sørkapp Sea Temperature (IMR/ICES, 1977–2023)
 2. Phytoplankton (ICES DOME, Baltic/North Sea) & Zooplankton (ICES DOME, Baltic/North Sea)
 3. Whale Shark GPS Tracks (Movebank, Gulf of Mexico)

### Norway Sørkapp Sea Temperature (IMR/ICES, 1977–2023)
 The sketch cycles slowly through 44 years of oceanographic records from the Sørkapp Section, completing one full loop every three minutes. This dataset operates at the level of the entire canvas, it is the atmosphere the organisms live inside, not the organisms themselves. Temperature anomaly controls the background colour. Warm years push a faint amber-orange glow up from the bottom of the screen, for example; 2017, at +1.11°C above baseline, produces one of the most visible blooms. Cold years bring a blue violet tint bleeding down from the top such as data drom 1978 at −1.63°C is among the deepest. The stronger the anomaly in either direction, the more saturated the tint. Neutral years return the canvas to pure black. The background is always data. Salinity from the same dataset controls the luminosity of everything else on screen. Higher salinity years make the organisms pulse slightly faster, particles become brighter, and the sand ripple layer sharper. Lower salinity years dim the whole composition. Technically this is handled through a per frame alpha multiplier applied to every organism: `(0.82 + nS * 0.14)`, where `nS` is the normalised salinity value for the current year. The light in the portrait is not a design choice, it is also a measurement.

### Phytoplankton (ICES DOME, Baltic/North Sea)
 Each phytoplankton data point carries three values: an x position, a y position, and an abundance score normalised between 0 and 1. The x and y coordinates map directly onto the canvas as starting positions, these are real survey locations translated into screen space. Abundance drives organism size, glow intensity, and level of biological detail. A high abundance point produces a large organism with a strong glow and a complex form, more beads in a chain colony, more spokes on a radiolarian, more intricate cell patterning. A low abundance point produces something smaller and simpler.

 Each data point is randomly assigned one of six biologically accurate phytoplankton forms on each page load. The form category; phytoplankton rather than zooplankton, is determined by the data, but which specific organism within that category is left to chance, so the portrait looks different each time while always being true to its source material:
 - Jellyfish small: orange red palette
 - Comb jelly: golden yellow with iridescent rainbow shimmer across the comb rows
 - Radiolarian: vivid green, spokes alternating between two hues
 - Chain colony: lime coloured cells graduating in hue from base to tip
 - Dinoflagellate: turquoise coloured, each armour plate a slightly shifted hue
 - Diatom disc: hot pink magenta, striae graduating through 60° of hue

### Zooplankton (ICES DOME, Baltic/North Sea) 
 The zooplankton data follows the same structure; x position, y position, and abundance score maps in the same way. What distinguishes the zooplankton organisms is their energy. They pulse faster than phytoplankton across the board (0.45–1.05 Hz compared to 0.22–0.65 Hz for phyto), and higher abundance zooplankton are proportionally more active: more bells on a siphonophore, more tentacle detail, a faster pulse rate. 

 Five organism types, each with a fixed colour identity:
 - Siphonophore: vivid violet, bells graduating from base to highlight hue
 - Pteropod (sea butterfly): magenta coloured, with slowly flapping wings
 - Larvacean: electric blue, transparent mucus house with undulating tail
 - Medusa: teal bell with long trailing tentacles
 - Amphipod: indigo blue segmented crustacean, body segments graduating in hue from head to tail

### Whale Shark GPS Tracks (Movebank, Gulf of Mexico)
 The whale sharks, each represented by a series of real GPS waypoints recorded in the Gulf of Mexico. The x and y coordinates map directly to starting positions on the canvas. A signal and speed score for each observation drives the size of the shark organism and the number of bioluminescent spots scattered across its body, a faster or more active reading produces a larger animal with more glowing dots. Each shark is drawn as an elongated glowing body with a dorsal fin, pectoral fins, tail, and eye, rendered in blue. They move slowly across the canvas along their real recorded routes. They are the largest forms in the composition and the only ones carrying individual identity.

### What Stays Random
 A few things are intentionally left to chance on each page load, to keep the portrait feeling alive and unrepeatable:
 - Which specific organism type each data point becomes, within its phyto or zoo category
 - Starting animation phase, wobble frequency, and drift velocity
 - Small hue variation within each type's palette (±15°), so same-type organisms look individual rather than identical
 - Particle positions and lifetimes

### Project Statement: Third Draft
 This work is a living data portrait of the ocean. Built in p5.js, it draws from four scientific datasets to produce a continuously shifting digital painting: GPS tracking data of 41 whale sharks in the Gulf of Mexico from Movebank, phytoplankton and zooplankton population records from the ICES DOME database, and 44 years of sea surface temperature and salinity measurements from the Institute of Marine Research Norway's Sørkapp Section. Each data point becomes an organism on the canvas. Each organism moves, pulses, and glows according to what the data actually says. Its position, its abundance, its speed. The background itself is data: warm years push an amber bloom up from the bottom of the screen, cold years pull a blue violet tint down from the top, and the salinity of any given year determines how bright everything glows. Nothing in the piece is decorative.

 The project imagines a near future where real-time environmental biotelemetry is part of everyday public life - present in homes, galleries, and shared spaces as something people live with rather than consult. This is not a speculative idea so much as a question about distance. The researchers studying blue whale strikes off Sri Lanka had years of tracking data. What was missing was not information but connection. People did not feel close enough to the subject to care. My argument is that emotional proximity is what precedes behaviour change, and that conventional data visualisation — charts, maps, legends, coordinates — consistently produces the opposite: it makes living systems legible while making them feel remote.

 This work removes all of that. There are no labels, no legends, no geographic references. What remains is movement, colour, rhythm, and light. The data is still entirely present — it is just no longer asking to be decoded. I want viewers to spend time with the ocean the way they might spend time with a painting: returning to it, noticing it differently, feeling something before understanding anything. The ocean has always held more life than most people will ever witness directly. This portrait is an attempt to close that distance.

### Project Statement: Third Draft Reflection
 This is the third version of my project statement, and the first one that I feel fully represents the work as it actually exists now. The first draft was generated through NotebookLM in Week 9 and did a reasonable job of covering the required elements, but it was tonally flat and read like a summary rather than an argument. My evaluation of it at the time noted the adjective stacking phrases like "living, moving artwork" and "slowly shifting, screen-based colour field visualisation" as the clearest sign that the language was doing the opposite of what the project itself does. The project strips things back, while the statement was piling things on. The second draft was a significant improvement. It felt more like my voice and went further in explaining the ideas behind the work rather than just describing it. But it still had two problems. The most practical one was that it didn't yet include the sea surface temperature and salinity data, which I hadn't fully incorporated into the portrait at that point. The more conceptual problem was that it described the project's critical position without really making it, it said the work questions conventional data representation, but the statement itself wasn't doing any questioning. This final version tries to fix both. The full data portrait is accounted for now, with all datasets present and the temperature and salinity mappings described specifically rather than mentioned. More importantly, the statement makes an actual claim: that conventional visualisation consistently makes living systems legible while making them feel remote, and that this project is a direct response to that. 

### Final Reflection
 Looking back from Week 6 to where the project sits now, the thing that strikes me most is how different the final work is from what I originally imagined, and how much more honest it is because of that. The proposal I wrote in Week 5 described the final artefact as 'a slowly shifting, screen based colour field visualisation' using 'watercolour inspired radial gradients.' That description is not wrong, but it is describing a completely different piece to what I ended up making. The watercolour aesthetic was where I started because it was where my visual reference was: Monet's Water Lilies, Klimt's Attersee, soft dissolving colour fields that felt like the ocean without showing it. That logic still holds and I still believe it. But the work moved somewhere more specific, more biologically grounded, and I think more true. The shift happened because of feedback. Across Weeks 7 and 8, the same problem kept surfacing: the work looked beautiful but it didn't feel like the ocean. Multiple people, independently, said they couldn't tell what they were looking at. My instinct was to treat that as a legibility problem, something to fix by adding text or labels or a cleaner visual language. But what I actually did was think about what in the ocean already looked abstract. Things that are scientifically real, biologically vivid, and almost completely invisible to ordinary people. The data was already populated with living things that had their own visual logic. I just had to stop ignoring them and start drawing from them instead. That reframing changed everything. The bioluminescent microorganism visual language that replaced the watercolour aesthetic is not just more aesthetically coherent, it is a more honest representation. The organisms in the portrait are not approximations of the data, they are actually the data. The other thing I did not expect was how much the question of what gets left out would become part of the project's thinking. In Week 7, when I reduced 3,424 GPS observations to 448 by sampling every eighth point, I made that decision for a practical reason: the sketch was running too slowly. But the decision forced me to think about what it means to represent data you cannot fully show. I kept all 41 sharks, I just thinned it evenly. And what I realised is that the absent data points are not absences in the portrait, they are still real whale sharks in real locations on real days, just below the threshold of what the canvas can hold. That gap between what the data contains and what any representation can show is something I think about differently now. The piece of feedback that mattered most across the whole project came from someone at the Week 9 round robin session. They said: "I don't know what it is, so that's what keeps my interest. I want to keep seeing to figure it out." I had been treating the level of abstraction as a problem to manage. That comment reframed it as the actual mechanism of engagement. The work holds attention because it withholds explanation. The not knowing is not a failure, it is the invitation. Once I understood that, I stopped trying to make the portrait more legible and started trusting it. What I am taking away from this project is what it means to make something honest from data. Scientific data is often treated as objective, as if the act of measurement is neutral and the act of representation is just a matter of choosing the right chart. I do not think that anymore. Every decision about what to show and how to show it is an argument about what the data means and who it is for. The data portrait I made is not objective. It has a position. It argues that the ocean is alive and that people are too far from it, and that closing that distance is not a matter of information but of feeling. 

## AI Usage Statement
 Anthropic. (2026). Claude (Sonnet 4.6) [AI Language Model]. Claude.AI. https://claude.ai/login