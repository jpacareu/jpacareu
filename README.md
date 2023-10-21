This is me ;)

```tsx
import React from "react";
import Cuba from "countries/cuba";
import FrontendDev from "developer/frontend";
import FullstackDev from "developer/fullstack";
import {
  Javascript,
  Webpack,
  ReactJS,
  Angular,
  AngularJS,
} from "stacks/frontend";
import { Sass, MaterialUI, Bootstrap } from "stacks/frontend/styles";
import { Jest, ReactTestingLib, Enzyme } from "stacks/testing";
import { NodeJS, Express, NestJS } from "stacks/backend";
import { MySQL, Postgres, MongoDB } from "stacks/databases";
import { GoogleAnalytics, Hotjar } from "stacks/tracking";

const Typescript = Javascript.superset();
const me = new Cuba({
  mama: "Ibis",
  papa: "Francisco",
  brother: "Frank",
  wife: "Leidys",
  son: "Maxi",
  pet: "Pachi",
});

type JPacareuProps = {
  getRestOfAttributes: () => Record<string, unknown>;
};

/**
 * Cuban developer with over 3 years of experience
 *
 * @param {func} getRestOfAttributes Method that receives the rest of the features 
 * you can't cover in a single component ;)
 */
const JPacareu = (props: JPacareuProps) => {
  <Cuban
    name="Javier Pacareu"
    twitter="https://twitter.com/jpacareu"
    linkedin="https://www.linkedin.com/in/javier-pacareu/"
    jobDescription={[<FrontendDev />, <FullstackDev />]}
    stacks={{
      languages: [<Javascript />, <Typescript />],
      frontend: [<ReactJS />, <Angular />, <AngularJS />, <Webpack />],
      styles: [<Sass />, <MaterialUI />, <Bootstrap />],
      testing: [<Jest />, <ReactTestingLib />, <Enzyme />],
      backend: [<NodeJS types={[<Express />, <NestJS />]} />],
      tracking: [<GoogleAnalytics />, <Hotjar />],
      database: [<MySQL />, <Postgres />, <MongoDB />],
    }}
    {...props.getRestOfAttributes()}
  />;
};

export default JPacareu;
```
