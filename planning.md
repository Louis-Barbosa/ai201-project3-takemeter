## The Community: r/LetsTalkMusic

**Description of Community :** This community is focused on talking all things music. This means that this subreddit isn't tied to any specific genre or artist but talks about all artits, genres, and even the music industry itself. The community makes it clear however that searching for recomendations are relegated to general discussion posts instead of recieving a standalone post. 

**Why this Community? :**  This specific subreddit was chosen mainly due to the fact that music is an art medium that is open to various interpretations and opinoins. So, people could have various opinions and questions about music or artists that could spark up very interesting discussion. It's also an massive topic with countless generes and artists, meaning there is room for endless thoughts and discussions. 

**Lables:**

***Question***: These posts are specifically interested in understanding something better. They provide some context or their current understanding of a specific music topic and then ask the community for more of an explanation. These are typically supposed to have on definitive answer instead of being open-ended. 

Example: "Alright everybody-please break down Deftones for me.
Hey everyone! So, have you ever had an artist who you feel like you should like more than you do? One of those for me is Deftones. Plenty of friends of mine dig them hell some even since we were in high school in the early 2000’s. I try I so truly do but I feel like I need advice on how to listen to them. To like actually hear them. What is there that I’m not hearing? What do you love about them?
I considered if it’s best to cold ask the question without any background about me musically or give more info. And ya know what? I didn’t come to a decision so feel free to ask if it encourages you to answer. They’re challenging to me but I feel like I gotta get some navigational assistance. Thanks!"

***Reviews/Opinion***: These are posts that choose a specific topic, and review or give their experience on the topic. This could be their opionion on an artist, albulm, concerts, or anything related to music.  

Example: 


***Discussion Prompt***: These are for either designated general discussion posts in which users can discuss anything music or for any post that is attempting to ask for people's ideas without specifically arriving at a definitive conclusion.

Example:

**Hard Edge Cases :** Typically the type of posts that will be ambiguous are going to be ones that seem as if they could fit into either Question or Discussion Prompt. The main destinction is that Question posts will have a concrete and definitive answer while Discussion Prompts will ask people for their opinions or thoughts instead of a definitive answer. This will be handled during annotation by focusing on what the seeming intention is behind the post. It's clear that discussion prompts are more focused on having an initial take and seeing what others think while a question typically will  provide a disconnect/misunderstanding that they want an explanation for. 

**Evaluation Metrics :** I think that instead of simply focusing on accuracy I will be focusing on precision within each category. This means that for a specific category, lets say Discussion, out of 50 prompts that are actually discussion it lables 45 of them properly as discussion then the model is working relatively well. However, if  it only get 10 out of the 50 for the discussion lable then the model isn't working quite well. 

**Definition of Success :** My definition of success is a model that is able to near perfectly, around 85% accuracy, label a prompt correctly. This means that it is able to provide a post with a prompt that accuralty matches the contents and intent of the post itself. I would also want to understand why the prompt gives posts the labels they are given.

## AI Tool Plan
For this project, Claude will specifically generating fake posts that sit as a boundary between the different labels. This means I will have it generate about 6 posts per label pairing for the model to end up using to learn the difference between the two labels. I might use an LLM to pre-label the posts before I verify, although I am leaning more towards simply labeling them myselves only. 
