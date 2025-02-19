# gag

## Gags Ain't GANs

> What's this guide all about?

This guide introduces a method I call `gag` (Gags Ain't GANs), designed to generate jokes using two different approaches: comebacks and wordplay. Each approach follows two steps: generating jokes and evaluating jokes.

## Comebacks

> How do I generate a comeback joke?

1. Open [DeepSeek-R1](https://api-docs.deepseek.com/news/news250120).

1. Enter the prompt:

   ```
   # Generate a comeback joke
   
   ## Process
   1. Identify a phrase that:
      - Is insulting
      - Has double meanings
      - Is commonly used in everyday speech
      - Relates to concepts in the article
   2. Create a comeback that:
      - Transforms the intended insult into a weapon against the insulter
      - Uses the phrase's first meaning
      - Uses the phrase itself
      - Relates to concepts in the article
      - Is short
   3. Create a setup that:
      - Is insulting
      - References the phrase's alternate meaning
      - Does not use the phrase itself
      - Works in everyday conversation
      - Requires no article knowledge
      - Is short
      - Addresses "you"
   
   ## Example
   1. Phrase: cast iron heart
   2. Comeback: Sure. What? Do you sink? It might be that cast iron heart.
   3. Setup: Do you float a lot in the ocean?
   
   ## Output
   1. Phrase: [phrase]
   2. Comeback: [comeback]
   3. Setup: [setup]
   
   ## Article
   ```

1. Paste the article content below the prompt.

1. Run DeepSeek-R1 to get a comeback joke.

> How do I evaluate the comeback jokes?

1. Open a new session in GPT-4o.

1. Enter the prompt:

   ```
   For each joke provided, discuss how well the response flips the initial insult back on the person in a surprising way by using vivid metaphors. Then, give a score from 0 to 10, with 10 being the best.

   ---

   Do you float a lot in the ocean?
   Sure. What? Do you sink? It might be that cast iron heart.
   ```

1. Copy and paste the jokes you created below the prompt.

1. Run GPT-4o to get scores on each joke.

[The "cast iron heart" joke](https://youtu.be/VN3zrFBXynw?t=10) is from the late-night talk show Conan. If your jokes score as high or higher than the reference joke, they might be as funny as or funnier than what you see on TV.

## Wordplay

> How do I generate a wordplay joke?

1. Open DeepSeek-R1.

1. Enter either of these prompts:

   ```
   # Generate a wordplay joke
   
   ## Process
   1. Identify an original phrase that:
      - Is commonly used in everyday speech
      - Relates to concepts in the article
   2. Choose one modification technique:
      - Replace a word with its synonym
      - Replace a word with its antonym
      - Replace a word with its homophone
      - Change less than half of the phonemes in a word
   3. Create a modified phrase that:
      - Has a completely different meaning from the original phrase
      - Relates to concepts in the article
   4. Create a punchline that:
      - Use the modified phrase
      - Relates to concepts in the article
      - Is short
   5. Create a setup that:
      - Does not use the modified phrase
      - Relates to concepts in the article
      - Is short
   
   ## Example
   1. Original: Fruit of the Loom
   2. Technique: Change less than half of the phonemes in a word
   3. Modified: Fraud of the Loom
   4. Punchline: They were from "Fraud of the Loom."
   5. Setup: Bernie Madoff's underpants were sold at an auction.
   
   ## Output
   1. Original: [original]
   2. Technique: [technique]
   3. Modified: [modified]
   4. Punchline: [punchline]
   5. Setup: [setup]
   
   ## Article
   ```

   ```
   # Generate a wordplay joke
   ## Process
   1. Identify a target word that:
      - Is commonly used in everyday speech
      - Relates to concepts in the article
   
   2. Identify a related word that:
      - Is a synonym of the target word
      - Is an antonym of the target word
      - Is a homophone of the target word
      - Differs from the target word by less than half of its phonemes
   
   3. Identify an original phrase that:
      - Is commonly used in everyday speech
      - Contains the related word
   
   4. Create the modified phrase by:
      - Replacing the similar word with the target word
      - Relates to concepts in the article
   
   5. Create a punchline that:
      - Use the modified phrase
      - Relates to concepts in the article
      - Is short
   
   6. Create a setup that:
      - Does not use the modified phrase
      - Relates to concepts in the article
      - Is short
   
   ## Example
   1. Target: fraud
   2. Related: fruit
   3. Original: Fruit of the Loom
   4. Modified: Fraud of the Loom
   5. Punchline: They were from "Fraud of the Loom."
   6. Setup: Bernie Madoff's underpants were sold at an auction.
   
   ## Output
   1. Target: [word]
   2. Related: [word]
   3. Original: [original]
   4. Modified: [modified]
   5. Punchline: [punchline]
   6. Setup: [setup]
   
   ## Article
   ```

1. Paste the article content below the prompt.

1. Run DeepSeek-R1 to get a wordplay joke.

This process steals techniques from "[Comedy Writing for Late-Night TV](https://www.goodreads.com/en/book/show/22350931)".

> How do I evaluate the wordplay jokes?

1. Switch to GPT-4o.

1. Enter the prompt:

   ```
   For each joke provided, discuss how the deviation from the original meaning contributes to creating a surprising effect. After providing a thorough explanation for each joke, assign a score from 0 to 10, where 10 is the highest, based on its effectiveness.

   ---

   Bernie Madoff's underpants were sold at an auction. They were from "Fraud of the Loom."
   ```

1. Copy and paste the jokes you created below the prompt.

1. Run GPT-4o to get scores on each joke.

That Bernie Madoff underpants joke is from the Late Show with David Letterman. If your jokes score as high or higher than the reference joke, they might be as funny as or funnier than what you see on TV.
