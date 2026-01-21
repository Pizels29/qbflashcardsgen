<h1 align="center">QBReader Flashcard CSV Generator</h1>
<h2 align="center">Made by Aarnav Dave (pizels)</h2>
##Todo:
1. Add library of premade flashcards
2. Allow users to use flashcards directly rather than upload to Anki
3. Add CSS to make it more visually appealing
4. Link directly to Anki API (if possible)
5. Anything else? 

## Why carding matters in Quizbowl

If you want to actually improve at Quizbowl, you need to **card**.

Strong players don’t just read questions — they convert knowledge into **retrievable memory** using spaced repetition. Flashcards train your brain to recognize clues faster and recall answers under pressure.

Carding helps you:
- Recognize **early clues** faster  
- Lock in **important answers, names, and concepts**  
- Build long-term recall instead of short-term familiarity  
- Improve both **speed and depth** of buzzing  

This tool removes the annoying manual work so you can focus on what actually matters: **studying and getting better.**

## What this project does

QBReader Flashcard CSV Generator is a tiny web tool that converts QBReader `.txt` exports into a clean **2-column CSV** for flashcard apps.

- **Front of card:** first sentence of the question  
- **Back of card:** full answer line  

You can import the CSV into:
- Quizlet  
- Anki  
- Notion  
- RemNote  
- Any platform that supports CSV flashcards  

Everything runs **locally in your browser**. No servers. No tracking.

## How to get the `.txt` file (from QBReader)

This tool is designed for QBReader exports.

1. Go to **https://qbreader.org**  
2. Click **Database**  
3. Choose your filters:
   - Category (Science, History, Lit, etc.)
   - Difficulty / Level  
   - Number of questions  
4. Click the **blue `.txt` button** to download the file  
5. Open this tool (`index.html`)  
6. Upload the downloaded `.txt` file  
7. Click **Preview** to check your cards  
8. Click **Download** to export your CSV  
9. **Upload the CSV into Quizlet or Anki and start practicing**

###An example input should look like this
`2013 Penn Bowl Packet 2
Question ID: 62d98017f67c8a6f6e0a1c19
20. This man's second wife was the subject of John Singer Sargent's final oil portrait. With Philip Stanhope, this man was the president of the National League for Opposing Women's Suffrage. In one position, he sent the Younghusband expedition to Tibet and established the North-West Frontier Province. One of this man's daughters became the first wife of Oswald Moseley. This one-time Viceroy of India was passed over for the Prime Ministership by (*) Bonar Law, losing to Stanley Baldwin. The position of Lviv changed in the B form of one proposal made by this successor of Arthur Balfour while serving as Foreign Secretary under Lloyd George; that proposal was a border between two nations that split during the Russian Civil War. For 10 points, name this British foreign secretary who names a line that separated Soviet Russia from Poland.
ANSWER: The Lord Curzon of Kedleston [or George Curzon, 1st Marquess Curzon of Kedleston; or The Earl Curzon of Kedleston]
<History / European History>`
###It should output this
`This man's second wife was the subject of John Singer Sargent's final oil portrait.,"The Lord Curzon of Kedleston [or George Curzon, 1st Marquess Curzon of Kedleston; or The Earl Curzon of Kedleston]"`
