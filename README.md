# Next + Netlify Markdown Blog Starter

This is a lightweight Next.js Markdown Blog, configured so you can one-click install a blog and deploy it to Netlify!

Get started by clicking here:

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/cassidoo/next-netlify-blog-starter)

## The nitty gritty

If you'd like to work with this project locally, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

If you'd like to write a new blog post, write it in Markdown in the `posts` directory.

### Installation options

**Option one:** One-click deploy

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/cassidoo/next-netlify-blog-starter)

**Option two:** Manual clone

1. Clone this repo: `git clone https://github.com/cassidoo/next-netlify-blog-starter`
2. Navigate to the directory and run `npm run dev`
3. Make your changes
4. Connect to [Netlify](https://url.netlify.com/r1j6ybSYU) manually (the `netlify.toml` file is the one you'll need to make sure stays intact to make sure the export is done and pointed to the right stuff)

### Styling

Included are some basic styles with [styled-jsx](https://github.com/zeit/styled-jsx), which is included out of the box with Next.js. Because this uses Next.js 9.3, there's also built-in Sass support and CSS Module support, if you'd prefer to use those.