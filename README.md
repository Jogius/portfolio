# portfolio
My small portfolio, presenting who I am and what I do.

# How to use
First of all - why would you ever want to use my portfolio locally on your machine? It doesn't really make any sense, but ... well, you do you, I can tell you how it's done.

## Prerequisites
You need to have a few things installed - namely `NodeJS` with either `npm` or `Yarn`. I personally used NodeJs `v18.10.0` and Yarn `v1.22.19` while developing, but I guess others should work just fine as well. Oh, and it would be helpful to have `git` installed, though it's not really a prerequisite. But if you're using GitHub and looking at the portfolios of other people I would guess you have git and know how to use it.

## Cloning the repository and installing packages
You have everything I just told you about? Great, then you can use

```bash
git clone https://github.com/Jogius/portfolio.git
```

to download the repository. After entering the directory (I won't bother telling you how to to that), you can use

```bash
npm install # if you prefer using npm
yarn install # if you prefer using yarn
```

to download all the packages. You're almost done btw, keep on going!

## Using vite
To develop and build this page, I decided to use [Vite](https://github.com/vitejs/vite), a really cool project for JavaScript (or TypeScript) projects. It makes it really easy to start a development server and build the project.

```bash
npm run dev / yarn dev # = `vite`, running the development server
npm run build / yarn build # = `vite build`, building the static files
```

Et voilà, depending on what you did, you should be able to access the page via http://localhost:5173/ (at least that's the port Vite used for me, but it'll tell you itself...) or see the files in `dist/`.

# License and stuff
I added an MIT License to this because I was told everything should be licensed...it basically means: you do you, I don't really care what you use this for, but don't try to sue me because your multimillion dollar unicorn company lost a bunch of money and reputation after all your capital was invested in Dogecoin through the account information that was somehow leaked due to a fatal security flaw in this page. However, if that did happen, I would like to sincerely apologize and please text me to tell me that story :D