## Field Trip Project

### Project Summary

- This project is about an old **large-format field camera** maybe something like a Graflex speed Graphic camera. It is part of the photography collection at the Museum of Art.  
- The camera is important because it helped people take very clear and detailed photos, especially outside, like in nature or during travel.  
- I chose this artifact because it shows how photography used to work and how it has changed over time and I'm taking a Fill and darkroom class this semester. I loved learn about the whole process.
- The website will help people learn about this old camera through pictures, videos, and fun activities.


### Core Webpages

 **Homepage**
  - A big picture of the camera with a short welcome message.  
  - A simple timeline that shows the history of cameras.  
  - Some short videos that explains why the camera is important.

 **Camera details page**
  - Users can move the camera around in 3D to see it from all sides.  
  - Clickable parts of the camera with short explanations.  
  - Extra pictures that show how the camera was used.

 **Photography history page**
  - Real photos taken with this kind of camera, with short stories about them.  
  - A slider to compare old photos with new digital ones.  
  - A short animation that explains how film photography works.

 **Quiz and games page**
  - Simple quiz to test what users learned.  
  - A drag-and-drop game to label the parts of the camera.  
  - A download area for teachers or students who want extra learning materials.

### Design choices

**Websites I used for inspiration**
  - [The Met’s Online Features](https://www.metmuseum.org/art/online-features): simple design with big pictures and short texts.  
  - [Getty Exhibits](https://www.getty.edu/art/exhibitions/): clean layout with focus on art and history.  
  - [Smithsonian Object Stories](https://americanhistory.si.edu/): example of how to tell the story of an object.


  **Colors palette**
  - **Dark gray #2C2C2C:** (background, like a darkroom)
  - **Ivory white #F8F5F0:** (main color text, easy to read with dark background) 
  - **Brown #704214:** (buttons and titles)
  - **Slate blue #6A7BA2:** (hover effects and small details) 
  - **Light gray #C4C4C4:** (boxes, pop-ups, and extra info)

  ### Data structure 

- I used a JSON format because it is simple and easy to work with when building pages like this project. Each piece of content like the name, year, or images is stored clearly. 
- This makes it easy to load and update information on the site without having to rewrite everything.  

- **Example:**

``` 
    {
      "artifact": {
        "title": "Large-Format Field Camera",
        "year": "About 1915",
        "description": "A wooden camera used by photographers to take clear outdoor photos.",
        "images": ["photo.jpg", "photo2.jpg"],
        "media": {
          "video": example.mp4"
        }
      }

      ```