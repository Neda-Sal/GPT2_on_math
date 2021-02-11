# GPT-2 on Math

In a [previous project](https://github.com/Neda-Sal/Twitter_on_Math), I collected 9,000 tweets (~6,500 after cleaning and dropping duplicates) with the keyword math to do topic modeling and sentiment analysis. At the time I collected the tweets, 

I decided I wanted to train a model to output AI generated math tweets. I trained a GPT-2 model on the 6,500 tweets and a theme in some of the tweets is about the election. 

After training for 4 epochs, here are some tweets that were generated:

> how do you report math excuse me
>
> math doesnt add up in 20 years.
>
> math is hard, can you help me
>
> they dont math much like our ancestors
>
> rt there are so many people on both sides that the math just does not add up.
>
> my math teacher pressed on me, saying that biden would need 70% of the vote to catch trump with only 25% of the votes remaining in a legal fashion.
>
> the only reason im good at math is because im good at it
>
> math test on day 9
>
> my math teacher isnt there. she is talking about loans with a man. i dont think the student knows where i got that from.
>
> rt math is one of the easiest math classes
>
> rt lets do some math, let alone some actual math of electoral college math. lets see. lets assume the worst about 85% of the wm still uncounted and 90% of the nonvoters who voted biden are going to be able to vote. that means biden wins by-election in like fashion.
>
> the way i got there and when i got there the teacher was holding a mid year test and i couldnt see what i was doing so i turned around and started doing my math hw instead
>
> my brain doesnt comprehend how i have to decipher math answers on twittwr the math may be wrong but at the end of the day i have to decipher that blue box in my head and at the end of the day i have to decipher that blue box
>
> i know who invented the cotton gin, but i think if you took a 1 ⁴1d4d4x6 you'd be wearing a cotton gin, not a math-rimony pair
>
> me after listening 3435 times before it was 3435 and actually doing the math.... https://t.co/o5hptk5qh9
>
> okay so i took math so lets talk now
>
> i tried to explain to him that i suck at math, that i suck at electoral math, that i dont know the electoral college vote. he actually laughed- i wouldnt have if i only had been a sophomore in high school.


It should be noted that around the time that the votes for the 2020 election were being counted, I was scraping twitter for tweets with the keyword math. Unsurprisingly, when I did topic modeling, tweets about the election had its own topic cluster. Other topic clusters included math teachers, math being hard, needing help with math, and various meme formats. More details on the topics can be found in my GitHub [project repo](https://github.com/Neda-Sal/Twitter_on_Math), or in the [blog post](https://towardsdatascience.com/math-unsupervised-a3667b6ec9b8) I wrote about that project.

I found it interesting (although perhaps not very surprising) that the themes appearing in the generated tweets are consistent with the topics I uncovered in my previous project. I also found it quite interesting that the model generated it's own links for some of the tweets.


I would be interested to see more AI generated tweets after another round of cleaning.









