# Simple Website

The website shows the poem _Who Has Seen the Wind?_ by Christina Rossetti. The image used to represent the poem is by Markus Spiske.

- Link to Christina Rossetti's [poem](https://poets.org/poem/who-has-seen-wind)
- Link to Markus Spiske's [image](https://unsplash.com/photos/QHQYCrSriPA)

##### Code Attribution for CSS

The template for the code below is from Andy Bell's [presentation](https://www.youtube.com/watch?v=5uhIiI9Ld5M) (Section starts from 25:24 - 28:03)

```
:root {
--flow-space: 3rem;
}

.flow > * + * {
margin-top: var(--flow-space, 1em);
}
```
