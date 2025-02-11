# gag

## Gags Ain't GANs

> What's this guide all about?

This guide introduces a method I call `gag` (Gags Ain't GANs), designed to generate jokes using two different approaches: comebacks and wordplay. Each approach involves three steps: generating jokes and evaluating jokes.

## Comebacks

> How do I generate jokes?

1. Open [OpenAI o3-mini](https://openai.com/index/openai-o3-mini).

1. Enter the prompt:

   ```
   Generate multiple pairs of comeback jokes based on the following article. For each pair:
   
   1. Create a short, conversational, insulting question that could work without article context without using the word "or"
   
   2. Create a short, clever, and surprising comeback that flips the initial insult back on the person
   
   Example pair:
   
   Q: Do you float a lot in the ocean?
   
   A: Sure. What? Do you sink? It might be that cast iron heart.
   
   ---
   ```

1. Paste the article content below the prompt.

1. Run OpenAI o3-mini to get a list of jokes.

> How do I evaluate the jokes?

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

> How do I generate jokes?

1. Open OpenAI o3-mini.

1. Enter the prompt:

   ```
   Generate multiple pairs of wordplay jokes based on the following article. For each pair:
   
   1. Identify a cliche that relates to the article's content
   
   2. Create a humorous variation using any of these methods:
   
      - Replacing a word with its homophone
   
      - Replacing a word with a similar-sounding word
   
      - Combining multiple words
   
      - Splitting a word
   
   Example pair:
   
   Original: Fruit of the Loom
   
   Modified: Fraud of the Loom
   
   ---
   ```

1. Paste the article content below the prompt.

1. Run OpenAI o3-mini to get a list of jokes.

This process steals techniques from "[Comedy Writing for Late-Night TV](https://www.goodreads.com/en/book/show/22350931)".

> How do I evaluate the jokes?

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
