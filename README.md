# gag

## Gags Ain't GANs

> What's this guide all about?

This guide introduces a method I call `gag` (Gags Ain't GANs), designed to generate jokes using two different approaches: comebacks and wordplay. Each approach involves three steps: generating material, creating jokes, and evaluating jokes.

## Comebacks

> How do I generate material?

1. Open [GPT-4o](https://openai.com/index/hello-gpt-4o/).

1. Enter the prompt:

   ```
   Generate simple, conversational, and insulting questions. For example, "Do you float a lot in the ocean?" serves as a reference for the style. Draw loose inspiration from any section of the following article, but make sure each question doesn't rely on the article for context.

   ---
   ```

1. Paste the article content below the prompt.

1. Run GPT-4o to get a list of questions.

> How do I create jokes?

1. Open a new session in GPT-4o.

1. Enter the prompt:

   ```
   Using the following list of questions, create clever, surprising, and offensive comebacks in response. Each comeback should be brief and can consist of multiple short sentences. For instance, if the question is "Do you float a lot in the ocean?", a suitable comeback could be "Sure. What? Do you sink? It might be that cast iron heart."

   ---
   ```

1. Copy and paste the questions you generated before below the prompt.

1. Run GPT-4o to get a list of jokes.

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

> How do I create jokes?

## Wordplay

> How do I generate material?

1. Open [Claude 3 Opus](https://claude.ai).

1. Enter the prompt:

   ```
   Generate cliches loosely associated with any section of the following article. For each phrase or cliche, provide a brief explanation of how it relates to the article's content.

   ---
   ```

1. Paste the article content below the prompt.

1. Run Claude 3 Opus to get a list of cliches.

> How do I create jokes?

1. Open a new session in Claude 3 Opus.

1. Enter the prompt:

   ```
   Using the items from the following list, create jokes that incorporate a play on words. Each joke should link two items, no more, no less. The play on words can be achieved through either two different words that sound similar or one word that has two different meanings. For example, if the list contains "Bernie Madoff" associated with "fraud" and "Fruit of the Loom", a possible joke could be "Fraud of the Loom", playing on the sound similarity between "fraud" and "fruit".

   ---
   ```

1. Copy and paste the cliches you generated before below the prompt.

1. Run Claude 3 Opus to get a list of jokes.

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
