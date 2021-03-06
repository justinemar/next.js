[![Deploy to now](https://deploy.now.sh/static/button.svg)](https://deploy.now.sh/?repo=https://github.com/zeit/next.js/tree/master/examples/with-react-md)

# Example app with react-md

![Screenshot](https://cloud.githubusercontent.com/assets/304265/22472564/b2e04ff0-e7de-11e6-921e-d0c9833ac805.png)

## How to use

### Using `create-next-app`

Download [`create-next-app`](https://github.com/segmentio/create-next-app) to bootstrap the example:

```
npm i -g create-next-app
create-next-app --example with-react-md with-react-md-app
```

### Download manually

Download the example [or clone the repo](https://github.com/zeit/next.js):

```bash
curl https://codeload.github.com/zeit/next.js/tar.gz/canary | tar -xz --strip=2 next.js-canary/examples/with-react-md
cd with-react-md
```

Install it and run:

```bash
npm install
ln -f -s ../node_modules/react-md/dist/react-md.light_blue-yellow.min.css static/react-md.light_blue-yellow.min.css
npm run dev
```

Deploy it to the cloud with [now](https://zeit.co/now) ([download](https://zeit.co/download))

```bash
now
```

## The idea behind the example

This example features how you use [react-md](https://react-md.mlaursen.com/) (React Material Design) with Next.js.

I recommend reading [layout-component](../layout-component) example next to learn how to reuse the layout across the pages.
