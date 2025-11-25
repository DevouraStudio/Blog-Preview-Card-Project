# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge:

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshots:

![Desktop](/Screenshot.png)
![Mobile](/Screenshot2.png)

### Links:

- Solution URL: [solution URL](https://github.com/DevouraStudio/Blog-Preview-Card-Project)
- Live Site URL: [live site URL](https://devourastudio.github.io/Blog-Preview-Card-Project/)

## My process

### Built with:

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Box Shadow
- Desktop-first workflow
- CSS Media Queries
- [Bootstrap](https://getbootstrap.com/) - CSS Framework

### What I learned:

"Through This Project, I Gained Valuable Experience And Enhanced My Technical Skills. Specifically, I Learned How To Implement Simple Bootstrap Cards, Which I Successfully Applied Within The Project. Additionally, I Worked With Important CSS Features That I Had Not Used Before, Such As Box-Shadow. Consistent Practice With HTML And CSS Further Helped Me Strengthen My Ability To Create Responsive Designs.

One Of The Main Challenges I Encountered Was Applying Images In A Responsive Manner, Along With Effectively Using Box-Shadow. Despite These Difficulties, The Project Provided An Excellent Opportunity To Practice And Deepen My Knowledge Beyond My Usual Scope. Overall, This Experience Contributed Significantly To My Growth In Web Development."

```html
<div class="card">
		<img src="https://i.postimg.cc/YShngcLk/illustration-article.jpg" alt="Illustration-Article" class="img-fluid" id="First">
		<div class="card-body">
			<span class="badge">Learning</span>
			<div class="card-title">
				<h2 class="h2">Published 21 Dec 2023</h2>
				<h1 class="h1">HTML And CSS Foundations</h1>
			</div>
			<div class="card-text">
				<p class="lead">
					These Languages Are The Backbone Of Every Website, Defining Structure, content and presentation.
				</p>
			</div>
			<div class="container">
				<img src="https://i.postimg.cc/zGMMxXr3/image-avatar.jpg" alt="Image Avatar" class="img-fluid d-inline" id="Second">
				<span class="d-inline">Greg Hooper</span>
			</div>
		</div>
	</div>
```
```css
h1.h1:hover {
	color: hsl(47, 88%, 63%);
	transition: color 1s ease;
}

@media (min-width: 375px) and (max-width: 1200px) {
	body {
		padding: 15rem 2rem;
	}
}
```

### Continued development:

"Moving Forward, I Aim To Advance My Expertise In Bootstrap, Enabling Me To Develop Projects Independently Without Relying On Documentation, And To Deliver Work Of Higher Quality And Sophistication.

Furthermore, Mastering Code Responsiveness Remains A Crucial Objective. By Enhancing My Skills In Both CSS And Bootstrap, I Intend To Implement Responsive Designs With Greater Efficiency And Precision.

Finally, Achieving A Comprehensive Understanding Of CSS Measurement Units Is Essential For Writing Accurate And Maintainable Code. I Plan To Deepen My Knowledge In This Area To Apply These Concepts More Effectively In Future Projects."

### Useful resources:

- [MDN](https://developer.mozilla.org/en-US/) - "During This Project, I Frequently Referred to the Mozilla Developer Network (MDN) Website as a Trusted Resource for Learning and Clarifying HTML, CSS, and JavaScript. MDN Provided Clear Documentation, Practical Examples, and Best Practices That Helped Me Solve Challenges More Efficiently. Using MDN Not Only Improved My Technical Accuracy but Also Strengthened My Confidence in Applying Modern Web Standards to My Work."

- [ChatGPT](https://www.chatgpt.com/) - "Throughout This Project, I Benefited Greatly From the Guidance and Support Provided by ChatGPT. From Explaining Complex HTML, CSS, and Bootstrap Concepts to Offering Practical Code Examples and Debugging Advice, ChatGPT Helped Me Overcome Challenges More Efficiently. It's Clear Explanations and Creative Suggestions Played a Key Role in Improving My Skills, Building My Confidence, and Ensuring the Project’s Overall Quality."

- [Bootstrap](https://getbootstrap.com/) - "In This Project, I Utilized Bootstrap to Streamline the Design Process and Enhance the Visual Appeal of My Pages. By Leveraging Bootstrap’s Pre-Built Components, Utility Classes, and Customization Options, I Was Able to Maintain Consistent Styling, Organize Content Effectively, and Apply Modern Web Design Techniques More Efficiently. Using Bootstrap Helped Me Focus on Creativity and Attention to Detail While Building the Project."

- [Gemini](https://gemini.google.com/) - "Google Gemini greatly assisted me in this coding project by providing guidance on Bootstrap and CSS. It helped me troubleshoot issues, explore creative customization options for accordions, and apply measurement units like vh and rem effectively, making my code more responsive and professional."

## Author

- Website - [DevouraStudio](https://www.devoura.ir)
- Frontend Mentor - [@DevouraStudio](https://www.frontendmentor.io/profile/DevouraStudio)
- Github - [@DevouraStudio](https://www.github.com/DevouraStudio)
- Codepen - [@DevouraStudio](https://www.codepen.io/DevouraStudio)
