<a href="https://github.com/3loka/nextjs-aws-s3-stack"><img src="./.github/stacks/use-stack-button.svg"/></a>

<img src="https://upload.wikimedia.org/wikipedia/commons/8/8e/Nextjs-logo.svg" alt="Hugo" width="200" height ="100"/>  

 <p>
    <img src="https://assets.vercel.com/image/upload/v1607554385/repositories/next-js/next-logo.png" height="20">
    <img src="https://avatars.githubusercontent.com/u/6844498?s=200&v=4" height="20">
    <b>Use this stack</b> to spin up a static website in seconds and deploy to AWS S3.
</p>


## Why should you use this stack?
You can spin a website in seconds using NextJS. This stack uses the OIDC flow which means you dont have to store the AWS credentials as Github Secrets. The necessary setup will be done by the Stack itself by creating roles and Setting up trust relationship. The stack will ask for AWS Credentials but that is not stored anywhere and is used only for Setup purposes.

Next.js gives you the best developer experience with all the features you need for production: hybrid static & server rendering, TypeScript support, smart bundling, route pre-fetching and more. No config needed. Read more about [next.js](https://nextjs.org/learn)

The website is hosted in AWS S3. 

The stack also sets up a proper Github CI/CD environment by taing care of the following things
- creating a "main" branch


## What are the inputs to pass while setting up the stack?
```
- AWS S3 Bucket Name
- AWS S3 Key
- AWS S3 Secret Access Key
- Use Existing Bucket?
- AWS Role Name
```

#### Github apps installed with this stack
None

## How to setup local development server?
```
# Start by using github-codespaces developer environments 

# or alternatively start a local development environment.
npm run dev
open http://localhost:3000 

# to run tests
npm test

# to generate a production build
npm run build
```

## Learn more 

### Nextjs
Learn more about [next.js](https://nextjs.org/learn) from the official tutorial.
Visit [https://nextjs.org/docs](https://nextjs.org/docs) to view the full documentation.

## Other Useful links

#### Security guide
Please see our guide lines for reporting issues related to [security.md](/.github/stacks/security.md).

#### Contributor guide
Please see our guide lines for [contributing.md](/.github/stacks/contributing.md).

## Contributors 
- Trilok Ramakrishna ([@3loka](https://twitter.com/3loka))

## License
Unless otherwise noted, this GitHub Stack is distributed under the Apache Version 2.0 license found in the LICENSE file.
