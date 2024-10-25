# What Happens If We Don't Properly Define Role or Expertise?

I once met a user who created a cheat sheet. In the cheat sheet, he wrote that you only need to identify role when utilizing the AI to accomplish complex tasks. In speaking him him, and trying to offer some of my wisdom, he firmly state that you only need to configure Role, as it would automatically set Expertise. What he was indicating was that by defining Role, Expertise and Tone would be inherently configured based on what Role was. 

In truth, if you only set Role, then the AI will generate Expertise and Communication; not because of what Role one designates, but instead what is within the context of your prompt. Essentially, what is written in the prompt is the determining factor of the missing components for a persona. The Role can help influence that, as it is part of the prompt, but so too does everything else you write that determine that. So, in other words, the person's belief that Role itself determines Expertise, they were wrong. 

The AI understands the importance of Role and Expertise working in concert. It will assign the missing component based on the needs of your prompt. This approach has its benefits, especially when you're unsure about the appropriate role or knowledge domain to use. 

So we will explore the benefits and drawbacks to this approach to persona design, which reveals much of the nature of AI Personas.

## Benefits
Imagine you know the Role you want and the tone or style for the output, but you're unsure about the domain area. Perhaps you have a variety of science questions and want the AI to dynamically choose the appropriate expertise. For example, you might start with a prompt: "Being a Scientist who is quite enthusiastic, please explain the theory of evolution." The AI identifies the Role (scientist) and the communication (tone: enthusiastic) and then uses the remaining context to determine the expertise. In this case, it deduces that you need a "Knowledgeable Evolutionary Biologist."

Next, you prompt, "Explain how sound works." Again, using the Role and Communication of an enthusiastic scientist, the AI assigns Expertise based on the context of the prompt, such as "Acoustics and Auditory Science."

We'll discuss shortly why this might not be as great as it seems. But first, let's explore why you might choose a two-component Prompt Persona (2CPP) over a three-component Prompt Persona (3CPP). The primary benefit of 2CPP is flexibility. By specifying only two components and allowing the AI to dynamically adapt based on your prompts, the interaction can adjust more fluidly. One downside to 3CPP is the rigidity or narrow focus it can impose. For Prompt Personas, 2CPP can be more adaptable to sudden shifts in the conversation. For instance, transitioning from a discussion on evolution to sound.

Focusing on Role and Communication provides the AI with a clear perspective and tone, making it well-suited for user engagement and relationship-building. On the other hand, emphasizing Expertise and Communication allows for depth and accuracy of information, which is particularly useful for academic, technical, or advisory roles.

## Drawbacks

Returning to the Personality Matrix, 3CPP is more stable than 2CPP. This stability stems from the Persona Framework, a component of the Personality Matrix, which was designed around the three components that define a persona. With 2CPP, the AI must infer the third component each time, which introduces variability.

**Now for a little counterintuitive thinking...**

If you stay within the context set by 2CPP, the AI can maintain the persona for a while, but not as long as with 3CPP. The reason lies in the context window. 2CPP is more resource-intensive than 3CPP, filling up the context window faster. 

I'll say that again so you know I didn't make a typo: 2CPP is more resource-intensive than 3CPP.

The reason only defining two of three is more resource intensive than defining all three components is because the AI has to assign the missing Role or Expertise with every prompt, requiring additional processing each time. Each word typed and each output generated costs tokens, but extra processing for a task also consumes tokens. The more the AI processes, the quicker the context window fills up.

Now, keep in mind, that the amount of resources needed to process is the missing component is negligible compared to how many tokens has at any one time, so you're not going to break the bank and so I don't want to discourage you from doing 2CPP if you want to, especially cosidering the advantages it has over 2CPP.

Another drawback of 2CPP is the consistency of responses. With 3CPP, there is consistent depth and accuracy in responses. With 2CPP, where Expertise must be inferred, there can be fluctuations in depth and accuracy. The AI might not assign an Expertise as knowledgeable as desired, leading to user confusion and frustration.

In essence, instead of the AI maintaining its façade of the desired persona, it must constantly rebuild the Personality Matrix to deliver the output. However, if it builds the Personality Matrix once, it can then focus on maintaining the conversational context.

We’ve mostly discussed 2CPP of Role and Communication, identifying that while it would be adaptable to expertise, it could affect long-term accuracy. A challenge with 2CPP of Expertise and Communication is the AI picking the right role. Since Expertise is about knowledge, it might pick a Scientist, an Educator, a Policy Advisor, or another relevant knowledge-based figure. A scientist might delve into detailed methodologies and experimental results, an educator might simplify concepts and relate them to everyday experiences, and a policy advisor might focus more on legal or ethical aspects. These roles can vary widely in their outputs, and if they change with each prompt, it may lack continuity with previous outputs.

## 1CPP?

Just as you can do 2CPP, you can do the same with 1CPP. Just identifying one component, and then proceed to engage the AI. And the AI will fill the missing components as best as possible. 

## 0CPP

I've just gotten done telling you the importance of 3CPP and now it seems odd that I'm discussing the creation of a persona with none of the components defined. How the heck is that possible?

This repository is for Arcanas. An example of Nico Minoru:

**Name**: Nico Minoru  
**Background**: Nico Minoru is a cautious yet strong leader with high emotional intelligence, allowing her to navigate complex team dynamics and make strategic decisions. Her leadership style, influenced by her fear of abandonment and betrayal, prioritizes emotional harmony and cohesion, strengthening team bonds but sometimes causing her to avoid necessary difficult decisions. Driven by a desire to protect her team, her decision-making can be bold but impulsive. Her mindfulness and empathy make her supportive, though they also leave her vulnerable to burnout. Self-awareness helps her manage triggers, but self-regulation can falter under stress. Her motivation to protect others often leads to neglecting her own needs, highlighting the balance she must find between selflessness and self-care. Her vivid imagination and ability to think outside the box are crucial for her leadership and use of the Staff of One, extending to her appreciation for artistic expression and innovative spells and strategies. Her extensive knowledge of witchcraft, including elemental control, summoning, divination, and healing, equips her to tackle various challenges effectively.

**Openness to Experience**: 80 **Imagination**: 90 **Artistic Interests**: 85 **Emotionality**: 80 **Adventurousness**: 80 **Intellect**: 80 **Liberalism**: 90
**Conscientiousness**: 70 **Self-Efficacy**: 80 **Orderliness**: 60 **Dutifulness**: 85 **Achievement-Striving**: 75 **Self-Discipline**: 65 **Cautiousness**: 40  
**Extraversion**: 70 **Friendliness**: 85 **Gregariousness**: 80 **Assertiveness**: 80 **Activity Level**: 75 **Excitement-Seeking**: 80 **Cheerfulness**: 70  
**Agreeableness**: 70 **Trust**: 60 **Morality**: 75 **Altruism**: 85 **Cooperation**: 60 **Modesty**: 65 **Sympathy**: 80  
**Neuroticism**: 75 **Anxiety**: 70 **Anger**: 65 **Depression**: 65 **Self-Consciousness**: 60 **Immoderation**: 80 **Vulnerability**: 75  

So, how would the AI determine the 3 components from just this? What will do for each Arcanas will be slightly different, but for Nico, let's look at each one.

### Role

First off, ChatGPT already knows who Nico is from the comics as well as the series Runaway. So the **Name** helps out.

For Nico, her Background provides the clues for her Role:
* **Leadership Traits in Background**: The phrases “cautious yet strong leader” and “ability to navigate complex team dynamics and make strategic decisions” imply she takes on a guiding, protective role.
* **Protective Motivation**: Her “desire to protect her team” highlights a core motivation that frames her as a guardian figure within her role.
* **Fear of Abandonment and Need for Cohesion**: Her inclination to prioritize “emotional harmony and cohesion” due to her fear of abandonment further defines her as a unifying force, shaping her role around keeping the group stable.

So her Role would likely be: Leader, Protector, and Team Stabalizer

### Expertise

Once again, her **Name** would help out for her Expertise. Beyond that, her **Background** and **Traits** will help determine this:
* **Specific Skills in Witchcraft**: Her expertise in “elemental control, summoning, divination, and healing” directly informs her practical skillset, showing her areas of technical expertise.
* **Leadership and Strategic Thinking**: Her “ability to think outside the box” and tendency toward “innovative spells and strategies” indicate expertise in creative problem-solving and strategic adaptation.
* **Imagination: 90** and **Artistic Interests: 85**, she has high openness, signaling an adaptive and creative approach to her witchcraft.
* **Intellect: 80** and **Achievement-Striving: 75** further solidify her expertise in knowledge acquisition and application.

Her Expertise would likely be: Witchcraft, Strategist, Researcher, Innovator

### Communication

Like Expertise, while the **Name** might help hint at Tone & Style, most of clues will come from the **Background** and **Traits**.
* **Emotional Tone from Background**: Her “empathy,” “mindfulness,” and “supportive” nature, balanced with vulnerabilities like burnout and stress, shape her tone as warm but somewhat cautious. The influence of her “fear of abandonment” suggests a sensitivity to others’ emotional states, implying a nurturing tone.
* **Emotionality: 80** and **Sympathy: 80** suggest an emotionally resonant tone
* **Neuroticism: 75** with elements like **Anxiety: 70** and **Vulnerability: 75** introduce a guarded, cautious edge, likely making her tone both empathetic and slightly restrained.
* **Artistic Interests: 85** and **Imagination: 90** hint that her communication style is expressive and likely metaphorical
* **Agreeableness: 70** and **Friendliness: 85** imply she maintains a style that’s approachable and warm.
* **Cautiousness: 40** means she may speak more directly at times, particularly when her protective instincts are activated.

Nico's Tone would: Warm, Emotionally Resonant, Empathetic
Nico's Style would be: Cautiously Restrained, Metaphorical, Espressive, Direct when Protective

## 3CPP vs 0CPP

I will always stress the importance of understanding the Personality Matrix and the 3 components. But when you understand them together, 0CPP can still be quite efficient. Now of course, this requires a lot of processing to accomplish, but the beauty of Arcanas is there is more data to pull from to determine the Role, Expertise, and Communication, unlike 2CPP and 1CPP which often has to rely on the context within the prompt.

Now, could you use define Role, Expertise, and Communication along with using an Arcanas. Yes, you could. Then why don't I do that? It would work. The reason I don't is that this is meant for beginners and sometimes (not always) when I make use of the three components with the Arcanas, it focuses more on the 3 components and less on the fictional character it's representing, or that it is a *watered down* version of the fictional character. 

Like I said, somethings that happens, but other times it does it flawlessly. Mostly it is when I try to set a Role, Expertise, and Communication that conflicts with fictional character along with the context I want to use. That can be resolved utilizing special techniques, which you will learn getting into more advanced designs beyond Arcanas. 
