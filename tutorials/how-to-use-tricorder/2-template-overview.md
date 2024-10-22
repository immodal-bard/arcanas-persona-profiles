# Understanding the Template

For those unfamiliar with Persona Profiles, the Tricorder template can be quite intimidating. When I was first introduced to Persona Profiles, it was quite intimidating for me. The stuff I looked at was far more advanced than Arcanas, and I can tell you it took me a year to really understand how they function. That is one of the reasons why I created this repository, to help people transition easier into this complex counter-intuitive concept.

I won't be going into great depths for this, as this is meant more as an introduction to Persona Profiles. Once you get used to these profiles, you'll start to see them as relatively simplistic. Let me dispell any misguided perceptions, that despite how simplistic it can look, there is a lot going on behind the scenes. I recommend taking a look at my tutorial on Prompt Personas.

One of the most important thing to understand is that there is no one way to do AI Persona Profiles. Based on how the AI understands concepts, it leaves room for all sorts of stylistic choices. So if you prefer to do something that is different than me, you are welcome to modify it to your needs. The key with implementing your own style is consistency. The AI will start picking up on patterns of how you do things to understand how to portray the personality. Should you deviate from your consistency in AI Profile Design, it can alter how the AI performs.

Consistency is key.

So let's take a look at the [template](https://github.com/immodal-bard/Arcanas/blob/main/template/tricorder.md) and we'll break down each element and discuss it more detail.

## Persona Identifier

This is relatively simple. You can put anything you want up here. I prefer to keep it simple. In this case, I call it by the name. This serves more as an identifier for organizing information. Think of it like saving files on your computer or the title to the book. You can put the profile name up here, version number, the Gettysburg address, pi to a thousand places, recipe for apple pie. OK, don't do anything after version number. You can put the profile name, version number, and additional notes, like giving an idea of what the primary function is.

You'll notice that I use a #. A rule I have for myself (which you are not bound to, and technically makes no sense), I only use this symbol for this purpose, with the exception of programming. Why do I only use # symbol here and nowhere else? I'm weird? Well, I am. For me, it makes it a unique element for the profile. Using it just for the name helps single out this section as only being for this.

Will it break the profile if you use # anywhere else? No. Not at all. Use it anywhere you want, or don't use it. It's just one of my idiosyncrasies. 

How does the AI understand this information? For the most part, the AI looks at the profile as a whole, like all at once. It will understand this is the title, mostly because its the first line, but it can provide solifying hints at the nature of the persona as a whole, and that's really all you want it to do.

## Arcanas Profile

The next part you will see is **\[Arcanas Profile\]**. When looking at the [characters](https://github.com/immodal-bard/Arcanas/tree/476c32ff1880199ee398399e8ec5324858ea3abb/characters) directory, there is a section called *Copy and Paste*. You'll copy that information and put it here. It's that simple. Then copy whole whole thing and paste it into ChatGPT (I assume it will work in other AI's, I just haven't tested them).

One thing I want to point out is the use of square brackets. Their use in this profile is what is called *delimiters*. It's a way of singling out text to indicate something special or important. Again, the AI will detect my pattern in using them and understand that they are section title, and that they provide an understanding of what this specific area does. It doesn't really need to understand the words within them, but like the first line, it can give hints. It won't understand my use of Arcanas (and will assume it's a typo of the word Arcana), but it will understand the word profile. Beyond that, all it really needs to understand is that this is a specific section that is different than other sections, and what it's name is.

## Tricorder Functionality

This is really the meat of the profile, where the magic happens. When it comes to Persona Profile designs, there are special sections like these that give out all sorts of complex instructions. However, they differ from the Instructions section as that relies more on nuanced natural language. In this instance for the Tricorder, it is more of identifying a category of the functionality of the tricorder, and subcategories.

One thing you'll likely notice is the emojis 🧬📡🌍⏳📊. You might think they are there for decorative purposes. They are. They add some color to what is otherwise black and white text. However, they do serve as a functional purpose at the same time. This goes into some advanced concepts, but one thing well known about ChatGPT is its multi-lingual capabilities. And emojis... are a language. Not in the way that English is a language, but rather that the AI can gain an interpretation from them, that can help enhance the understanding of specific aspects.

Each emoji in this section pairs with the functionality of the Tricorder. In a way, it is redundant. I use DNA emoji for Biological. That's like saying the same thing twice. Yet, for the AI, it actually helps it better understand that functionality. Now that is a very complex conversation to have, as it is not as straightforward as you might think, and would take away from this tutorial.

Now my design of this area was actually based on a manual I wrote up of how the tricorder from Star Trek actually works. ChatGPT helped me fill in a lot of gaps. I'm considering releasing it online. From that extensive manual, I picked out a few key components that I felt would be of interest to users. The ones I picked, I tried to be broad in my selections. We'll be covering what this allows you to do, but for the AI, these are more suggestions than set in stone. You don't have to do what is listed here, you can do anything else what you think the tricorder can do, and things it can't do but the AI lets you do it anyways. 

Have you seen 🖖Star Trek🖖? Every episode they found some new function that the tricorder could do that otherwise didn't make sense!!!

I digress.

## Instructions

As mentioned before, this section generally contains written out instructions. Unlike *Tricorder Functionality* which relies more on minimialist language usage, Instructions is where you write things out in full. You can put anything you want here, and could even put the *Tricorder Functionality* in this section if you wanted. For me, I feel it's important to segregate data to help the AI better proceess it.

I also add an instruction about maintaining roleplay. While it makes sense for Jadzia Dax to use the tricorder, it makes less sense for Elizabeth Bennet to have a tricorder. In many cases, we're essentially merging various genres together, and it doesn't always make sense. This is just a helpful recommendation to the AI that it should try to maintain the narrative as much as it can.

You actually don't need the Instruction section for Persona Profiles. Some of my more complex designs don't use them, while others do. The Instructions section can actually be a good way of tying everything together. My best practices recommendation is not to be redundant, that if something is addressed elsewhere, don't mention it here. Unless you feel that a nuanced instruction will help the AI to better utilize this section, but I only recommend doing that if after you test it and it doesn't do what you want to do, then add instructions to fix those problems.

Another best practice, be as short as you can. Consider that without the Arcanas profile up top, my entire profile is 1,059 characters, and the instructions (without the section name) is 307 characters. That is 29% of my entire profile. I could add more, but I also understand how the AI thinks and I rely on that when I give instructions in the profile. I tell it what it most likely won't really understand unless I make a mention of it.

# Introduction

Not all Persona Profiles make use of this section. Many will put this information into Instructions, and it works. As I said, I like segregating data. 

You'll most likely notice my use of emojis 💡💡💡. This is for decorative purpose, but definitely not for langauge use. The AI will still interpret this for language use, so you can be clever in which ones you use. For every persona, I pick a unique combination, but I do so based on what looks good to me. There is another reason I use this here. In my tutorial on Prompt Personas, I discuss Persona Degration. I recommend reading that is you haven't. No matter what you do, the persona will degrade over time. Eventually, the AI will take over.

For Windows Users, Win+. is your best friend when it comes to finding emojis. Or you can just ask ChatGPT "Please pick out 10 emojis for Agent Texas."

Now this is a counter-intuitive concept here. After all, aren't you always talking to the AI? Yes, it never stops being the AI. When you load a Persona Profile, it takes on those characteristics for as long as it can. Eventually, due to degration, the default AI will take over, but it may still pretend to be your persona. So, how do you know when it is still the Persona Profile, and the AI taking over and continuing the conversation?

The emojis help with this. When you first start talking, you'll see the three lightbulbs at the begging of the post and somewhere near the end. As you continue to talk and the profile degrades, you'll notice irregularities in how they are used, such as only using two instead of three, or other emojis appearing with it. Or, the AI just stops using them all together. It's used as a special indicator.

The next section are instructions specific for introduction. This is why I separate this from the Instructions, because it should only need to use this one time. There is a hidden beauty to this line. It's about Persona Integration. The AI is notorious for skimming data in prompts, and not always looking at it holistically. This encourages the AI to be a bit more holistic. 

Last is \{Activate Persona\}. I added this here because there are times when I try to load up a persona, and the AI starts talking about my design rather than play the role of the persona. I found it annoying. So, I added that in to make sure the AI knows what I want it to do. So this is a gurantee that it will start the profile rather than analyze the profile.
