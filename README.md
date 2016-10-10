Bukdu 🌌  on Heroku
==================


* Go to the demo site =>  https://bukdu.herokuapp.com


------------------

[Bukdu](https://github.com/wookay/Bukdu.jl) is a web development framework for Julia (http://julialang.org).

It's influenced by Phoenix framework (http://phoenixframework.org).

You can run Bukdu on [Heroku](https://www.heroku.com/).

 * Heroku: Create new app like this.

   - [heroku-bukdu](https://github.com/wookay/heroku-bukdu)

 * Heroku: Add two buildpacks on **Settings** -> **Add buildpack**

   - [https://github.com/rcaught/heroku-buildpack-cmake](https://github.com/rcaught/heroku-buildpack-cmake)

   - [https://github.com/wookay/heroku-buildpack-julia](https://github.com/wookay/heroku-buildpack-julia)

  ```sh
λ ~/work/heroku-bukdu $ heroku buildpacks
=== bukdu Buildpack URLs
1. https://github.com/rcaught/heroku-buildpack-cmake
2. https://github.com/wookay/heroku-buildpack-julia
```

 * Get more information: [https://devcenter.heroku.com/categories/deployment](https://devcenter.heroku.com/categories/deployment)
