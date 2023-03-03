# signUpForm

03/03/2023:
Tried layering a div on top of the sidebar image but it kept messing up the shape of the image. I am realizing more and more that you need to put things in a wrapper. I don't quite know the full extent of why but it does seem to correct a lot of issues.
---
Next time I work on this I should redo the whole side bar from scratch since I think my patchwork is not getting me anywhere.

02/03/2023:
Add the external font type and logo. Then you're done... probably.
---
I put the box into the website but need to have it layer itself on top. This doesn't seem hard but I don't want to spend any more time on this right now.

01/03/2023:
I don't want to fuck around with small things so I'm just going to change the button style to match with a forest green color and a shadow. Not much time today so that's probably it.

28/02/2023:
Fix the div and wrapper background color so that it paints the whole div and not just the wrapper within it. I am assuming there is a margin that is not being painted so I will need to investigate further.

27/02/2023:
I'm going to add colour to the form boxes and give a shadow to the field box.
---
Maybe I should create a structure for the colours and font styles separately so that I can address them all with a few classes in a single section instead of adding them whenever I think of them inside the CSS file.
---
Something like:
<!-- Colors -->
All colors will be addressed within this section
<!-- Font -->
All font will be addressed in this section
<!-- Maybe Spacing -->
All general spacing will be addressed here.
---
This way, I have a general sense of where to find the thing I'm looking for when applying style or wanting to change the style. This also makes me think that I should have some sort of glossary or something.
---
I colored a couple boxes but my margins are fucking up the spacing. I'll have to figure out how to address that. The shadow I added was a fuck around too but it's working at least.

26/02/2023:
Going to put the text in a wrapper too to work on the spacing.
---
CSS is confusing. I never know when it's going to apply the style I want or not.

25/02/2023:
I have to assign columns and rows to the fields again today. I was adding a column and row class to each element and targeting that class to assign things but I can target the my specific class instead. I don't need additional classes just to assign a grid layout.

24/02/2023:
I'm going to fix how big the input fields are and label them.
---
I realized that I was making a class name just to set items into a grid but I can just select all the class names that I need and define the grid row or column. I'm not sure if that's smart or not but I'm changing everything to do it like that.

23/02/2023:
Post Coding: I'm slowly plugging away at this page but this dev journal is annoying...

21/02/2023:
Pre Coding: Add all the interactionable objects into the page, buttons, input fields, images, and text place holders.
Post Coding:
Thoughts:

20/02/2023:
Pre Coding: Make a div that holds everything and has a padding so the content is more centralized. I think it should be simple to make the spacing but adjusting how it flexes will be the challenge.
---
Post Coding: I think the bones are done, I just need to add some muscle to the framework.This was much more simple than I thought it would be. I am really happy with the results and don't think there is anything further that needs to be done for the bones.
---
Thoughts: I will need to add some buttons and the image to this tomorrow. I'm suspecting the image will give me issues again but I've done it once already so hopefully it's not to bad. The buttons should be easy. Oh, and input fields.

19/02/2023:
Pre Coding: Continuing to add to the framework. I am going to add the three sections in the form section which will be the end of the structure. From there, I can add the text and buttons.
---
Post Coding: That was really simple and I'm happy with how it came out. I do think that I need to restrict some sizing so that when the page grows or shrinks the website has a general look to it. I won't be manipulating the site to consider phones.
---
To Do: Create a min and max size for the whole container so that the page can adjust a bit but not too much. The sidebar should adjust itself first until it is completely invisible and then the form should shrink a bit but never to the point that it stacks the input fields. Maybe I will adjust it for phones if it's a reasonable process.

18/02/2023:
Pre Coding: So I mentioned making the structure in my last To-Do, I thought that I should break it down into the "bones, muscle, skin, and brain". The bones is the structure, the muscle is the interactionable objects, the skin is the colouring and styles, and the brain is the functions. I feel like previously I have been working outside in where I work on one thing until completion and then hope it fits with the next thing I work on. I am trying to form a workflow that works for me.
---
Thoughts: I think the way I set up the bones is making a "framework" with a unique class name so that I can apply style to it but later delete these values. From there I'll lay the website out and then replace some values.
---
To Do: Continue adding to the framework until the structure exists, then add the text fields, button, and image (the muscle), and finally, correct the colors and spacing (the skin).

17/2/2023:
I struggled to fit a very large image into the sidebar of the page. I wanted it to take up the space that the grid outlined by default but the grid would flex to accommodate the image. I then added overflow:hidden; to try and force the image to lose adapt to the cell size but I couldn't figure out it. I ended up using chatGPT to write code that kind of works but I don't like it.
TO DO:
Make the structure of the form to have a general sense of spacing. I should also consider writing up a workflow and template so I have a plan instead of moving from one thing to the next naturally. It leaves room for mistakes later in the project.

15/02/2023:
I broke down the website into thirds and imported the sidebar image.
To Do:
I'll need to use the two right most columns to place to form in and make sure that they don't stretch the sidebar image but layers overtop I think.