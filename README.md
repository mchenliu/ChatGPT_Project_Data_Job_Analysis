![Friends](images/Friends.png)
# Introduction
:mega: This project explores screenplay script of the most popular sitcom Friends using ChatGPT. This project was is completed following Luke Barousse's [Youtube tutorial](https://www.lukebarousse.com/chatgpt).

:bar_chart: **Data Source:** [FRIENDS TV Series - Screenplay Script](https://www.kaggle.com/datasets/blessondensil294/friends-tv-series-screenplay-script/data)

:moyai: **AI Disclaimer:** This entire project was built using ChatGPT, from generating the code for visualizations to producing the text for this markdown file.

# Tools I used 
- **ChatGPT:**
- **Git & Github:**

# :mag: Exploratory Data Analysis

### Setting Frequency
- **Central Perk** by far the most common setting, with nearly 200 scenes. This suggests that Central Perk is a central social hub for the characters throughout the series.

- **Ross's Apartment and Joey's Apartment** are the next most frequent settings, but they are used much less compared to Central Perk.

- **Monica's Apartment** also feature prominently, reflecting how Monica’s place was one of the primary hangout spots.

- **Chandler's Office and Phoebe's Apartment** are the least featured settings. Chandler’s office is shown infrequently, as his work life is not as central to the storyline. Similarly, Phoebe's apartment is also not as frequently used for major group interactions compared to other settings.


Central Perk serves as the primary social hub. The other prominent locations are the apartments of various characters

![Settings](images/Setting.png)

### Jokes
- **Season 6 Peak**: There is a notable peak in humor contributions in Season 6, with most characters showing increased joke counts, especially Chandler and Ross.
- **Season 2 Dip**: Humor contributions reach a low point in Season 2, as indicated by almost all characters having a decrease in their joke counts.
- **Fluctuations Across Seasons**: Chandler and Ross show the most noticeable spikes and declines, while Phoebe, Monica, and Rachel maintain steadier contributions across seasons.

Chandler and Ross are the main drivers of humor throughout the series. Season 6 is a comedic high point for the entire show.

![Jokes](images/jokes.png)

### Common Words Used

- **Most Common Words:** The words "know", "oh", and "okay" are words were frequently used by the main characters.Other notable words include "yeah", "right", "hey", and "like".
- **Conversational Language:** The frequent appearance of words like "know", "oh", "yeah", and "okay" suggests that the characters use a lot of casual conversational fillers.
- **Character References:** The names "ross" and "joey" appear in the word cloud, indicating that the characters often refer to each other by name during conversations. This also implies that Ross and Joey were often talked about or addressed by other characters.
- **Emotional/Exclamatory Words:** Words like "oh", "right", and "hey" point towards a conversational tone filled with emotional or exclamatory expressions, which adds to the comedic timing and dynamics among the characters.
- **Insights on Interaction:** The words are indicative of frequent interactions and responses among characters. For instance, "okay" and "know" likely represent agreement or acknowledgment, showing active back-and-forth exchanges.

The word cloud gives an impression of the casual and interactive nature of dialogue in Friends.

![WodCloud](images/Word%20Cloud.png)

### Lexical Diversity
#### How this was calculated:

$$
\text{Lexical Diversity} = \frac{\text{Unique Words} }{\text{Total Words}}
$$

The result is a number between 0 and 1. If the number is closer to 1, it means you used lots of different words and had very diverse speech. If the number is lower, it means you repeated a lot of the same words.

#### The Findings:

- **Chandler and Phoebe Lead the Pack:** They use the most varied vocabulary among all main characters. This could indicate that their lines are more unique, perhaps due to their distinct and quirky personalities which tend to bring more nuanced and diverse dialogue to the show.
- **Rachel Falls Below the Averag:** Her vocabulary is the most repetitive compared to others. This might be a reflection of her consistent character arc, personality traits, or the nature of her interactions, which may rely on more common phrases or expressions.
- **Average Lexical Diversity:** Monica, Ross, and Joey hover closer to the average, indicating they have moderately diverse vocabularies, neither too repetitive nor highly varied.

Chandler and Phoebe exceed the average, highlighting their broader word usage, while Rachel falls below it.
![Lexical Diversity](images/Lexical%20Diversity.png)



### Jokes- Number of Scenes/Lines Correlation Analysis

### The Findings:
- The positive correlation means that characters who are in more scenes or have more lines generally tend to have more jokes.
- The wide confidence interval suggests there is still a lot of variability, and while the trend appears to be positive, it is not perfectly consistent across all characters.

Chandler appears to have the strongest presence in terms of both jokes and scenes/lines, while Phoebe remains lower in both.
![Correlation Analysis1](images/Correlation%20Analysis2.png)
![Correlation Analysis2](images/Correlation%20Analysis3.png)


### Jokes- Lexical Diversity Correlation Analysis


### The Findings:
- The negative correlation means generally, as lexical diversity increases, the number of jokes tends to decrease slightly, but the relationship is not strong.
- The confidence interval indicates a lot of variability, this correlation is not statistically significant, meaning we cannot confidently claim there is a relationship based on this data alone.




The relationship between jokes and lexical diversityisn't meaningful, and other factors could be influencing joke frequency.
![Correlation Analysis3](images/Correlation%20Analysis1.png)

## The Results
# What I Learned
# Conclusions
### Insights
### Closing Thoughts



