# CSS layout

# Description

## Phase 1 - playground

(2 hours)

In the first phase students are invited to use the online games to get familiar with grid and flex layout methods.

- [Flexbox Froggy]( https://flexboxfroggy.com/)
- [Grid Garden](https://cssgridgarden.com/)

Then we can discuss the advantages to use one method over another (try to give concrete examples). See Mozilla's guide [Relationship of grid layout to other layout methods](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Relationship_of_Grid_Layout).

# Phase 2 - getting serious

(4-8 hours)

In this second phase students need to apply the layout methods grid and flex to replicate mockups using their IDE and pur CSS.

Methodology:

0. The mockups to replicate are located inside the ```resources``` folder
1. Create a unique folder for each of the layouts (like separate projects) containing a ```index.html``` and ```style.css``` file.
2. For each layout, create a HTML structure using ```<div>```.
3. Then use CSS to apply a style to the ```<div>``` using ```background-color()``` and organise them to re-create the layout of the image. Since there is no content inside the ```<div>```, we will need to set their dimensions in ```px``` or ```%``` so that they appear on screen.
4. Repeat the operation for each layout using either grid or flex methods (or both).

# Phase 3 - real world

(16 hours)

In this final phase students get to recreate the entire home page from an existing website using what they've learnt before. The website can be chosen by the students depending on their interest within a selection made by their teacher, or they can look up for other website and start upon validation by their teacher.

Suggested websites:
- [https://ars.electronica.art/news/en/](https://ars.electronica.art/news/en/)
- [https://www.esa.int/](https://www.esa.int/)
- https://www.factmag.com/
- ...

Methodology:

1. Plan before executing: use pen and paper to break down the sections of the website, DOM structure and which layout method is preferred for each section / sub-section. Get validation before coding.
2. Start coding
3. Regular checkups: students share their progress and struggles to the rest of the group, we debug together
4. In the end, students share their final results

Resources:
- [https://cssgrid-generator.netlify.app/](Grid Generator)
- [https://cssflex-generator.netlify.app/](Flex Generator)

Notes:
- setting a fixed size to ```<div>``` as we did in phase 2 is not best practice when developing a real site, as the natural behaviour (which is to fit the size of its content) can be preferred depending on the situation. Students need to be aware of this.
- When making a real website from scratch, students need to be aware of the nature of the content they are dealing with to make relevant choices. For instance, there can be the temptation to use a grid for the whole website, whereas it would be more advised to break it down by sections. I've seen this mistake a lot, so before creating a full website from scratch students needs to plan on how they will break down the sections before going into the code.

