# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

### Screenshot

![Preview Image](https://user-images.githubusercontent.com/57645180/151640861-de22a5e9-adec-4020-b2b2-9d543bdefe5f.png)


### Links

- Solution URL: [Solution](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ/hub/responsive-profile-card-using-vanilla-css-naYGB_RTd)
- Live Site URL: [Live Site](https://caastech.github.io/profile-card/)

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

