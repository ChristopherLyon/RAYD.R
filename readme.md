<p align="center">
  <a href="https://alibaba.github.io/rax">
    <img alt="RAYD.R" src="https://raw.githubusercontent.com/lyon-industries/RAYD.R/1.0.0/public/android-icon-192x192.png" width="66">
  </a>
</p>

<p align="center"> 
  <b>RAYD.R</b> is a 
  <a href="https://nextjs.org">Next.js</a> and 
  <a href="https://mdxjs.com">MDX </a> 
  powered, global repository for meteorological infrastructure.
</p>

<p align="center">
  <a href="https://github.com/lyon-industries/RAYD.R/blob/main/LICENSE"><img src="https://img.shields.io/github/license/lyon-industries/RAYD.R"></a>
  <a href="https://github.com/lyon-industries/RAYD.R/releases"><img src="https://img.shields.io/badge/version-1.0.0-blue"></a>

</p>

---

    

## Crowd Sourced Development

The code of the **RAYD.R Engine** is under the [`core`](https://github.com/shuding/nextra/tree/core) branch.

To contribute to this repository you will need to fork the `main`  repository and make changes to the MDX files under /pages, or to the CSV/JSON data files.

When you are happy with the changes, you can submit a request to merge your branch with the `main` repository. The backend will automatically detect the file changes, and re-compile and redeploy the documentation.


## Data Visualization

The data files will be pulled down and represented using [kepler.gl]("https://github.com/keplergl/kepler.gl"), a data-agnostic, high-performance web-based application for visual exploration of large-scale geolocation data sets. Built on top of Mapbox GL and deck.gl, kepler.gl can render millions of points representing thousands of data points and perform spatial aggregations on the fly.


![](/public/demo.png)

---
:wrench: Created and maintained by Lyon Industries
