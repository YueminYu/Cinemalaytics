# Cinemalaytics

## Inspiration

We are inspired by the 'for you' features on Spotify.

## What it does

Our website can recommend users with movies based on what they have watched before.

## How we built it

For the frontend, we used Flask as the framework and used HTML, CSS, and JavaScript to build our lovely website. For the backend, we used pandas and machine learning to output the recommended movies based on what the user watched before as the input. Specifically, we used tf and idf vectorization for genres and calculate cosine similarities based on genres. Taking in all these factors combined, we created a machine learning model that was trained on a movie database to give up to five movie recommendations.

## Challenges we ran into

We ran into many challenges as none of us were experienced in any of the technologies used, HTML CSS JavaScript, Python, and Flask. On the frontend, we struggled to come up with a good-looking website. On the backend, we ran into troubles with the machine learning algorithm and manipulating such a large dataset. Integrating the two together with flask was tough as well as it was the first time for all of us to use this python library.

## Accomplishments that we're proud of

We provided the recommended movies not only based on the ratings of the movies from a big data set but also the genres of movies and how they are related to the movies the user watched before.

## What we learned

We have learned a variety of languages and frameworks including HTML, CSS, JavaScript, Python, git version controls, pandas, and Flask. More importantly, we have learned collaborating skills and problem-solving skills.

## What's next for Cinemalaytics

We want to make more pages on the website and also include a filter bar in the input search bar. We are seeking to consider movie descriptions in our ML model which would tokenize certain words and try to match with similar movies in the database using natural language processing We also would like to expand more on the output by adding the movie poster and description for a engaging user experience
