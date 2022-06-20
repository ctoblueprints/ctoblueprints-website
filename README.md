# CTO Blueprints website

[ctoblueprints.com](https://ctoblueprints.com) lists resources for building engineering organizations.

We welcome contributions to templates or submissions of new templates, please do so by submitting a PR.

To run locally 
`npm install`
`npm run start`

To deploy:
You will need the AWS CLI https://aws.amazon.com/cli/
`npm run export`
Then upload to the S3 bucket. Normally this is done with the deploy.sh script, which is not distributed as part of this repo.


## Theme from 
[Netlify Next.js Blog Template designed by Bejamas](https://github.com/netlify-templates/nextjs-blog-theme)

Which is a customizable blog starter using:

- [Next.js](https://github.com/vercel/next.js) v12
- [Tailwind](https://tailwindcss.com/) v3.0
- Built-in [MDX](https://mdxjs.com/) v1 support
- Includes modern design with dark & light themes



## Adding new posts
All posts are stored in `/posts` directory. To make a new post, create a new file with the [`.mdx` extension](https://mdxjs.com/).
Since the posts are written in `MDX` format you can pass props and components. That means you can use [React components](https://reactjs.org/docs/components-and-props.html) inside your posts to make them more interactive. Learn more about how to do so in the [MDX docs on content](https://mdxjs.com/docs/using-mdx/#components).
