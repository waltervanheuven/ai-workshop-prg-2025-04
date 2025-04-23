# Activity 4: Word familiarity ratings from LLM

Brysbaert et al. (2025) obtained word familiarity ratings from GPT4 using this prompt:

```txt
Familiarity is a measure of how familiar something is. A word is very FAMILIAR if you see/hear it often and it is easily recognisable. 
In contrast, a word is very UNFAMILIAR if you rarely see/hear it and it is relatively unrecognisable. Please indicate how familiar you 
think each word is on a scale from 1 (VERY UNFAMILIAR) to 7 (VERY FAMILIAR), with the midpoint representing moderate familiarity. 
The word is: {word}. Only answer a number from 1 to 7. Please limit your answer to numbers.
```

Try this prompt with different LLMs.

You can also obtain word familiarity values from GPT4 and LLMs available on [huggingface](https://huggingface.co) with a Python script. Instructions and code can be found on github at [https://github.com/waltervanheuven/llm-familiarity](https://github.com/waltervanheuven/llm-familiarity).

## References

Brysbaert, M., Martínez, G., & Reviriego, P. (2025). Moving beyond word frequency based on tally counting: AI-generated familiarity estimates of words and phrases are a better index of language knowledge. *Behavior Research Methods*. [https://doi.org/10.31234/osf.io/kgevy](https://doi.org/10.31234/osf.io/kgevy)
