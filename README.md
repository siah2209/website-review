# website-review
This was college project for my interface design class. The goal was to make an interface for a specific purpose and our topic was website opinions via sentiment analysis.


## Overview
The Website Evaluation Tool is a web-based application that allows users to review, rate, and leave feedback on websites based on usability, design, performance, and overall satisfaction. This project is designed to give users a platform to express their experiences and offer suggestions for improving website usability. In future phases, user input will be analyzed using sentiment analysis to assist developers in making data-driven improvements.

## Features (In Progress / Planned)

- Website Rating System — Star-based rating with categorized feedback (navigation, speed, accessibility, etc.)
- User Comments — Comment section for more detailed feedback
- Sentiment Analysis — Planned feature to analyze tone (positive, neutral, negative)
- Review Display — Users can browse other reviews to learn more about a site's user experience
- Feedback Update — Users can return and revise previous ratings if the site improves
- Survey-Based Research — Insights gathered from real users through interviews and forms

## User Research & Evaluation

We conducted:
- 4 semi-structured interviews
- 16-user survey analyzing opinions on web usability and feedback tools

### Key Findings:
- 68% of users want to see reviews before visiting a website
- Users value fast loading times, intuitive navigation, and accessible design
- Some users want to judge websites for themselves but appreciate the option to leave feedback afterward

### Personas:
- **Alex Carter**: A marketing specialist who values structured, transparent feedback systems
- **Sarah Johnson**: A web developer who wants meaningful user insights to guide site improvements

## Typical Use Case Interactions

1. **User Activates Tool** — Launch via browser extension or web interface
2. **User Provides Feedback** — Star rating and category-based selection, with optional comments
3. **Sentiment Analysis (Planned)** — System processes comments to assess tone and calculate an overall score
4. **User Browses Other Reviews** — See ratings and comments from past users
5. **User Revisits Website** — Updates review to reflect changes in experience

## Tech Stack (Planned)

- Frontend: HTML/CSS, JavaScript (React or Vanilla JS)
- Backend: Flask / Node.js / Django (TBD)
- Database: MongoDB / Firebase / PostgreSQL
- NLP (Planned): TextBlob, NLTK, or HuggingFace Transformers
- Hosting: GitHub Pages, Render, or Heroku

## Future Goals / Wishlist
Would Love to fully implement this
- Build out sentiment analysis integration
- Create a clean, user-friendly UI
- Allow users to edit/update reviews over time
- Add review filtering/sorting functionality
- Interview more diverse users, including non-technical participants
- Consider developing a browser extension version of the tool

## Project Structure (Coming Soon)



How to use


Demo of a concept website to leave reviews about other websites

First you can check a url of a website you would like to rewiew. You can simply paste a url in then leave an icon, star value, and a comment. 
All these together generate a sentiment score. You can then hit submit at the bottom and click in the to right to view other reviews and filter via sentiment and other factors

With the webiste html file you should be able to click around and even try out the view other reviews button in the top left
