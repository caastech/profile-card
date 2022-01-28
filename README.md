# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

### Screenshot

![](./screenshot.jpg)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

The trickiest part of the challenge was the background images positioning, I struggle a lot until I saw a video from Kevin Powell who really help me out to understand the background-image positioning.

```css
body {
    background-color: var(--main-color);
    background-image: url('images/bg-pattern-top.svg'), url('images/bg-pattern-bottom.svg');
    background-repeat: no-repeat, no-repeat;
    background-size: 65%, 65%;
    background-position: top -34vw left -18vw, bottom -42vw right -13vw;
}
```

### Useful resources

- [Kevin Powell Channel](https://www.youtube.com/channel/UCJZv4d5rbIKd4QHMPkcABCw) 

## Author

- Frontend Mentor - [@caastech](https://www.frontendmentor.io/profile/caastech)
- Twitter - [@bleacksubject](https://www.twitter.com/bleacksubject)

