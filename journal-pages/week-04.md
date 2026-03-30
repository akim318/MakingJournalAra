---
layout: default
---

# Week 04

[← Back to Home](../index.md)

# Introduction
 Hello and welcome to Week Four of DES250: Designing with Data! This week we began our third in class experiment, focusing on artificial intelligence using Ollama and NotebookLM. We also started dicussing our ideas for our indiviual data driven portraits, exploring what data we could use, how we might collect it or find it, and how we could express it through a physical or digital outcome.

## Building onto Last Week's Experiments
 Last week, we dicussed and worked on our indiviual live data portraits. We began the class by sharing our projects with each other in small groups, guided by five prompts to help structure our discussions.

### What Live Data Source Did You Work With, And How Did You Access It?
 I decided to use my own personal data collected from my phone and laptop. My live data source was the messages I sent across both devices, categorised into each different platform I used to send these messages.

### What Does Your Work Reveal Or Communicate About The Data?
 I wanted my work to highlight which platforms I used to communicate and reveal patterns in how I interact across different medium. By mapping out the platform, whether that was email, messaging apps, or other platforms. I hoped to viuslly respresent the nature of those coversations without directly showing the messages. For example, certain platforms tend to be used for more formal or work related exchanges, while others are reserved for casual, personal communication. Visualising this distinction could offer a deeper understanding of not just how often I communicate, but the context and purpose behind each interaction.

### How Would You Develop Further With More Time?
 I would expand the plane of data collected. I could look into also collecting the time of day, the day of the week, the message length or even response times to further visually showcase my behavioural patterns with communication. 

 <iframe src="https://editor.p5js.org/akim318/full/KFXq54k6S" height="500" width="600"></iframe>

## Artifical Intelligence
 We began by discussing how we personally use AI and what implications it could have on design. Many people felt that AI has the potential to streamline the design process, particularly by assisting with the more technical groundwork that happens before the creative work begins.

 We also explored how AI could support designers in developing new skills. Whether that's learning a specific program or picking up techniques that would otherwise take a long time to master. Rather than sifting through countless tutorials, a designer can ask an AI chatbot targeted questions and get immediate, relevant guidance.

## Ollama & NotebookLM
 In our class experiment, we began by exploring Ollama, an open source tool that allows you to run large language models directly on your own computer through the terminal, which we had been introduced to the previous week. All the data stays on your device, however, the models available through Ollama tend to be less powerful and capable than cloud based language models like ChatGPT, which have access to significantly more computing resources and larger training datasets.

### Running Ollama And Using Qwen
 I started by downloading and running Ollama on my device. I got lucky in that I copied and pasted the cURL link directly into my terminal to install it, rather than downloading Ollama as an application. This turned out to be the smoother approach as most other people in class ran into significant difficulties trying to get the application version to open and run properly.

 ![example screenshot of finished downloading ollama onto my terminal](../assets/week-04/downloadollama.png)
 *Screenshot of Downloading Ollama Into Terminal*

### Using Qwen
 I then downloaded Qwen.

 ![example screenshot of finished downloading qwen onto my terminal](../assets/week-04/downloadqwen.png)
 *Screenshot of Downloading Qwen Into Terminal*

 In class, we were shown an example model that Leo had created, where he had defined his model file so that the language model would interact with him as Mario from Super Mario Bros. For my model file, I decided to define my language model as Yoshi, also from Super Mario Bros. To make the interactions feel more authentic, I went onto the Super Mario Bros. wiki and copied the section describing how Yoshi speaks, pasting it into the model file to help shape the tone and style of our conversations.

 ![example screenshot of inside the model file](../assets/week-04/insidemodelfile.png)
 *Screenshot of Writing in The Model File*

### Talking To Yoshi
 ![example screenshot of me talking to yoshi](../assets/week-04/talkingtoyoshi1.png)
 *Screenshot of Me Interacting with Yoshi 1*

 ![example screenshot of me talking to yoshi](../assets/week-04/talkingtoyoshi2.png)
 *Screenshot of Me Interacting with Yoshi 2*

 ![example screenshot of me talking to yoshi](../assets/week-04/talkingtoyoshi3.png)
 *Screenshot of Me Interacting with Yoshi 3*

### NotebookLM
 I didn't known a resource like this existed. I think it would be incredibly useful for studying, and could easily be applied across a range of different classes and subjects. What impressed me most was that I was able to copy and paste the link to my making journal directly into NotebookLM and asked it to generate a quiz based on the content. The questions were surprisingly in depth and covered things I hadn't even explicitly mentioned in my writing.

 ![example screenshot of notebooklm](../assets/week-04/notebooklmquiz.png)
 *Screenshot NotebookLM and the Quiz*
 
## Reflective Proposal 
 During the weeks spent in class and independently, I found myself enjoying working with p5.js. A large portion of my enjoyment comes from vibe coding, as it has made everything more accessible for me. I can use AI tools to write specific parts of the code I am not yet familiar with, which keeps the creative momentum going. This class has also helped me notice that most of the data I encounter day to day already exists in visual form on my devices such as my phone's screen time report and the health app tracking my movement. For my reflective proposal, I am drawn toward the theme of the datafication of everyday life. The way ordinary behaviour is quietly being measured, recorded, and fed back to us as visual information. My thematic focus and vision for the reflective proposal are still taking shape, but I plan to use the break to work through these ideas and narrowing down what I want to represent, what I want to say, and how I might best show that through my work

### Independent Study 
 For this weeks independent study, I selected a public dataset from data.govt.nz called the Annual Gambling Expenditure Statistics. The dataset records spending across the four main types of gambling in New Zealand: TAB, NZ Lotteries Commission, Class 4 gaming machines such as pokies in pubs and clubs, and Casinos. From the financial years 2010/11 onwards. I chose this dataset because I was curious about two things: which form of gambling is most popular in New Zealand, and whether overall gambling has increased since 2010. To begin exploring the data, I uploaded the CSV file to NotebookLM as a source and asked the AI questions to help my understanding of the data.

### What I Discovered
 Kiwis are buying a lot more Lotto tickets than they used to. Spending has nearly doubled since 2010 and has grown steadily every year with no crashes or dips. The pokies look like they're growing because the dollar amounts keep going up, but once you account for inflation, people are actually spending less in real terms than they were in 2010. The numbers went up, but money is worth less now so the growth is partly an illusion. Pokies are also worth understanding differently from other gambling. Players lost about $1 billion on gaming machines in 2023/24, but they actually wagered $11.5 billion. The same money cycled in and out of machines over and over before 1 billion dollars of it was gone. Casino revenue also collapsed during COVID because people simply couldn't go, then shot back up fast once restrictions lifted. In 2010, the average adult spent more than twice as much on pokies as on Lotto. That gap has narrowed significantly, Lotto is becoming more popular per person, pokies slightly less so. Casinos are only gambling category where the full picture is missing. For every other gambling type we can see how much was wagered, how much was paid out in prizes, and how much was ultimately lost. For casinos, only the losses are recorded, what actually gets wagered is not shown through the data. Inflation adds another important layer, while the raw numbers suggest gambling is growing, the inflation adjusted figures show that gaming machine spendings actually fell in real terms from $856 million to $769 million over the data time period. Meaning that despite more dollars being spent, the actual value of that spending declined. There is no explicit information regarding who collected this data or the specific purpose for which it was gathered, however, specific datasets like this are typically maintained and published by the New Zealand Department of Internal Affairs (Te Tari Taiwhenua). The Department is the primary regulator for gambling in New Zealand and is responsible for monitoring the four sectors mentioned in the sources: Casinos, Gaming Machines, NZ Lotteries Commission, and TAB New Zealand.

## Designing Multiple Representations
### First Prompt
 Visualise the New Zealand gambling expenditure data.
 ![example png generated by notebooklm](../assets/week-04/viusalise.png)
 *Data Visualization Generated by NotebookLM*

### Second Prompt
 Generate a Mind Map based on my sources
 ![example png of mindmap generated by notebooklm](../assets/week-04/mindmap.png)
 *Mind Map Generated by NotebookLM*

### Third Prompt
 Generate an infographic based on my sources
 ![example png of infographic generated by notebooklm](../assets/week-04/infographic.png)
 *Infographic Generated by NotebookLM*

 //more writing here

## Readings
### Maori Data Soverignty & Data Feminism
 Despite the rapid growth of AI, there is still a very human factor at the centre of it all. AI systems are built, trained, and guided by people, which means the decisions of those people are inevitably embedded into the technology. From the way AI makes decisions to the content it generates, there are ongoing concerns about fairness, accountability, and transparency. Who is responsible when AI produces something harmful or biased? And are the systems in place to regulate it keeping up with how quickly the technology is evolving? Another critical consideration is the data that AI relies on. Where is it coming from, and was it ethically sourced? Much of the data used to train AI models is scraped from the internet including the work of artists, writers, and designers, often without their knowledge or consent. This brings up serious questions around ownership, copyright, and whether the people whose data was used should have any say in how it is being used. 

 I chose the NZ Gambling Expenditure and Turnover Statistics 2010–2024 from data.govt.nz. I wanted to interrogate whether they reflected genuine habit change or simply the effect of inflation. That question felt like one where data analysis could add real insight rather than just illustrate the obvious. I chose to use NotebookLM as it was introduced in class. It was useful for getting a quick overview and identifying which gambling categories had grown most. What it could not do was  the human context: problem gambling, socioeconomic vulnerability, and affected communities were entirely absent from its framing. As D'Ignazio and Klein argue in Data Feminism, the choices made in representing data such as what to show, what to scale are never neutral. They carry the values of whoever made them. Reading that alongside this dataset made me ask whose story it tells and whose it hides. The data records expenditure as an data set but tells us nothing about who is gambling or what the consequences are for their families. The data is there while the people are not. Mikaere frames data as a strategic asset, having access to and control over data relevant to your own community is fundamental to self determination. This dataset does not categorise by ethnicity, meaning Māori communities, often disproportionately affected by problem gambling, are invisible within it. Mikaere challenged me to think of data collection as a political act, not a neutral one. The core insight across all of this is that data is never just data. It is always produced by someone, for someone, within particular power relations. 

## AI Usage Statement
*Document any use of AI tools under an AI Usage Statement heading. Explain which tools you used and describe how you used them. Reference any AI-generated content (see [QuickCite](https://auckland.libguides.com/referencing-generative-ai-tools) for guidance).*
