# Named routes example ([next-routes](https://github.com/fridays/next-routes))

## How to use

Download the example [or clone the repo](https://github.com/zeit/next.js):

```bash
curl https://codeload.github.com/zeit/next.js/tar.gz/master | tar -xz --strip=2 next.js-master/examples/with-next-routes
cd with-next-routes
```

Install it and run:

```bash
npm install
npm run dev
```

Deploy it to the cloud with [now](https://zeit.co/now) ([download](https://zeit.co/download))

```bash
now
```

## The idea behind the example

This example uses [next-routes](https://github.com/fridays/next-routes) for dynamic routing, which lets you define parameterized, named routes with express-style parameters matching.

It works similar to the [parameterized-routing](https://github.com/zeit/next.js/tree/master/examples/parameterized-routing) example and makes use of next.js [custom server and routing](https://github.com/zeit/next.js#custom-server-and-routing) possibilities.
