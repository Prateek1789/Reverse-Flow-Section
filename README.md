# Reverse-Flow-Section
This is a small project inspired by a website I saw on Awwwards.com called Q-Industrial. 
While navigating through the website what caught my attention was the scroll animation in the Services page where the height of each service row animates/increases against the normal document flow. As we scroll through the secton the height of each service row beautifully animates upwards whitout pushing down the content below.
I liked this scroll animation so much that I wanted to re-create this with pure CSS only 😁.
To achieve this animation:
    1. We need a flex container with flex direction 'column-reverse'
    2. Now, 'column-reverse', as the name suggests reverses the flow of content inside the flex container. When we add things inside the container it goes form bottom to top, kinda like stack data structure where we place one itm first and then second on top of it. 
    3. We need to use 'order' property to reverse the order to match the HTML structure. 
    4. Create keyframe animation to animate height of the row container and width of the image. 
    5. And done 🤩 🎉!!  