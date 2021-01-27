# tylerkrop.github.io

This is my repository for holding the source code to my GitHub Pages website.
I decided to use GitHub Pages to host my website because it offers serverless hosting for free and is very intuitive.
I also wanted to take advantage of using Codespaces as a development environment.
This enables me to develop my website from virtually any machine with a reliable internet connection.
Feel free to copy my setup.

I chose four main technologies for this website.
- [Typescript](https://www.typescriptlang.org/)
- [Next.js](https://nextjs.org/)
- [Chakra UI](https://chakra-ui.com/)
- [GitHub Pages](https://pages.github.com/)

I chose to use Typescript as the primary language for my website because it enhanced my development experience a lot.
The strong typing, auto-completion, and compilation error catching make it a must-have for my environment.
Codespaces uses the web-based version of Visual Studio Code which has wonderful integration with Typescript.

Next.js was chosen as my JavaScript framework because I wanted to use a reliable React-based framework.
Next.js was build to enhance React and my existing React knowledge translated well into the using the technology.
It was also a requirement of mine to have realiable, actively-supported SSG.
This would allow me to host to GitHub Pages without any issues.
Next.js has strong support for SSG and dynamic route handling which made it the best choice for my hosting solution.

I am really bad at CSS.
This is mostly due to my lack of experience in it, but I also just do not find it fun to work with.
I wanted a design system that could allow me to write as little CSS as possible and allow for some tweaking.
Chakra UI was my solution.
This design system provides stylized React components that are easy to tweak and adhere to a standard that it easy to follow.
The inclusion of easy Dark Mode switching was an added bonus.

GitHub Pages was the easiest choice for my hosting solution since it is provided entirely free for users.
It is a very elegant solution for hosting static sites which was my target.
It also has good support and GitHub Actions to make CD a breeze.

# Development

To develop this repo, simply open the repo in a Codespace and run `npm run dev`.
Any merges to `main` will automatically be deployed to GitHub Pages via GitHub Actions.
