# JAMstack & Gatsby

![Back to The Future Animation](//media.giphy.com/media/xp0zPWfyPTlYI/giphy.gif)

Simon Hopstätter    
05 / 2019

---

## Agenda

- How web architecture evolved
- JAMstack
- Gatsby
- Pros & Cons
- Code!

---

## Late 1990s to early 2000s: Static Websites

![Static Websites with MS Frontpage](./frontpage.jpg)

---

## Since late 2000s: Dynamic Websites

![Dynamic Websites with Wordpress](./wordpress_screenshot.png)

---

## Wordpress

- Powering **33% of the web**
- Almost 50% of these sites are hosted on wordpress.com
- wordpress.com has 142M unique visits per month

## Downsides

- Resources: Webservers, FTPs, Databases
- Less than 1/3 are updated to the latest version
- Many sites are abandoned

---

![JAMstack](./jamstack.png)

---

## Architecture

![Traditional Web vs. JAMstack workflow](./traditional-web-vs-jamstack.jpg)

---

## Workflow

![Dynamic Site vs. JAMstack workflow](./jamstack-vs-wordpress.png)

---

## Gatsby

![Gatsby Architecture](./gatsby-architecture.png)

---

## Why Gatsby is great

- Performance!
- PWA out-of-the-box
- Starters (& soon themes)
- Lots of plugins for data sources, e.g. Wordpress
  - Fully progressive & responsive image component
  - Markdown & MDX
  - Headless CMS, e.g. netlify-cms or Contentful
- Documentation

---

## JAMstack & Gatsby in a nutshell

- Write content in React/JS/HTML or MDX 💖
- Push changes to remote git repository
- Everything else can be automated
  - Build site using a static site generator (Gatsby)
  - Deploy to CDN hoster (Netlify)
- Site is live!

---

## Advantages

- Performance
  - Everything is precompiled and handled client-side
  - CDNs serve pages faster than dynamic webservers
- Security
  - No database or webserver required
  - Literally nothing to attack
- Developer-friendly
  - Just work with git
  - Building & deployment are decoupled & automated
  - CDN takes care of cache invalidation
  - External authoring with headless CMS is possible

---

## Disadvantages

- Every change requires a new build
- Not suited for every web application
  - Complex SPAs
  - Sites relying heavily on access control

---

## Code!

![Live Demo](./live-demo.jpg)

---

## That's it

![The Great Gatsby Animation](//cdn.vox-cdn.com/thumbor/t2xNU6eTG3xvDr80Z5ssWb_9EYE=/0x0:800x333/920x613/filters:focal(336x103:464x231):no_upscale()/cdn.vox-cdn.com/uploads/chorus_image/image/55278743/gatsby.1497548146.gif)

Any questions or remarks?